# 🩸 Blood Banking System

A single-page, web-based blood bank management website that connects **donors**, **receivers** (hospitals and patients) and a blood bank **administrator**. Built with plain HTML, CSS and JavaScript, with no frameworks and no build step.

---

## Features

### Public website
- **Home page** with live figures: persons registered as donors, persons who requested blood, total units in stock and low-stock groups
- **Blood inventory and activity table** showing units, donors registered and requests received for each blood group, with Low Stock flags (25 units or fewer)
- **Donor compatibility table** (who can donate to whom)
- Responsive design for desktop and mobile, with automatic dark mode

### Donor
- Registration form: name, age, gender, blood group, phone, city, weight, last donation date, address and health confirmation
- Eligibility checks: age 18 to 65, weight of at least 45 kg, at least 90 days since the last donation, valid phone number
- A **reference ID** (for example `D-PCZG8W`) on every registration

### Receiver (hospital or patient)
- Request form: receiver type, name, contact, city, blood group, units (1 to 20), urgency (Normal, Urgent or Critical), required-by date and details
- A **reference ID** (for example `R-PCZGLM`) on every request

### Admin portal (separate, login protected)
- Separate full-screen admin login, opened from the **Admin Login** button in the top menu
- Sidebar layout with six sections:
  - **Dashboard:** counts, stock level bars, latest requests and donors, blood group overview
  - **Registered Donors:** search, filter, Approve, Reject, Delete and **+1 Donation**
  - **Blood Requests:** urgency, stock check, matching approved donors, Approve, Reject, Delete and **Fulfil**
  - **Inventory:** increase (Add), decrease (Remove) or Set the units for each blood group
  - **Stock Log:** a full history of every stock change (time, group, before and after, change, reason and admin)
  - **Admins:** add or remove admin accounts (only a logged-in admin can do this)
- Fulfilling a request automatically deducts its units; recording a donation adds one unit
- Automatic logout after 15 minutes of inactivity; login locks for 30 seconds after 5 failed attempts

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (Grid, Flexbox, CSS variables, responsive, dark mode) |
| Logic | Vanilla JavaScript (ES2020) |
| Password hashing | Web Crypto API (SHA-256) |
| Data storage | In-memory demo store, or a shared database when hosted on Claude artifacts |

---

## Getting Started

### Run locally
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/blood-banking-system.git
   cd blood-banking-system
   ```
2. Open `blood_bank_portal.html` in any modern browser (double-click it, or serve it with `npx serve`).

When opened locally the page runs in **demo mode**: all data (donors, requests, stock, admins) is kept in memory in that browser tab only and is lost on refresh.

### Project structure
```
blood-banking-system/
├── blood_bank_portal.html   # Complete application (HTML + CSS + JavaScript)
└── README.md
```

---

## How It Works

```
Donor registers ─┐
                 ├─► Admin reviews ─► Approves / records donation ─► Stock +1
Receiver requests ┘                 └► Fulfils request ──────────► Stock −units
                                      (every change is saved in the Stock Log)
```

1. A donor registers and waits for approval.
2. A receiver submits a blood request.
3. The admin logs in, reviews both lists and approves or rejects.
4. When a donor donates, the admin clicks **+1 Donation** and the stock increases.
5. When a request is fulfilled, the units are deducted from stock.

---

## Admin Access

- The default administrator is defined in the code by `DEF_ID` and `DEF_HASH` (the password is stored only as a SHA-256 hash).
- **Change these before deploying.** Generate a new hash with:
  ```js
  // run in the browser console
  const h = async (id, pw) => [...new Uint8Array(await crypto.subtle.digest(
    'SHA-256', new TextEncoder().encode('bbs:' + id + ':' + pw)))]
    .map(x => x.toString(16).padStart(2, '0')).join('');
  h('YOUR_ID', 'YOUR_PASSWORD').then(console.log);
  ```
  Then replace the `DEF_ID` and `DEF_HASH` constants in `blood_bank_portal.html`.

---

## Security Notes

This is a **front-end project**. Please read before using it for anything real:

- The admin login check runs in the browser, so anyone can read the source code and attempt to bypass it. It is a convenience gate, **not real security**.
- Real access control requires a **server-side backend** with authentication, hashed and salted passwords, and role-based database permissions.
- Do not store real personal or medical data with this version.
- All user-entered text is HTML-escaped before display to prevent script injection.

---

## Future Scope

- Backend with REST API (Node.js, Express) and a database (MongoDB or MySQL)
- Server-side authentication with JWT or sessions
- Email and SMS alerts for emergency blood requests
- Donor search by city and blood group
- Export of donor, request and stock reports (CSV and PDF)
- Appointment booking for donation camps

---

## License

Released under the [MIT License](https://opensource.org/licenses/MIT). Free to use for learning and academic projects.

---

## Author

Created by **Vignesh** as a blood donation and inventory management project.
