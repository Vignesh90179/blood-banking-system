<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Blood Banking System</title>
<style>
:root{--red:#b30000;--red2:#800000;--bg:#f5f5f5;--card:#fff;--text:#2b2b2b;--mute:#6b6b6b;--line:#e3e3e3;--soft:#fdeeee;--ok:#1f8a4c;--warn:#d97706;--bad:#c0262d;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#151515;--card:#202020;--text:#ececec;--mute:#a0a0a0;--line:#333;--soft:#2a1a1a;--red:#d12a2a}}
:root[data-theme="dark"]{--bg:#151515;--card:#202020;--text:#ececec;--mute:#a0a0a0;--line:#333;--soft:#2a1a1a;--red:#d12a2a}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,Helvetica,sans-serif}
body{background:var(--bg);color:var(--text)}
header{background:var(--red);color:#fff;padding:0 32px;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;position:sticky;top:env(safe-area-inset-top,0px);z-index:5}
header h1{font-size:22px;padding:14px 0}
nav{display:flex;flex-wrap:wrap}
nav a{color:#fff;padding:18px 16px;font-weight:bold;font-size:14px;cursor:pointer;border-bottom:3px solid transparent}
nav a:hover{background:rgba(255,255,255,.12)}
nav a.on{border-bottom-color:#fff}
.view{display:none}.view.on{display:block}
.hero{background:linear-gradient(rgba(120,0,0,.82),rgba(120,0,0,.82)),#600;color:#fff;text-align:center;padding:70px 20px}
.hero h2{font-size:40px;margin-bottom:14px}
.hero p{font-size:18px;max-width:680px;margin:0 auto 26px}
.btn{display:inline-block;background:var(--red);color:#fff;border:0;padding:11px 22px;border-radius:5px;font-weight:bold;font-size:14px;cursor:pointer}
.btn:hover{background:var(--red2)}
.btn.w{background:#fff;color:#b30000}.btn.w:hover{background:#eee}
.btn.sm{padding:6px 10px;font-size:12px}.btn.ok{background:var(--ok)}.btn.gr{background:#777}
section.s{padding:44px 8%}
h2.h{text-align:center;color:var(--red);margin-bottom:8px}
p.sub{text-align:center;color:var(--mute);margin-bottom:28px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:18px}
.card{background:var(--card);border-radius:10px;padding:24px;box-shadow:0 3px 10px rgba(0,0,0,.1)}
.card h3{color:var(--red);margin-bottom:10px}
.card p,.card li{font-size:14px;line-height:1.5;color:var(--mute)}
.card ul{padding-left:18px}
.stat{text-align:center}.stat .n{font-size:32px;font-weight:bold}
.role .ico{font-size:30px;margin-bottom:8px}
.fc{max-width:760px;margin:auto}
.row2{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.fg{margin-bottom:16px}
label{display:block;font-weight:bold;font-size:14px;margin-bottom:6px}
input,select,textarea{width:100%;padding:11px;border:1px solid var(--line);border-radius:5px;background:var(--bg);color:var(--text);font-size:14px}
.chk{display:flex;gap:8px;align-items:flex-start;font-size:13px;color:var(--mute);margin-bottom:16px}.chk input{width:auto;margin-top:2px}
.tw{overflow-x:auto;border-radius:10px;box-shadow:0 3px 10px rgba(0,0,0,.1)}
table{width:100%;border-collapse:collapse;background:var(--card);min-width:560px}
th,td{padding:12px;text-align:center;border-bottom:1px solid var(--line);font-size:13px}
th{background:var(--red);color:#fff}
td.l,th.l{text-align:left}
.tag{font-size:12px;font-weight:bold;padding:3px 9px;border-radius:12px;white-space:nowrap}
.ok{color:var(--ok)}.low{color:var(--warn)}.bad{color:var(--bad)}
.tag.Approved,.tag.Fulfilled{background:#dff3e7;color:#1f8a4c}.tag.Pending{background:#fdeccc;color:#b45309}.tag.Rejected{background:#fbdcdd;color:#c0262d}
.tag.Critical{background:#c0262d;color:#fff}.tag.Urgent{background:#fdeccc;color:#b45309}.tag.Normal{background:var(--soft);color:var(--mute)}
.tabs{display:flex;gap:8px;margin:24px 0 16px;flex-wrap:wrap}
.tabs button{border:1px solid var(--red);background:transparent;color:var(--red);padding:9px 18px;border-radius:5px;font-weight:bold;cursor:pointer}
.tabs button.on{background:var(--red);color:#fff}
.bar{display:flex;gap:10px;margin-bottom:14px;flex-wrap:wrap}.bar input,.bar select{width:auto;flex:1;min-width:140px}
.note{background:var(--soft);border-left:4px solid var(--red);padding:12px 16px;border-radius:6px;font-size:13px;margin-bottom:18px;color:var(--text)}
.acts{display:flex;gap:5px;justify-content:center;flex-wrap:wrap}
.inv{display:flex;align-items:center;justify-content:center;gap:8px}.inv input{width:70px;text-align:center}
.cmp td,.cmp th{padding:9px}
footer{background:#222;color:#fff;text-align:center;padding:20px;margin-top:20px;font-size:13px}
#toast{position:fixed;left:50%;bottom:calc(24px + env(safe-area-inset-bottom,0px));transform:translateX(-50%) translateY(120px);background:#222;color:#fff;padding:13px 22px;border-radius:8px;font-size:14px;transition:.3s;z-index:20;max-width:90%;text-align:center}
#toast.show{transform:translateX(-50%) translateY(0)}
@media(max-width:700px){header{padding:0 12px;justify-content:center}.hero h2{font-size:28px}.row2{grid-template-columns:1fr}}
.admbtn{background:#fff;color:#b30000!important;border-radius:6px;margin:10px 0 10px 10px;padding:8px 14px!important;border-bottom:0!important}
.admbtn:hover{background:#eee!important}
.shell{display:flex;min-height:100vh}
.side{width:240px;background:#1c1c28;color:#fff;flex-shrink:0}
.sb{padding:22px 20px;font-size:18px;font-weight:bold;border-bottom:1px solid #2e2e3e}
.sb small{display:block;font-size:12px;color:#9a9aa8;font-weight:normal;margin-top:4px}
.side a{display:block;padding:14px 20px;color:#cfcfd8;cursor:pointer;font-size:14px;border-left:4px solid transparent}
.side a:hover{background:#25253a}.side a.on{background:#2a2a3e;color:#fff;border-left-color:var(--red)}
.mainc{flex:1;min-width:0;background:var(--bg)}
.topbar{background:var(--card);padding:14px 24px;display:flex;justify-content:space-between;align-items:center;gap:12px;box-shadow:0 1px 4px rgba(0,0,0,.12);position:sticky;top:0;z-index:4}
.topbar b{font-size:18px}.chip{background:var(--soft);color:var(--red);padding:6px 12px;border-radius:16px;font-size:13px;font-weight:bold;margin-right:10px}
.pad{padding:24px}
.two{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:18px;margin-top:18px}
.sbar{display:flex;align-items:center;gap:10px;margin-bottom:10px;font-size:13px}.sbar span{width:34px;font-weight:bold}
.bt{flex:1;height:10px;background:var(--line);border-radius:6px;overflow:hidden}.bt div{height:100%}
.li{display:flex;justify-content:space-between;align-items:center;gap:8px;padding:10px 0;border-bottom:1px solid var(--line);font-size:14px}.li small{display:block;color:var(--mute);margin-top:2px}
.pos{color:var(--ok);font-weight:bold}.neg{color:var(--bad);font-weight:bold}
@media(max-width:800px){.shell{flex-direction:column}.side{width:100%}#sideNav{display:flex;overflow-x:auto}.side a{white-space:nowrap;border-left:0;border-bottom:3px solid transparent}.side a.on{border-bottom-color:var(--red)}}
.strip{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:14px}.strip span{background:var(--card);border:1px solid var(--line);padding:8px 14px;border-radius:20px;font-size:13px}.strip b{color:var(--red)}
.warnbox{background:#fdeccc;color:#7a4a00;border-left:4px solid #d97706;padding:12px 16px;border-radius:6px;font-size:13px;margin-bottom:18px}
</style>
</head>
<body>
<div id="site">
<header>
  <h1>🩸 Blood Banking System</h1>
  <nav id="nav">
    <a data-v="home" class="on">Home</a><a data-v="donor">Donor</a><a data-v="receiver">Receiver</a><a class="admbtn" onclick="openAdmin()">🛡️ Admin Login</a>
  </nav>
</header>

<div id="demoBar" class="note" style="display:none;margin:0;border-radius:0">Demo mode: data is kept only in this browser tab and is not shared. Admin view is open for preview.</div>

<!-- HOME -->
<div class="view on" id="home">
  <div class="hero">
    <h2>Save Lives Through Blood Donation</h2>
    <p>One platform that connects blood donors, receivers (hospitals and patients) and the blood bank administrator for quick and efficient blood availability.</p>
    <a class="btn w" data-go="donor">Become a Donor</a> &nbsp; <a class="btn w" data-go="receiver">Request Blood</a>
  </div>
  <section class="s">
    <h2 class="h">Blood Bank at a Glance</h2><p class="sub">Live figures from donor registrations, blood requests and stock.</p>
    <div class="grid" id="hStats"></div>
  </section>
  <section class="s" style="padding-top:0">
    <h2 class="h">Who Uses the System</h2><p class="sub">Three roles, each with its own responsibilities.</p>
    <div class="grid">
      <div class="card role"><div class="ico">🧑‍🤝‍🧑</div><h3>Donor</h3><ul><li>Registers with personal and health details</li><li>Blood group and last donation date recorded</li><li>Waits for admin approval</li></ul></div>
      <div class="card role"><div class="ico">🏥</div><h3>Receiver</h3><ul><li>Hospital or patient submits a request</li><li>Chooses blood group, units and urgency</li><li>Request is reviewed by the admin</li></ul></div>
      <div class="card role"><div class="ico">🛡️</div><h3>Admin</h3><ul><li>Views every registered donor</li><li>Views every blood request</li><li>Approves, rejects, fulfils and updates stock</li></ul></div>
    </div>
  </section>
  <section class="s" style="padding-top:0">
    <h2 class="h">Blood Inventory &amp; Activity</h2><p class="sub">Units in stock, donors registered and requests received for each blood group. Groups with 25 units or fewer are marked Low Stock.</p>
    <div class="tw"><table id="hInv"></table></div>
  </section>
  <section class="s" style="padding-top:0">
    <h2 class="h">Who Can Donate to Whom</h2><p class="sub">Standard red blood cell compatibility.</p>
    <div class="tw"><table class="cmp" id="cmp"></table></div>
  </section>
</div>

<!-- DONOR -->
<div class="view" id="donor">
  <section class="s">
    <h2 class="h">Donor Registration</h2><p class="sub">Register as a donor. The admin will review and approve your details.</p>
    <div class="card fc">
      <form onsubmit="regDonor(event)">
        <div class="row2">
          <div class="fg"><label>Full Name</label><input id="dName" placeholder="Enter donor name" required></div>
          <div class="fg"><label>Age (18 to 65)</label><input id="dAge" type="number" min="18" max="65" placeholder="Enter age" required></div>
        </div>
        <div class="row2">
          <div class="fg"><label>Gender</label><select id="dGen" required><option value="">Select</option><option>Male</option><option>Female</option><option>Other</option></select></div>
          <div class="fg"><label>Blood Group</label><select id="dBlood" required></select></div>
        </div>
        <div class="row2">
          <div class="fg"><label>Phone Number</label><input id="dPhone" type="tel" placeholder="Enter phone number" required></div>
          <div class="fg"><label>City</label><input id="dCity" placeholder="Enter city" required></div>
        </div>
        <div class="row2">
          <div class="fg"><label>Weight (kg)</label><input id="dWt" type="number" min="45" placeholder="Minimum 45 kg" required></div>
          <div class="fg"><label>Last Donation Date (optional)</label><input id="dLast" type="date"></div>
        </div>
        <div class="fg"><label>Address</label><textarea id="dAddr" rows="3" placeholder="Enter address"></textarea></div>
        <label class="chk"><input type="checkbox" id="dOk" required> I confirm that the details are correct and I am in good health to donate blood.</label>
        <button class="btn" style="width:100%" type="submit">Register Donor</button>
      </form>
    </div>
    <div class="card fc" style="margin-top:18px"><h3>Donor eligibility</h3><ul><li>Age between 18 and 65 years</li><li>Weight of at least 45 kg</li><li>At least 3 months since the last donation</li></ul></div>
  </section>
</div>

<!-- RECEIVER -->
<div class="view" id="receiver">
  <section class="s">
    <h2 class="h">Request Blood</h2><p class="sub">Hospitals and patients can request blood. The admin reviews every request.</p>
    <div class="card fc">
      <form onsubmit="regReq(event)">
        <div class="row2">
          <div class="fg"><label>Receiver Type</label><select id="rType" required><option>Hospital</option><option>Patient / Family</option></select></div>
          <div class="fg"><label>Hospital / Patient Name</label><input id="rName" placeholder="Enter name" required></div>
        </div>
        <div class="row2">
          <div class="fg"><label>Contact Number</label><input id="rPhone" type="tel" placeholder="Enter contact number" required></div>
          <div class="fg"><label>City</label><input id="rCity" placeholder="Enter city" required></div>
        </div>
        <div class="row2">
          <div class="fg"><label>Blood Group Required</label><select id="rBlood" required></select></div>
          <div class="fg"><label>Number of Units</label><input id="rUnits" type="number" min="1" max="20" placeholder="Enter required units" required></div>
        </div>
        <div class="row2">
          <div class="fg"><label>Urgency</label><select id="rUrg"><option>Normal</option><option>Urgent</option><option>Critical</option></select></div>
          <div class="fg"><label>Required By</label><input id="rDate" type="date" required></div>
        </div>
        <div class="fg"><label>Request Details</label><textarea id="rDet" rows="4" placeholder="Reason for the request, ward, doctor name, etc."></textarea></div>
        <button class="btn" style="width:100%" type="submit">Submit Blood Request</button>
      </form>
    </div>
  </section>
</div>

<footer>© 2026 Blood Banking System | Connecting Donors &amp; Receivers &nbsp;|&nbsp; <a onclick="openAdmin()" style="cursor:pointer;text-decoration:underline">Admin Login</a></footer>
</div>

<!-- SEPARATE ADMIN PORTAL -->
<div id="adminApp" style="display:none">
  <div id="admLogin" style="min-height:100vh;display:flex;align-items:center;justify-content:center;padding:20px;background:linear-gradient(135deg,#600,#b30000)">
    <form class="card" style="width:100%;max-width:400px" onsubmit="admLogin(event)">
      <div style="text-align:center;font-size:44px">🛡️</div><h3 style="text-align:center;font-size:22px">Blood Bank Administration</h3>
      <p style="text-align:center;margin-bottom:18px">Authorized personnel only. All stock changes are logged.</p>
      <div class="fg"><label>User ID</label><input id="aId" autocomplete="username" required></div>
      <div class="fg"><label>Password</label><input id="aPw" type="password" autocomplete="current-password" required></div>
      <button class="btn" style="width:100%" type="submit">Log in</button>
      <p id="aErr" class="bad" style="margin-top:12px;font-size:13px;text-align:center"></p>
      <p style="text-align:center;margin-top:12px"><a class="btn gr sm" onclick="closeAdmin()">← Back to website</a></p>
    </form>
  </div>
  <div id="admMain" style="display:none">
    <div class="shell">
      <aside class="side"><div class="sb">🩸 Blood Bank<small>Admin Portal</small></div><div id="sideNav"></div></aside>
      <div class="mainc">
        <div class="topbar"><b id="admTitle"></b><div style="display:flex;align-items:center"><span class="chip" id="admWho"></span><button class="btn sm" onclick="admLogout()">Log out</button></div></div>
        <section class="pad" id="adminBody"></section>
      </div>
    </div>
  </div>
</div>

<div id="toast"></div>

<script>
const G=['A+','A-','B+','B-','AB+','AB-','O+','O-'];
const DEF={'A+':120,'A-':45,'B+':95,'B-':20,'AB+':60,'AB-':15,'O+':180,'O-':25}; // default display values until admin saves stock
const CAN={'O-':G,'O+':['O+','A+','B+','AB+'],'A-':['A-','A+','AB-','AB+'],'A+':['A+','AB+'],'B-':['B-','B+','AB-','AB+'],'B+':['B+','AB+'],'AB-':['AB-','AB+'],'AB+':['AB+']};
const S={donors:[],requests:[],admins:[],stocklog:[],pubD:[],pubR:[],err:{},inv:{...DEF}};
const PUB={donors:'pubdonors',requests:'pubrequests'};
const DEF_ID='2500090179',DEF_HASH='1c32d4159376c542e62c41b86027b42a540ced1426034767ca5bfc40f12594ab';
let db=null,uid=null,dbAdmin=false,session=null,fails=0,lockUntil=0,lastAct=Date.now(),tab='dash',fBlood='',fStat='',fText='';
const $=id=>document.getElementById(id);
const esc=s=>String(s??'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const fmt=t=>t?new Date(t).toLocaleDateString():'';
const fmtT=t=>t?new Date(t).toLocaleString():'';
function toast(m){const t=$('toast');t.textContent=m;t.classList.add('show');clearTimeout(t._h);t._h=setTimeout(()=>t.classList.remove('show'),3400)}

/* Navigation */
function show(v){document.querySelectorAll('.view').forEach(s=>s.classList.toggle('on',s.id===v));document.querySelectorAll('#nav a').forEach(a=>a.classList.toggle('on',a.dataset.v===v));window.scrollTo(0,0)}
document.addEventListener('click',e=>{const v=e.target.dataset&&(e.target.dataset.v||e.target.dataset.go);if(v)show(v)});

/* Data layer: shared db when available, in-memory demo otherwise */
async function add(col,data){
  data.ts=Date.now();data.ref=(col==='donors'?'D-':'R-')+data.ts.toString(36).toUpperCase().slice(-6);
  if(db){if(!uid)throw new Error('no user');await db.doc(col+'/'+uid).set(data);try{await db.doc(PUB[col]+'/'+uid).set({blood:data.blood,ts:data.ts})}catch(e){}}
  else{S[col].unshift({id:'l'+Date.now()+Math.random(),...data});render()}
  return data.ref;
}
async function upd(col,id,p){if(db)await db.collection(col).doc(id).update(p);else{const x=S[col].find(x=>x.id===id);if(x)Object.assign(x,p);render()}}
async function del(col,id){if(db){await db.collection(col).doc(id).delete();try{await db.collection(PUB[col]).doc(id).delete()}catch(e){}}else{S[col]=S[col].filter(x=>x.id!==id);render()}}
async function setGroup(g,nv){
  if(db){const ref=db.doc('inventory/stock');try{await ref.update({[g]:nv})}catch(e){await ref.set({...S.inv,[g]:nv})}}
  else{S.inv={...S.inv,[g]:nv};render()}
}
function sub(){
  const er=k=>e=>{S.err[k]=(e&&e.code)||'error';renderAdmin()};
  const rows=q=>q.docs.map(d=>({id:d.id,...d.data()}));
  db.doc('inventory/stock').onSnapshot(x=>{if(x.exists)S.inv={...DEF,...x.data()};render()},er('inventory'));
  db.collection('admins').onSnapshot(q=>{S.admins=rows(q);renderAdmin()},er('admins'));
  db.collection('pubdonors').onSnapshot(q=>{S.pubD=rows(q);render()},er('pubdonors'));
  db.collection('pubrequests').onSnapshot(q=>{S.pubR=rows(q);render()},er('pubrequests'));
  if(dbAdmin)[['donors','donors'],['requests','requests'],['stocklog','stocklog']].forEach(([c,k])=>db.collection(c).onSnapshot(q=>{delete S.err[c];S[k]=rows(q).sort((a,b)=>(b.ts||0)-(a.ts||0));render()},er(c)));
}
window.addEventListener('load',async()=>{
  try{
    const c=window.claude?await claude.use('db'):null;
    if(c){db=c;const u=await claude.use('user');dbAdmin=u?((await u.canEdit())||(await u.isOwner())):false;uid=u?await u.id():null;sub()}
    else{dbAdmin=true;$('demoBar').style.display='block'}
  }catch(e){dbAdmin=true;db=null;$('demoBar').style.display='block'}
  render();
});

/* Forms */
document.querySelectorAll('#dBlood,#rBlood').forEach(s=>s.innerHTML='<option value="">Select Blood Group</option>'+G.map(g=>`<option>${g}</option>`).join(''));
$('rDate').min=new Date().toISOString().slice(0,10);
const PH=/^\+?[0-9][0-9\s-]{6,14}$/, today=()=>new Date().toISOString().slice(0,10);
async function guard(e,fn){const btn=e.target.querySelector('button[type=submit]');if(btn.disabled)return;btn.disabled=true;try{await fn()}finally{btn.disabled=false}}
async function regDonor(e){
  e.preventDefault();
  await guard(e,async()=>{
    const d={name:$('dName').value.trim(),age:+$('dAge').value,gender:$('dGen').value,blood:$('dBlood').value,phone:$('dPhone').value.trim(),city:$('dCity').value.trim(),weight:+$('dWt').value,last:$('dLast').value,address:$('dAddr').value.trim(),status:'Pending'};
    if(d.name.length<2){toast('Please enter the full name.');return}
    if(!(d.age>=18&&d.age<=65)){toast('Donor age must be between 18 and 65.');return}
    if(!PH.test(d.phone)){toast('Please enter a valid phone number.');return}
    if(!(d.weight>=45)){toast('Donor weight must be at least 45 kg.');return}
    if(d.last){const days=(Date.now()-new Date(d.last))/864e5;if(d.last>today()){toast('Last donation date cannot be in the future.');return}if(days<90){toast('Donors must wait at least 3 months (90 days) between donations.');return}}
    try{const ref=await add('donors',d);toast('Donor Registered Successfully! Reference ID '+ref+'. '+d.name+' ('+d.blood+') is awaiting admin approval.');e.target.reset()}
    catch(x){toast('Could not register. Please make sure you are signed in and try again.')}
  });
}
async function regReq(e){
  e.preventDefault();
  await guard(e,async()=>{
    const r={type:$('rType').value,name:$('rName').value.trim(),phone:$('rPhone').value.trim(),city:$('rCity').value.trim(),blood:$('rBlood').value,units:+$('rUnits').value,urgency:$('rUrg').value,needBy:$('rDate').value,details:$('rDet').value.trim(),status:'Pending'};
    if(r.name.length<2){toast('Please enter the hospital or patient name.');return}
    if(!PH.test(r.phone)){toast('Please enter a valid contact number.');return}
    if(!Number.isInteger(r.units)||r.units<1||r.units>20){toast('Units must be a whole number from 1 to 20.');return}
    if(r.needBy<today()){toast('Required-by date cannot be in the past.');return}
    try{const ref=await add('requests',r);toast('Blood request submitted! Reference ID '+ref+'. The admin will review your request.');e.target.reset()}
    catch(x){toast('Could not submit. Please make sure you are signed in and try again.')}
  });
}

/* Admin actions */
async function setStatus(col,id,st){try{await upd(col,id,{status:st});toast('Marked as '+st)}catch(e){toast('Action not permitted')}}
async function removeRow(col,id){if(!confirm('Delete this record?'))return;try{await del(col,id)}catch(e){toast('Action not permitted')}}
async function addLog(e){e.ts=Date.now();if(db)await db.collection('stocklog').add(e);else{S.stocklog.unshift(e);render()}}
async function applyStock(g,nv,reason){
  const before=S.inv[g]||0;
  try{await setGroup(g,nv);await addLog({group:g,before,after:nv,change:nv-before,reason,by:session||'admin'});return true}
  catch(e){toast('Action not permitted');return false}
}
async function stock(g,mode){
  const n=parseInt($('u_'+g).value),cur=S.inv[g]||0;
  if(!(n>=0)){toast('Enter a valid number of units.');return}
  const nv=mode==='add'?cur+n:mode==='sub'?cur-n:n;
  if(nv<0){toast('Cannot go below 0. Only '+cur+' units of '+g+' available.');return}
  const why=mode==='add'?'Donation received':mode==='sub'?'Units issued / removed':'Stock corrected';
  if(await applyStock(g,nv,why))toast(g+' stock is now '+nv+' units.');
}
async function recordDonation(id){
  const d=S.donors.find(x=>x.id===id);if(!d)return;
  if(d.status!=='Approved'){toast('Approve the donor before recording a donation.');return}
  if(await applyStock(d.blood,(S.inv[d.blood]||0)+1,'Donation by '+d.name)){await upd('donors',id,{last:new Date().toISOString().slice(0,10)});toast('+1 unit of '+d.blood+' added from '+d.name)}
}
async function fulfil(id){
  const r=S.requests.find(x=>x.id===id);if(!r)return;
  if(r.status==='Fulfilled'){toast('This request is already fulfilled.');return}
  if(r.status==='Rejected'){toast('This request was rejected. Approve it first.');return}
  const cur=S.inv[r.blood]||0;
  if(cur<r.units){toast('Not enough '+r.blood+' stock: only '+cur+' units available.');return}
  if(await applyStock(r.blood,cur-r.units,'Request fulfilled: '+r.name)){await upd('requests',id,{status:'Fulfilled'});toast(r.units+' unit(s) of '+r.blood+' issued to '+r.name)}
}

/* Rendering */
const total=()=>G.reduce((s,g)=>s+(S.inv[g]||0),0);
const low=g=>(S.inv[g]||0)<=25;
const cnt=(a,g)=>a.filter(x=>x.blood===g).length;
const pubD=()=>db?S.pubD:S.donors, pubR=()=>db?S.pubR:S.requests;
function render(){
  $('hStats').innerHTML=[['Persons Registered as Donors',pubD().length],['Persons Requested Blood',pubR().length],['Total Units in Stock',total()],['Low-Stock Groups',G.filter(low).length]].map(x=>`<div class="card stat"><h3>${x[0]}</h3><div class="n">${x[1]}</div></div>`).join('');
  $('hInv').innerHTML='<tr><th>Blood Group</th><th>Units in Stock</th><th>Donors Registered</th><th>Requests Received</th><th>Status</th></tr>'+G.map(g=>`<tr><td><b>${g}</b></td><td>${S.inv[g]||0}</td><td>${cnt(pubD(),g)}</td><td>${cnt(pubR(),g)}</td><td class="${low(g)?'low':'ok'}"><b>${low(g)?'Low Stock':'Available'}</b></td></tr>`).join('');
  $('cmp').innerHTML='<tr><th>Donor Group</th><th>Can Donate To</th></tr>'+G.map(g=>`<tr><td><b>${g}</b></td><td>${CAN[g].join(', ')}</td></tr>`).join('');
  renderAdmin();
}
function strip(a,kind){const c=s=>a.filter(x=>x.status===s).length;return `<div class="strip"><span>Total <b>${a.length}</b></span><span>Pending <b>${c('Pending')}</b></span><span>Approved <b>${c('Approved')}</b></span>${kind==='requests'?`<span>Fulfilled <b>${c('Fulfilled')}</b></span>`:''}<span>Rejected <b>${c('Rejected')}</b></span></div>`}
function overview(D,R){return '<div class="tw" style="margin-top:18px"><table><tr><th>Blood Group</th><th>Units in Stock</th><th>Donors Registered</th><th>Requests Received</th><th>Units Requested (open)</th></tr>'+G.map(g=>{const open=R.filter(r=>r.blood===g&&(r.status==='Pending'||r.status==='Approved')).reduce((t,r)=>t+(+r.units||0),0);return `<tr><td><b>${g}</b></td><td>${S.inv[g]||0}</td><td>${cnt(D,g)}</td><td>${cnt(R,g)}</td><td class="${open>(S.inv[g]||0)?'bad':''}"><b>${open}</b></td></tr>`}).join('')+'</table></div>'}
const MENU=[['dash','📊 Dashboard'],['donors','🧑‍🤝‍🧑 Registered Donors'],['requests','🏥 Blood Requests'],['stock','🩸 Inventory'],['log','📜 Stock Log'],['admins','🛡️ Admins']];
function renderAdmin(){
  if(!session)return;
  $('sideNav').innerHTML=MENU.map(m=>`<a class="${tab===m[0]?'on':''}" onclick="tab='${m[0]}';renderAdmin()">${m[1]}</a>`).join('');
  $('admTitle').textContent=MENU.find(m=>m[0]===tab)[1].replace(/^\S+\s/,'');
  const b=$('adminBody');
  if(!dbAdmin&&tab!=='admins'){b.innerHTML='<div class="card fc"><h3>🔒 Lists unavailable</h3><p>You are logged in as an admin, but this Claude account does not have Editor access to the page, so donor, request and stock data cannot be loaded. Ask the page owner to share it with you as an Editor.</p></div>';return}
  const D=S.donors,R=S.requests,pd=D.filter(d=>d.status==='Pending').length,pr=R.filter(r=>r.status==='Pending').length,cr=R.filter(r=>r.urgency==='Critical'&&r.status!=='Fulfilled'&&r.status!=='Rejected').length;
  const keep=document.activeElement&&document.activeElement.id==='fText';
  let h='';
  const filt=a=>a.filter(x=>(!fBlood||x.blood===fBlood)&&(!fStat||x.status===fStat)&&(!fText||(x.name+x.city+x.phone).toLowerCase().includes(fText.toLowerCase())));
  const bar=`<div class="bar"><input id="fText" placeholder="Search name, city or phone" value="${esc(fText)}" oninput="fText=this.value;renderAdmin()"><select onchange="fBlood=this.value;renderAdmin()"><option value="">All blood groups</option>${G.map(g=>`<option ${fBlood===g?'selected':''}>${g}</option>`).join('')}</select><select onchange="fStat=this.value;renderAdmin()"><option value="">All statuses</option>${['Pending','Approved','Fulfilled','Rejected'].map(s=>`<option ${fStat===s?'selected':''}>${s}</option>`).join('')}</select></div>`;
  if(tab==='dash'){
    const ek=Object.keys(S.err);if(ek.length)h+='<div class="warnbox">Some live data could not be loaded ('+ek.map(esc).join(', ')+'). Make sure you opened the page signed in as the owner or an Editor.</div>';
    h+='<div class="grid">'+[['Persons Registered as Donors',D.length],['Donors Pending Approval',pd],['Persons Requested Blood',R.length],['Requests Pending',pr],['Critical Requests',cr],['Total Units in Stock',total()]].map(x=>`<div class="card stat"><h3>${x[0]}</h3><div class="n">${x[1]}</div></div>`).join('')+'</div>';
    h+='<div class="two"><div class="card"><h3>Blood Stock Levels</h3>'+G.map(g=>{const v=S.inv[g]||0;return `<div class="sbar"><span>${g}</span><div class="bt"><div style="width:${Math.min(100,v/2)}%;background:${low(g)?'#d97706':'#1f8a4c'}"></div></div><b>${v}</b></div>`}).join('')+'</div>';
    h+='<div class="card"><h3>Latest Blood Requests</h3>'+(R.slice(0,5).map(r=>`<div class="li"><div><b>${esc(r.name)}</b><small>${esc(r.blood)} · ${esc(r.units)} unit(s) · ${esc(r.status)}</small></div><span class="tag ${esc(r.urgency)}">${esc(r.urgency)}</span></div>`).join('')||'<p>No requests yet.</p>')+'</div>';
    h+='<div class="card"><h3>Latest Registered Donors</h3>'+(D.slice(0,5).map(d=>`<div class="li"><div><b>${esc(d.name)}</b><small>${esc(d.blood)} · ${esc(d.city)}</small></div><span class="tag ${esc(d.status)}">${esc(d.status)}</span></div>`).join('')||'<p>No donors yet.</p>')+'</div></div>';
    h+=overview(D,R);
  }else if(tab==='donors'){
    const L=filt(D);
    h+=strip(D,'donors')+bar+'<div class="tw"><table><tr><th class="l">Donor</th><th>Age / Gender</th><th>Blood</th><th>Phone</th><th>City</th><th>Last Donated</th><th>Registered</th><th>Status</th><th>Actions</th></tr>'+(L.map(d=>`<tr><td class="l"><b>${esc(d.name)}</b> <small>${esc(d.ref)}</small><br><small>${esc(d.address)}</small></td><td>${esc(d.age)} / ${esc(d.gender)}</td><td><b>${esc(d.blood)}</b></td><td>${esc(d.phone)}</td><td>${esc(d.city)}</td><td>${esc(d.last)||'Never'}</td><td>${fmt(d.ts)}</td><td><span class="tag ${esc(d.status)}">${esc(d.status)}</span></td><td><div class="acts"><button class="btn sm ok" onclick="setStatus('donors','${esc(d.id)}','Approved')">Approve</button><button class="btn sm" style="background:#2a6ebb" onclick="recordDonation('${esc(d.id)}')">+1 Donation</button><button class="btn sm gr" onclick="setStatus('donors','${esc(d.id)}','Rejected')">Reject</button><button class="btn sm" onclick="removeRow('donors','${esc(d.id)}')">Delete</button></div></td></tr>`).join('')||'<tr><td colspan="9">No donors registered yet.</td></tr>')+'</table></div>';
  }else if(tab==='requests'){
    const L=filt(R);
    h+=strip(R,'requests')+bar+'<div class="tw"><table><tr><th class="l">Receiver</th><th>Blood</th><th>Units</th><th>Urgency</th><th>Need By</th><th>Contact</th><th>Stock / Donors</th><th>Status</th><th>Actions</th></tr>'+(L.map(r=>{const md=D.filter(d=>d.status==='Approved'&&(CAN[d.blood]||[]).includes(r.blood)).length;return `<tr><td class="l"><b>${esc(r.name)}</b> <small>${esc(r.ref)}</small><br><small>${esc(r.type)} · ${esc(r.city)}</small><br><small>${esc(r.details)}</small></td><td><b>${esc(r.blood)}</b></td><td>${esc(r.units)}</td><td><span class="tag ${esc(r.urgency)}">${esc(r.urgency)}</span></td><td>${esc(r.needBy)}</td><td>${esc(r.phone)}</td><td class="${(S.inv[r.blood]||0)>=r.units?'ok':'bad'}"><b>${S.inv[r.blood]||0}</b> in stock<br><small>${md} matching donors</small></td><td><span class="tag ${esc(r.status)}">${esc(r.status)}</span></td><td><div class="acts"><button class="btn sm ok" onclick="fulfil('${esc(r.id)}')">Fulfil (-${esc(r.units)})</button><button class="btn sm" style="background:#2a6ebb" onclick="setStatus('requests','${esc(r.id)}','Approved')">Approve</button><button class="btn sm gr" onclick="setStatus('requests','${esc(r.id)}','Rejected')">Reject</button><button class="btn sm" onclick="removeRow('requests','${esc(r.id)}')">Delete</button></div></td></tr>`}).join('')||'<tr><td colspan="9">No blood requests yet.</td></tr>')+'</table></div>';
  }else if(tab==='stock'){
    h+='<div class="note"><b>Add</b> records a donation (increases units). <b>Remove</b> records units issued or discarded (decreases). <b>Set</b> corrects the exact count. Fulfilling a request deducts its units, and recording a donor\'s donation adds 1 unit. Every change is saved in the Stock Log.</div><div class="tw"><table><tr><th>Blood Group</th><th>Units Now</th><th>Status</th><th>Change Units</th></tr>'+G.map(g=>`<tr><td><b>${g}</b></td><td><b style="font-size:18px">${S.inv[g]||0}</b></td><td class="${low(g)?'low':'ok'}"><b>${low(g)?'Low Stock':'Available'}</b></td><td><div class="inv"><input id="u_${g}" type="number" min="0" value="1"><button class="btn sm ok" onclick="stock('${g}','add')">➕ Add</button><button class="btn sm" onclick="stock('${g}','sub')">➖ Remove</button><button class="btn sm gr" onclick="stock('${g}','set')">Set</button></div></td></tr>`).join('')+'</table></div>';
  }else if(tab==='log'){
    h+='<div class="tw"><table><tr><th class="l">Date &amp; Time</th><th>Blood Group</th><th>Before</th><th>After</th><th>Change</th><th class="l">Reason</th><th>By</th></tr>'+(S.stocklog.slice(0,100).map(e=>`<tr><td class="l">${fmtT(e.ts)}</td><td><b>${esc(e.group)}</b></td><td>${esc(e.before)}</td><td>${esc(e.after)}</td><td class="${e.change>=0?'pos':'neg'}">${e.change>=0?'+':''}${esc(e.change)}</td><td class="l">${esc(e.reason)}</td><td>${esc(e.by)}</td></tr>`).join('')||'<tr><td colspan="7">No stock changes recorded yet.</td></tr>')+'</table></div>';
  }else{h+=adminsHtml()}
  b.innerHTML=h;
  if(keep){const f=$('fText');if(f){f.focus();f.setSelectionRange(f.value.length,f.value.length)}}
}
/* Separate admin portal: login + admin management */
async function sha(id,pw){const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode('bbs:'+id+':'+pw));return[...new Uint8Array(b)].map(x=>x.toString(16).padStart(2,'0')).join('')}
function openAdmin(){$('site').style.display='none';$('adminApp').style.display='block';window.scrollTo(0,0)}
function closeAdmin(){admLogout();$('adminApp').style.display='none';$('site').style.display='block'}
function admLogout(){session=null;$('admMain').style.display='none';$('admLogin').style.display='flex';$('aPw').value='';$('aErr').textContent=''}
async function admLogin(e){
  e.preventDefault();
  if(!(window.crypto&&crypto.subtle)){$('aErr').textContent='Secure login is not supported in this browser context.';return}
  if(Date.now()<lockUntil){$('aErr').textContent='Too many attempts. Try again in a few seconds.';return}
  const id=$('aId').value.trim(),h=await sha(id,$('aPw').value);
  const ok=(id===DEF_ID&&h===DEF_HASH)||S.admins.some(a=>a.id===id&&a.hash===h);
  if(!ok){fails++;if(fails>=5){lockUntil=Date.now()+30000;fails=0}$('aErr').textContent='Invalid User ID or password.';return}
  fails=0;session=id;lastAct=Date.now();$('aId').value='';$('aPw').value='';$('aErr').textContent='';
  tab='dash';$('admWho').textContent='👤 '+id;$('admLogin').style.display='none';$('admMain').style.display='block';renderAdmin();
}
function adminsHtml(){
  const rows=[{id:DEF_ID,by:'Default administrator',ts:0,def:true}].concat(S.admins.map(a=>({id:a.id,by:a.addedBy||'',ts:a.ts,def:false})));
  return '<div class="note">Only a logged-in admin can add or remove admins. New admins sign in on the Admin Login page with the ID and password set here.</div><div class="tw"><table><tr><th class="l">Admin ID</th><th>Added By</th><th>Added On</th><th>Action</th></tr>'+rows.map(r=>`<tr><td class="l"><b>${esc(r.id)}</b></td><td>${esc(r.by)}</td><td>${r.ts?fmt(r.ts):'-'}</td><td>${r.def?'<small>Protected</small>':`<button class="btn sm" onclick="delAdmin('${esc(r.id)}')">Remove</button>`}</td></tr>`).join('')+'</table></div><br><div class="card" style="max-width:480px"><h3>Add New Admin</h3><div class="fg"><label>New Admin ID</label><input id="nId" placeholder="Letters or numbers, min 4"></div><div class="fg"><label>Password (min 8 characters)</label><input id="nPw" type="password"></div><div class="fg"><label>Confirm Password</label><input id="nPw2" type="password"></div><button class="btn" onclick="addAdmin()">Add Admin</button></div>';
}
async function addAdmin(){
  if(!session)return;
  const id=$('nId').value.trim(),pw=$('nPw').value;
  if(!/^[A-Za-z0-9]{4,20}$/.test(id)){toast('Admin ID must be 4 to 20 letters or numbers.');return}
  if(pw.length<8){toast('Password must be at least 8 characters.');return}
  if(pw!==$('nPw2').value){toast('Passwords do not match.');return}
  if(id===DEF_ID||S.admins.some(a=>a.id===id)){toast('That Admin ID already exists.');return}
  const rec={hash:await sha(id,pw),addedBy:session,ts:Date.now()};
  try{if(db)await db.doc('admins/'+id).set(rec);else{S.admins.push({id,...rec});renderAdmin()}toast('Admin '+id+' added successfully.')}
  catch(e){toast('Only the page owner account can save new admins.')}
}
async function delAdmin(id){
  if(!confirm('Remove admin '+id+'?'))return;
  try{if(db)await db.doc('admins/'+id).delete();else{S.admins=S.admins.filter(a=>a.id!==id);renderAdmin()}toast('Admin removed.')}
  catch(e){toast('Only the page owner account can remove admins.')}
}
['click','keydown','touchstart'].forEach(ev=>document.addEventListener(ev,()=>{lastAct=Date.now()},true));
setInterval(()=>{if(session&&Date.now()-lastAct>15*60*1000){admLogout();toast('Logged out after 15 minutes of inactivity.')}},30000);
render();
</script>
</body>
</html>
