<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<meta name="theme-color" content="#111827"><title>ALGAIDA NAG WORK</title>
<style>
:root{--bg:#f3f6fb;--panel:#fff;--text:#172033;--muted:#68758a;--line:#e3e9f2;--accent:#2563eb;--soft:#eaf1ff;--danger:#dc2626;--shadow:0 8px 28px #17203312}
[data-theme=dark]{--bg:#0d1422;--panel:#172235;--text:#edf3ff;--muted:#a6b3c8;--line:#2a3950;--accent:#6d9cff;--soft:#203454;--danger:#ff7777;--shadow:0 8px 28px #0003}
*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--text);font:15px system-ui,-apple-system,Segoe UI,sans-serif}button,input{font:inherit}button{cursor:pointer;border:0;border-radius:11px;padding:11px 15px;background:var(--accent);color:white;font-weight:650}.secondary{background:var(--soft);color:var(--accent)}.danger{background:#fee2e2;color:#991b1b}.wrap{max-width:1100px;margin:auto;padding:18px}.panel{background:var(--panel);border:1px solid var(--line);border-radius:17px;padding:18px;box-shadow:var(--shadow);margin:14px 0}.top{display:flex;align-items:center;justify-content:space-between;gap:12px;flex-wrap:wrap}.brand{display:flex;align-items:center;gap:12px}.logo{width:44px;height:44px;border-radius:13px;background:linear-gradient(135deg,#2563eb,#7c3aed);display:grid;place-items:center;color:white;font-weight:900}.muted{color:var(--muted)}h1{font-size:20px;margin:0}h2{font-size:17px;margin:0 0 14px}.grid{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:12px}.stats{font-size:24px;font-weight:800;margin-top:5px}.field{display:flex;flex-direction:column;gap:6px}.field label{font-size:12px;color:var(--muted);font-weight:700}.field input{width:100%;padding:12px;border:1px solid var(--line);border-radius:10px;background:var(--bg);color:var(--text);outline:none}.formgrid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px}.actions{display:flex;gap:9px;flex-wrap:wrap;margin-top:14px}.hidden{display:none!important}.auth{max-width:430px;margin:7vh auto}.auth h1{margin-bottom:6px}.auth .field{margin:12px 0}.toolbar{display:flex;gap:9px;flex-wrap:wrap;align-items:center}.toolbar input{flex:1;min-width:180px}.tablewrap{overflow:auto}table{width:100%;border-collapse:collapse;min-width:680px}th,td{text-align:left;padding:11px;border-bottom:1px solid var(--line);white-space:nowrap}th{font-size:12px;color:var(--muted)}.pill{display:inline-block;padding:4px 8px;border-radius:30px;background:var(--soft);color:var(--accent);font-size:12px;font-weight:700}.calcbox{background:var(--soft);padding:13px;border-radius:12px;line-height:1.8}.avatar{width:38px;height:38px;border-radius:50%;object-fit:cover;background:var(--soft);border:1px solid var(--line)}.profileline{display:flex;align-items:center;gap:10px}.right{margin-left:auto}.small{font-size:12px}.notice{padding:10px 12px;border-radius:10px;background:var(--soft);color:var(--muted);font-size:12px}
@media(max-width:760px){.grid{grid-template-columns:repeat(2,minmax(0,1fr))}.formgrid{grid-template-columns:repeat(2,minmax(0,1fr))}.wrap{padding:12px}}
@media(max-width:430px){.formgrid{grid-template-columns:1fr}.panel{padding:14px}.stats{font-size:21px}}
</style></head>
<body><main class="wrap">
<section id="authView" class="auth panel">
<div class="brand"><div class="logo">AN</div><div><h1>ALGAIDA NAG WORK</h1><div class="muted small">MOHAMMD AFSAR</div></div></div>
<div class="actions"><button id="loginTab">Log In</button><button class="secondary" id="signupTab">Sign Up</button></div>
<div id="loginForm"><h2>Welcome Back</h2><div class="field"><label>Username or Email</label><input id="loginUser" autocomplete="username" placeholder="Enter username or email"></div><div class="field"><label>Password</label><input id="loginPass" type="password" autocomplete="current-password" placeholder="Enter password"></div><button id="loginBtn" style="width:100%">Log In</button></div>
<div id="signupForm" class="hidden"><h2>Create Account</h2><div class="field"><label>Full Name</label><input id="newName" placeholder="Your name"></div><div class="field"><label>Username</label><input id="newUser" autocomplete="username" placeholder="Choose username"></div><div class="field"><label>Email (optional)</label><input id="newEmail" type="email" placeholder="Email address"></div><div class="field"><label>Password</label><input id="newPass" type="password" autocomplete="new-password" placeholder="Create password"></div><button id="signupBtn" style="width:100%">Create Account</button></div>
<p id="authMsg" class="muted small"></p><div class="notice">Your records are saved in this browser on this device. Export a backup regularly.</div>
</section>
<section id="appView" class="hidden">
<header class="top panel"><div class="brand"><div class="logo">AN</div><div><h1>ALGAIDA NAG WORK</h1><div class="muted small">Business Dashboard</div></div></div><div class="toolbar"><button class="secondary" id="themeBtn">Dark Mode</button><button class="secondary" id="backupBtn">Export Backup</button><button class="secondary" id="importBtn">Import</button><button class="danger" id="logoutBtn">Log Out</button><input id="importFile" type="file" accept="application/json" class="hidden"></div></header>
<div class="panel toolbar">
<button class="secondary" onclick="showSection('dashboardSection')">Dashboard</button>
<button class="secondary" onclick="showSection('calculatorSection')">Calculator</button>
<button class="secondary" onclick="showSection('salarySection')">My Salary</button>
<button class="secondary" onclick="showSection('profileSection')">My Profile</button>
</div>
<div id="dashboardSection">
<div class="grid">
<div class="panel"><div class="muted small">Total Bills</div><div class="stats" id="totalBills">0</div></div>
<div class="panel"><div class="muted small">Total Booking</div><div class="stats" id="totalBooking">AED 0.00</div></div>
<div class="panel"><div class="muted small">Total Work Amount</div><div class="stats" id="totalWork">AED 0.00</div></div>
<div class="panel"><div class="muted small">Total Piece Charges</div><div class="stats" id="totalCharges">AED 0.00</div></div>
</div>
<div class="panel" id="monthlySummaryPanel">
<div class="top"><h2>Monthly Nag / Crystal / BN Summary</h2><div class="field" style="min-width:150px"><label>Select Month</label><input id="summaryMonth" type="month"></div></div>
<div class="grid">
<div class="panel"><div class="muted small">Nag Quantity</div><div class="stats" id="monthNagQty">0</div><div class="muted small" id="monthNagAED">AED 0.00</div></div>
<div class="panel"><div class="muted small">Crystal Quantity</div><div class="stats" id="monthCrystalQty">0</div><div class="muted small" id="monthCrystalAED">AED 0.00</div></div>
<div class="panel"><div class="muted small">BN Quantity</div><div class="stats" id="monthBnQty">0</div><div class="muted small" id="monthBnAED">AED 0.00</div></div>
<div class="panel"><div class="muted small">Monthly Total Charges</div><div class="stats" id="monthPieceTotal">AED 0.00</div><div class="muted small" id="monthBillCount">0 bills</div></div>
</div>
<div class="notice">Monthly totals are calculated from saved bills using the selected bill date. Only Nag, Crystal and BN are included in the monthly charge total.</div>
</div>
<div class="panel"><div class="top"><h2>New Bill / Update Bill</h2><span class="pill">Live AED Calculator</span></div>
<div class="formgrid">
<div class="field"><label>Bill Number</label><input id="billNo" placeholder="Auto generated"></div>
<div class="field"><label>Model Number</label><input id="modelNo" placeholder="Enter model number"></div>
<div class="field"><label>Bill Date</label><input id="billDate" type="date"></div>
<div class="field"><label>Customer Name (optional)</label><input id="customer" placeholder="Customer name"></div>
<div class="field"><label>Booking Amount (AED)</label><input id="booking" type="number" min="0" step="0.01" value="0"></div>
<div class="field"><label>Work Amount (AED)</label><input id="work" type="number" min="0" step="0.01" value="0"></div>
<div class="field"><label>Nag Quantity</label><input id="nag" type="number" min="0" step="1" value="0"></div>
<div class="field"><label>Crystal Quantity</label><input id="crystal" type="number" min="0" step="1" value="0"></div>
<div class="field"><label>BN Quantity</label><input id="bn" type="number" min="0" step="1" value="0"></div>
</div>
<div class="calcbox" style="margin-top:14px"><b>Live Calculation</b><br>
Nag: <span id="nagCalc">0.00</span> AED <span class="muted">(1440 units = AED 17)</span><br>
Crystal: <span id="crystalCalc">0.00</span> AED <span class="muted">(200 units = AED 10)</span><br>
BN: <span id="bnCalc">0.00</span> AED <span class="muted">(200 units = AED 10)</span><br>
<b>Total Nag + Crystal + BN: <span id="pieceTotal">AED 0.00</span></b><br>
<span class="muted small">Only Nag, Crystal and BN are included in this live total. Booking Amount and Work Amount are saved separately.</span></div>
<div class="actions"><button id="saveBtn">Save Bill</button><button class="secondary" id="clearBtn">Clear Form</button></div><p id="billMsg" class="muted small"></p></div>
<div class="panel"><div class="top"><h2>Search Bills</h2><div class="toolbar"><input id="search" placeholder="Search bill, model or customer..."></div></div><div class="tablewrap"><table><thead><tr><th>Bill No.</th><th>Model No.</th><th>Customer</th><th>Date</th><th>Booking</th><th>Work</th><th>Nag + Crystal + BN Total</th><th>Actions</th></tr></thead><tbody id="billRows"></tbody></table></div><p id="emptyMsg" class="muted small">No bills saved yet.</p></div>
</div>
<div id="calculatorSection" class="panel hidden">
<h2>Calculator</h2>
<div class="field"><label>Calculation</label><input id="calcDisplay" inputmode="decimal" placeholder="Example: 125 + 75"></div>
<div class="actions">
<button class="secondary" onclick="calcKey('7')">7</button><button class="secondary" onclick="calcKey('8')">8</button><button class="secondary" onclick="calcKey('9')">9</button><button class="secondary" onclick="calcKey('/')">÷</button>
<button class="secondary" onclick="calcKey('4')">4</button><button class="secondary" onclick="calcKey('5')">5</button><button class="secondary" onclick="calcKey('6')">6</button><button class="secondary" onclick="calcKey('*')">×</button>
<button class="secondary" onclick="calcKey('1')">1</button><button class="secondary" onclick="calcKey('2')">2</button><button class="secondary" onclick="calcKey('3')">3</button><button class="secondary" onclick="calcKey('-')">−</button>
<button class="secondary" onclick="calcKey('0')">0</button><button class="secondary" onclick="calcKey('.')">.</button><button class="secondary" onclick="calculateExpression()">=</button><button class="secondary" onclick="calcKey('+')">+</button>
<button class="danger" onclick="clearCalculator()">Clear</button>
</div><p class="muted small">Use the keypad or type an arithmetic expression.</p>
</div>
<div id="salarySection" class="panel hidden">
<div class="top"><h2>My Salary</h2><span class="pill">Salary Tracker</span></div>
<div class="grid">
<div class="panel"><div class="muted small">Total Salary Added</div><div class="stats" id="salaryTotal">AED 0.00</div></div>
<div class="panel"><div class="muted small">Salary Entries</div><div class="stats" id="salaryCount">0</div></div>
</div>
<div class="formgrid">
<div class="field"><label>Salary Amount (AED)</label><input id="salaryAmount" type="number" min="0" step="0.01" placeholder="Enter amount"></div>
<div class="field"><label>Payment Date</label><input id="salaryDate" type="date"></div>
<div class="field"><label>Salary Note</label><input id="salaryNote" placeholder="Month / payment details"></div>
</div>
<div class="actions"><button id="addSalaryBtn">Add Salary</button></div>
<div class="tablewrap"><table><thead><tr><th>Date</th><th>Note</th><th>Amount</th><th>Action</th></tr></thead><tbody id="salaryRows"></tbody></table></div>
<p id="salaryEmpty" class="muted small">No salary entries yet.</p>
</div>
<div id="profileSection" class="panel">
<h2>My Profile</h2><div class="profileline"><img id="avatar" class="avatar" alt="Profile picture"><div><b id="profileName">User</b><div class="muted small" id="profileEmail"></div></div></div><div class="actions"><label class="secondary" style="padding:10px 13px;border-radius:10px;cursor:pointer">Upload Profile Picture<input id="photoInput" type="file" accept="image/*" class="hidden"></label></div><hr style="border:0;border-top:1px solid var(--line);margin:18px 0"><h2>Change Password</h2><div class="formgrid"><div class="field"><label>Current Password</label><input id="oldPass" type="password"></div><div class="field"><label>New Password</label><input id="changedPass" type="password"></div></div><div class="actions"><button id="changePassBtn">Change Password</button></div><p id="profileMsg" class="muted small"></p></div>
<footer class="muted small" style="text-align:center;padding:10px">ALGAIDA NAG WORK · MOHAMMD AFSAR</footer>
</section></main>
<script>
const $=id=>document.getElementById(id), money=n=>'AED '+(Number(n)||0).toFixed(2), num=id=>Math.max(0,Number($(id).value)||0);
let current=null, bills=[], salaries=[], accounts=JSON.parse(localStorage.getItem('anw_accounts')||'{}');
const rates={nag:17/1440,crystal:10/200,bn:10/200};
function persist(){localStorage.setItem('anw_accounts',JSON.stringify(accounts));if(current){localStorage.setItem('anw_data_'+current,JSON.stringify(bills));localStorage.setItem('anw_salary_'+current,JSON.stringify(salaries))}}
function showAuth(signup=false){$('authView').classList.remove('hidden');$('appView').classList.add('hidden');$('loginForm').classList.toggle('hidden',signup);$('signupForm').classList.toggle('hidden',!signup);$('authMsg').textContent=''}
$('loginTab').onclick=()=>showAuth(false);$('signupTab').onclick=()=>showAuth(true);
$('signupBtn').onclick=()=>{let u=$('newUser').value.trim().toLowerCase(),p=$('newPass').value,n=$('newName').value.trim();if(!u||!p||!n){$('authMsg').textContent='Please complete name, username and password.';return}if(accounts[u]){$('authMsg').textContent='Username already exists.';return}accounts[u]={name:n,email:$('newEmail').value.trim(),password:p,photo:''};localStorage.setItem('anw_accounts',JSON.stringify(accounts));$('loginUser').value=u;$('loginPass').value=p;login()};
$('loginBtn').onclick=login;function login(){let u=$('loginUser').value.trim().toLowerCase(),p=$('loginPass').value;if(!accounts[u]||accounts[u].password!==p){$('authMsg').textContent='Incorrect username or password.';return}current=u;bills=JSON.parse(localStorage.getItem('anw_data_'+u)||'[]');salaries=JSON.parse(localStorage.getItem('anw_salary_'+u)||'[]');$('authView').classList.add('hidden');$('appView').classList.remove('hidden');$('profileName').textContent=accounts[u].name;$('profileEmail').textContent=accounts[u].email||u;setAvatar();applyTheme();clearForm();render()}
$('logoutBtn').onclick=()=>{persist();current=null;showAuth(false)};
function setAvatar(){let a=accounts[current].photo;$('avatar').src=a||'data:image/svg+xml,'+encodeURIComponent('<svg xmlns="http://www.w3.org/2000/svg" width="80" height="80"><rect width="100%" height="100%" fill="#dbeafe"/><text x="50%" y="58%" text-anchor="middle" font-size="32" fill="#2563eb">+</text></svg>')}
$('photoInput').onchange=e=>{let f=e.target.files[0];if(!f)return;let r=new FileReader();r.onload=()=>{accounts[current].photo=r.result;persist();setAvatar()};r.readAsDataURL(f)};
function applyTheme(){let t=localStorage.getItem('anw_theme')||'light';document.documentElement.dataset.theme=t;$('themeBtn').textContent=t==='dark'?'Light Mode':'Dark Mode'}
$('themeBtn').onclick=()=>{let t=document.documentElement.dataset.theme==='dark'?'light':'dark';localStorage.setItem('anw_theme',t);applyTheme()};
function calc(){let a=num('nag')*rates.nag,b=num('crystal')*rates.crystal,c=num('bn')*rates.bn,total=a+b+c;$('nagCalc').textContent=a.toFixed(2);$('crystalCalc').textContent=b.toFixed(2);$('bnCalc').textContent=c.toFixed(2);$('pieceTotal').textContent=money(total);return {nagCharge:a,crystalCharge:b,bnCharge:c,pieceTotal:total}}
['nag','crystal','bn','booking','work'].forEach(id=>$(id).addEventListener('input',calc));
function clearForm(){['billNo','modelNo','customer'].forEach(id=>$(id).value='');$('billDate').value=new Date().toISOString().slice(0,10);['booking','work','nag','crystal','bn'].forEach(id=>$(id).value='0');$('billNo').placeholder='Auto: '+nextBill();$('billMsg').textContent='';calc();$('saveBtn').textContent='Save Bill';$('saveBtn').dataset.edit=''}
function nextBill(){return 'ANW-'+String((bills.length?Math.max(...bills.map(x=>Number(x.billSeq)||0)):0)+1).padStart(4,'0')}
$('clearBtn').onclick=clearForm;
$('saveBtn').onclick=()=>{let bill=$('billNo').value.trim()||nextBill(),model=$('modelNo').value.trim();if(!model){$('billMsg').textContent='Please enter a model number.';return}let old=$('saveBtn').dataset.edit;let c=calc(),obj={billNo:bill,modelNo:model,customer:$('customer').value.trim(),date:$('billDate').value,booking:num('booking'),work:num('work'),nag:num('nag'),crystal:num('crystal'),bn:num('bn'),...c,billSeq:old?((bills.find(x=>x.billNo===old)||{}).billSeq||0):Number((bill.match(/\d+$/)||[])[0])||bills.length+1};if(old){let i=bills.findIndex(x=>x.billNo===old);if(i>=0)bills[i]=obj}else{if(bills.some(x=>x.billNo===bill)){$('billMsg').textContent='Bill number already exists.';return}bills.unshift(obj)}persist();render();$('billMsg').textContent='Bill saved successfully.';clearForm()};
function render(){renderSalary();updateMonthlySummary();let q=$('search').value.toLowerCase(),list=bills.filter(x=>[x.billNo,x.modelNo,x.customer].join(' ').toLowerCase().includes(q));$('billRows').innerHTML=list.map(x=>`<tr><td><b>${esc(x.billNo)}</b></td><td>${esc(x.modelNo)}</td><td>${esc(x.customer||'—')}</td><td>${esc(x.date||'—')}</td><td>${money(x.booking)}</td><td>${money(x.work)}</td><td><b>${money(x.pieceTotal)}</b></td><td><button class="secondary" onclick="editBill('${encodeURIComponent(x.billNo)}')">Edit</button> <button class="danger" onclick="deleteBill('${encodeURIComponent(x.billNo)}')">Delete</button></td></tr>`).join('');$('emptyMsg').classList.toggle('hidden',list.length>0);$('totalBills').textContent=bills.length;$('totalBooking').textContent=money(bills.reduce((s,x)=>s+x.booking,0));$('totalWork').textContent=money(bills.reduce((s,x)=>s+x.work,0));$('totalCharges').textContent=money(bills.reduce((s,x)=>s+x.pieceTotal,0))}
function esc(s){return String(s??'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]))}
window.editBill=key=>{let x=bills.find(b=>b.billNo===decodeURIComponent(key));if(!x)return;['billNo','modelNo','customer','billDate','booking','work','nag','crystal','bn'].forEach((id,i)=>$(id).value=[x.billNo,x.modelNo,x.customer,x.date,x.booking,x.work,x.nag,x.crystal,x.bn][i]??'');$('saveBtn').dataset.edit=x.billNo;$('saveBtn').textContent='Update Bill';calc();window.scrollTo({top:0,behavior:'smooth'})};
window.deleteBill=key=>{let n=decodeURIComponent(key);if(confirm('Delete bill '+n+'?')){bills=bills.filter(x=>x.billNo!==n);persist();render()}};
$('search').oninput=render;


function updateMonthlySummary(){
 let month=$('summaryMonth').value;
 let entries=bills.filter(x=>(x.date||'').slice(0,7)===month);
 let nag=entries.reduce((s,x)=>s+(Number(x.nag)||0),0);
 let crystal=entries.reduce((s,x)=>s+(Number(x.crystal)||0),0);
 let bn=entries.reduce((s,x)=>s+(Number(x.bn)||0),0);
 let nagAED=entries.reduce((s,x)=>s+(Number(x.nagCharge)||0),0);
 let crystalAED=entries.reduce((s,x)=>s+(Number(x.crystalCharge)||0),0);
 let bnAED=entries.reduce((s,x)=>s+(Number(x.bnCharge)||0),0);
 $('monthNagQty').textContent=nag.toLocaleString('en-US');
 $('monthCrystalQty').textContent=crystal.toLocaleString('en-US');
 $('monthBnQty').textContent=bn.toLocaleString('en-US');
 $('monthNagAED').textContent=money(nagAED);
 $('monthCrystalAED').textContent=money(crystalAED);
 $('monthBnAED').textContent=money(bnAED);
 $('monthPieceTotal').textContent=money(nagAED+crystalAED+bnAED);
 $('monthBillCount').textContent=entries.length+' bills';
}
$('summaryMonth').value=new Date().toISOString().slice(0,7);
$('summaryMonth').addEventListener('change',updateMonthlySummary);
function showSection(id){['dashboardSection','calculatorSection','salarySection','profileSection'].forEach(x=>$(x).classList.toggle('hidden',x!==id));window.scrollTo({top:0,behavior:'smooth'})}
function calcKey(k){$('calcDisplay').value+=k}
function clearCalculator(){$('calcDisplay').value=''}
function calculateExpression(){let s=$('calcDisplay').value.trim();if(!/^[0-9+\-*/().\s]+$/.test(s)){alert('Please enter a valid calculation.');return}try{let result=Function('"use strict";return ('+s+')')();if(!Number.isFinite(result))throw 0;$('calcDisplay').value=String(Number(result.toFixed(8)))}catch{alert('Invalid calculation.')}}
$('salaryDate').value=new Date().toISOString().slice(0,10);
$('addSalaryBtn').onclick=()=>{let amount=Math.max(0,Number($('salaryAmount').value)||0);if(amount<=0){alert('Enter a salary amount greater than zero.');return}salaries.unshift({date:$('salaryDate').value,note:$('salaryNote').value.trim(),amount});$('salaryAmount').value='';$('salaryNote').value='';persist();renderSalary()};
function renderSalary(){$('salaryTotal').textContent=money(salaries.reduce((s,x)=>s+(Number(x.amount)||0),0));$('salaryCount').textContent=salaries.length;$('salaryRows').innerHTML=salaries.map((x,i)=>`<tr><td>${esc(x.date||'—')}</td><td>${esc(x.note||'—')}</td><td><b>${money(x.amount)}</b></td><td><button class="danger" onclick="deleteSalary(${i})">Delete</button></td></tr>`).join('');$('salaryEmpty').classList.toggle('hidden',salaries.length>0)}
window.deleteSalary=i=>{if(confirm('Delete this salary entry?')){salaries.splice(i,1);persist();renderSalary()}};
$('changePassBtn').onclick=()=>{let a=accounts[current];if($('oldPass').value!==a.password){$('profileMsg').textContent='Current password is incorrect.';return}if($('changedPass').value.length<4){$('profileMsg').textContent='New password must be at least 4 characters.';return}a.password=$('changedPass').value;persist();$('oldPass').value=$('changedPass').value='';$('profileMsg').textContent='Password changed successfully.'};
$('backupBtn').onclick=()=>{let data={account:accounts[current],bills};let blob=new Blob([JSON.stringify(data,null,2)],{type:'application/json'}),a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download='ALGAIDA_NAG_WORK_backup.json';a.click();URL.revokeObjectURL(a.href)};
$('importBtn').onclick=()=>$('importFile').click();$('importFile').onchange=e=>{let f=e.target.files[0];if(!f)return;let r=new FileReader();r.onload=()=>{try{let d=JSON.parse(r.result);if(!Array.isArray(d.bills))throw 0;bills=d.bills;persist();render();alert('Backup imported.')}catch{alert('Invalid backup file.')}};r.readAsText(f)};
</script></body></html>
