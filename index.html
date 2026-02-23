<!DOCTYPE html>

<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>الاخوان لتنفيذ واجهات 🇮🇶</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
<script>
  const FB_URL = "https://omar-ali-97d74-default-rtdb.firebaseio.com";
  const ADMIN_PASSWORD = "Omarali1987";

window.*fbSet = async (path, val) => {
try {
const cleanPath = path.replace(/[.#$[]]/g, ’*’);
const url = FB_URL + ‘/’ + cleanPath + ‘.json’;
const res = await fetch(url, { method: ‘PUT’, headers: {‘Content-Type’: ‘application/json’}, body: JSON.stringify(val) });
const result = await res.json();
if (result && result.error) throw new Error(result.error);
localStorage.setItem(‘backup_’ + cleanPath.replace(///g,’_’), JSON.stringify(val));
return true;
} catch(e) { console.error(‘Firebase save failed:’, e); return false; }
};

window.*fbGet = async (path) => {
try {
const cleanPath = path.replace(/[.#$[]]/g, ’*’);
const url = FB_URL + ‘/’ + cleanPath + ‘.json’;
const res = await fetch(url);
const result = await res.json();
if (result && result.error) throw new Error(result.error);
if (result !== null) localStorage.setItem(‘backup_’ + cleanPath.replace(///g,’*’), JSON.stringify(result));
return result;
} catch(e) {
const local = localStorage.getItem(’backup*’ + path.replace(/[.#$[]]/g,’*’).replace(///g,’*’));
return local ? JSON.parse(local) : null;
}
};

window._firebaseReady = true;
</script>

<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: 'Segoe UI', Tahoma, Arial, sans-serif; background: #f0f4f8; direction: rtl; font-size: 15px; }

.header { background: #1565C0; color: white; padding: 12px 16px; display: flex; align-items: center; justify-content: space-between; position: sticky; top: 0; z-index: 50; flex-wrap: wrap; gap: 8px; }
.header-title { font-size: 17px; font-weight: 700; }
.tabs { display: flex; gap: 6px; flex-wrap: wrap; }
.tab-btn { padding: 6px 14px; border-radius: 20px; border: none; font-size: 13px; font-weight: 600; cursor: pointer; font-family: inherit; }
.tab-btn.active { background: white; color: #1565C0; }
.tab-btn:not(.active) { background: rgba(255,255,255,0.2); color: white; }
.sync-label { font-size: 12px; padding: 3px 10px; border-radius: 20px; font-weight: 600; display: flex; align-items: center; gap: 4px; white-space: nowrap; }
.sync-ok { background: #4caf50; color: white; }
.sync-pending { background: #ff9800; color: white; }
.sync-error { background: #f44336; color: white; }

/* Admin badge */
.admin-badge { background: #ffd600; color: #333; font-size: 11px; padding: 2px 8px; border-radius: 20px; font-weight: 700; }
.viewer-badge { background: rgba(255,255,255,0.25); color: white; font-size: 11px; padding: 2px 8px; border-radius: 20px; font-weight: 600; }

.week-bar { background: white; padding: 10px 16px; display: flex; align-items: center; justify-content: space-between; border-bottom: 2px solid #e0e0e0; flex-wrap: wrap; gap: 8px; }
.week-label { background: white; border: 2px solid #1565C0; color: #1565C0; font-weight: 700; padding: 6px 14px; border-radius: 8px; font-size: 14px; font-family: inherit; }
.week-actions { display: flex; gap: 6px; flex-wrap: wrap; }
.btn { padding: 7px 14px; border: none; border-radius: 8px; font-size: 13px; font-weight: 600; cursor: pointer; font-family: inherit; display: inline-flex; align-items: center; gap: 4px; transition: opacity .15s; }
.btn:active { opacity: .75; }
.btn-blue { background: #1565C0; color: white; }
.btn-red { background: #e53935; color: white; }
.btn-green { background: #2e7d32; color: white; }
.btn-orange { background: #e65100; color: white; }
.btn-teal { background: #00695c; color: white; }
.btn-gray { background: #607d8b; color: white; }
.btn-excel { background: #217346; color: white; }
.btn-purple { background: #6a1b9a; color: white; }

.content { padding: 14px; max-width: 700px; margin: 0 auto; }
.card { background: white; border-radius: 14px; margin-bottom: 14px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,.08); }
.card-header { padding: 12px 16px; font-size: 16px; font-weight: 700; display: flex; align-items: center; justify-content: space-between; color: white; }
.card-header.green { background: #2e7d32; }
.card-header.orange { background: #e65100; }
.card-header.red { background: #c62828; }
.card-header.purple { background: #6a1b9a; }
.card-body { padding: 14px 16px; }
.amount-badge { background: rgba(255,255,255,0.25); padding: 4px 12px; border-radius: 20px; font-size: 14px; }

.form-row { display: flex; gap: 8px; margin-bottom: 8px; flex-wrap: wrap; }
.form-row input, .form-row select { flex: 1; min-width: 100px; padding: 9px 12px; border: 1.5px solid #ccc; border-radius: 8px; font-size: 14px; font-family: inherit; direction: rtl; outline: none; }
.form-row input:focus { border-color: #1565C0; }

.worker-card { background: #f8f9fa; border: 1.5px solid #e0e0e0; border-radius: 12px; margin-bottom: 12px; overflow: hidden; }
.worker-name-bar { background: #e3f2fd; padding: 10px 14px; font-size: 16px; font-weight: 700; color: #1565C0; display: flex; align-items: center; justify-content: space-between; }
.worker-body { padding: 12px 14px; }
.days-row { display: flex; gap: 6px; margin-bottom: 10px; flex-wrap: wrap; }
.day-btn { padding: 6px 10px; border-radius: 8px; border: none; font-size: 13px; font-weight: 600; cursor: pointer; font-family: inherit; background: #e53935; color: white; transition: background .15s; }
.day-btn.present { background: #2e7d32; }
.day-btn:disabled { cursor: default; opacity: 0.85; }
.input-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; margin-bottom: 10px; }
.input-box { display: flex; flex-direction: column; gap: 3px; }
.input-box label { font-size: 11px; color: #666; font-weight: 600; }
.input-box input { padding: 8px 10px; border: 1.5px solid #ccc; border-radius: 8px; font-size: 14px; font-family: inherit; text-align: center; outline: none; }
.input-box input:focus { border-color: #1565C0; }
.final-salary { text-align: left; font-size: 16px; font-weight: 700; color: #2e7d32; margin-bottom: 10px; padding: 8px 10px; background: #e8f5e9; border-radius: 8px; }
.worker-actions { display: flex; gap: 6px; flex-wrap: wrap; }

.item-row { display: flex; align-items: center; padding: 8px 10px; background: #f5f5f5; border-radius: 8px; margin-bottom: 6px; font-size: 14px; gap: 8px; }
.item-info { flex: 1; }
.item-amount { font-weight: 700; }
.item-date { font-size: 12px; color: #888; }
.delete-btn { background: #e53935; color: white; border: none; border-radius: 6px; min-width: 28px; height: 28px; cursor: pointer; font-size: 14px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }

.empty-msg { text-align: center; color: #aaa; padding: 16px; font-size: 14px; }

.summary-box { border-radius: 12px; padding: 14px 16px; margin-bottom: 10px; }
.summary-box.green { background: #e8f5e9; border: 2px solid #2e7d32; }
.summary-box.orange { background: #fff3e0; border: 2px solid #e65100; }
.summary-box.red { background: #ffebee; border: 2px solid #c62828; }
.summary-box.blue { background: #e3f2fd; border: 2px solid #1565C0; }
.summary-box.purple { background: #f3e5f5; border: 2px solid #6a1b9a; }
.summary-row { display: flex; justify-content: space-between; padding: 5px 0; font-size: 15px; border-bottom: 1px solid rgba(0,0,0,0.07); }
.summary-row:last-child { border-bottom: none; font-weight: 700; font-size: 16px; }
.summary-title { font-size: 16px; font-weight: 700; margin-bottom: 10px; }

.action-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 14px; }
.action-btn-big { padding: 14px; border: none; border-radius: 12px; font-size: 15px; font-weight: 700; cursor: pointer; font-family: inherit; display: flex; flex-direction: column; align-items: center; gap: 6px; color: white; }
.action-btn-big .icon { font-size: 28px; }

.payment-item { background: #f3e5f5; border: 1.5px solid #ce93d8; border-radius: 10px; padding: 10px 14px; margin-bottom: 8px; display: flex; align-items: center; gap: 10px; }
.payment-item .p-amount { font-size: 18px; font-weight: 800; color: #6a1b9a; flex: 1; }
.payment-item .p-note { font-size: 13px; color: #555; }
.payment-item .p-date { font-size: 12px; color: #888; }

/* Read-only overlay for viewers */
.readonly-notice { background: #fff3e0; border: 2px solid #e65100; border-radius: 10px; padding: 10px 14px; margin-bottom: 14px; font-size: 14px; color: #e65100; font-weight: 600; text-align: center; }

.loading-overlay { position: fixed; inset: 0; background: rgba(21,101,192,0.95); display: flex; flex-direction: column; align-items: center; justify-content: center; color: white; z-index: 9999; gap: 16px; }
.loading-overlay.hidden { display: none; }
.spinner { width: 48px; height: 48px; border: 5px solid rgba(255,255,255,0.3); border-top-color: white; border-radius: 50%; animation: spin .8s linear infinite; }
@keyframes spin { to { transform: rotate(360deg); } }

/* Project selection modal */
.session-modal { position: fixed; inset: 0; background: rgba(0,0,0,0.7); display: flex; align-items: center; justify-content: center; z-index: 9998; }
.session-modal.hidden { display: none; }
.session-box { background: white; border-radius: 20px; padding: 28px 24px; max-width: 380px; width: 92%; text-align: center; }
.session-box h2 { color: #1565C0; margin-bottom: 8px; font-size: 20px; }
.session-box p { color: #555; margin-bottom: 16px; font-size: 14px; line-height: 1.6; }
.session-box input { width: 100%; padding: 10px 14px; border: 2px solid #ccc; border-radius: 10px; font-size: 15px; font-family: inherit; direction: rtl; outline: none; margin-bottom: 10px; text-align: center; }
.session-box input:focus { border-color: #1565C0; }
.hint { font-size: 12px; color: #999; margin-top: 10px; line-height: 1.5; }
.divider { border: none; border-top: 1px solid #eee; margin: 16px 0; }
.admin-link { font-size: 13px; color: #1565C0; cursor: pointer; text-decoration: underline; margin-top: 6px; display: inline-block; }

/* Admin login modal */
.admin-modal { position: fixed; inset: 0; background: rgba(0,0,0,0.6); display: flex; align-items: center; justify-content: center; z-index: 9999; }
.admin-modal.hidden { display: none; }
.admin-box { background: white; border-radius: 16px; padding: 28px 24px; max-width: 340px; width: 92%; text-align: center; }
.admin-box h2 { color: #1565C0; margin-bottom: 8px; }
.admin-box input { width: 100%; padding: 10px 14px; border: 2px solid #ccc; border-radius: 10px; font-size: 15px; font-family: inherit; direction: ltr; outline: none; margin-bottom: 12px; text-align: center; letter-spacing: 2px; }
.admin-box input:focus { border-color: #1565C0; }

.modal-overlay { position: fixed; inset: 0; background: rgba(0,0,0,0.5); display: flex; align-items: center; justify-content: center; z-index: 999; }
.modal-overlay.hidden { display: none; }
.modal-box { background: white; border-radius: 16px; padding: 24px; max-width: 380px; width: 92%; }
.modal-box h3 { color: #6a1b9a; margin-bottom: 16px; font-size: 18px; }
.modal-box input { width: 100%; padding: 10px 12px; border: 1.5px solid #ccc; border-radius: 8px; font-size: 14px; font-family: inherit; direction: rtl; outline: none; margin-bottom: 10px; }
.modal-box input:focus { border-color: #6a1b9a; }
.modal-actions { display: flex; gap: 8px; }

/* Project list */
.project-list { display: flex; flex-direction: column; gap: 8px; margin-bottom: 14px; max-height: 200px; overflow-y: auto; }
.project-item { background: #e3f2fd; border: 1.5px solid #1565C0; border-radius: 10px; padding: 10px 14px; cursor: pointer; font-weight: 600; color: #1565C0; text-align: right; font-size: 15px; transition: background .15s; }
.project-item:hover { background: #bbdefb; }
</style>

</head>
<body>

<div class="loading-overlay" id="loadingOverlay">
  <div class="spinner"></div>
  <div style="font-size:18px;font-weight:700">جاري تحميل البيانات...</div>
  <div style="font-size:13px;opacity:.7">يتم تحميل بياناتك من السحابة</div>
</div>

<!-- Project Selection Modal -->

<div class="session-modal" id="sessionModal">
  <div class="session-box">
    <div style="font-size:44px;margin-bottom:8px">🇮🇶</div>
    <h2>الاخوان لتنفيذ واجهات</h2>
    <p>اختر المشروع أو أدخل اسمه للدخول</p>

```
<div class="project-list" id="projectList"></div>

<input id="sessionInput" type="text" placeholder="اسم مشروع جديد (مثال: بيت احمد)" maxlength="40">
<button class="btn btn-blue" style="width:100%;justify-content:center;padding:12px;font-size:16px" onclick="enterAsViewer()">👁️ دخول كمشاهد</button>
<hr class="divider">
<span class="admin-link" onclick="showAdminModal()">🔐 دخول كمدير</span>
<div class="hint">المشاهد يرى البيانات فقط بدون تعديل<br>المدير يتحكم بكل شيء</div>
```

  </div>
</div>

<!-- Admin Password Modal -->

<div class="admin-modal hidden" id="adminModal">
  <div class="admin-box">
    <div style="font-size:36px;margin-bottom:8px">🔐</div>
    <h2>دخول المدير</h2>
    <p style="color:#666;margin-bottom:16px;font-size:14px">أدخل كلمة السر للتعديل</p>
    <input id="adminPassInput" type="password" placeholder="كلمة السر">
    <div style="display:flex;gap:8px">
      <button class="btn btn-gray" style="flex:1;justify-content:center" onclick="closeAdminModal()">إلغاء</button>
      <button class="btn btn-blue" style="flex:2;justify-content:center" onclick="verifyAdmin()">✅ دخول</button>
    </div>
  </div>
</div>

<!-- Payment Modal -->

<div class="modal-overlay hidden" id="paymentModal">
  <div class="modal-box">
    <h3>💜 تسجيل مبلغ مستلم</h3>
    <input id="pmtAmount" type="number" placeholder="المبلغ المستلم (دينار)">
    <input id="pmtDate" type="date">
    <input id="pmtNote" type="text" placeholder="ملاحظة (اختياري)">
    <div class="modal-actions">
      <button class="btn btn-gray" onclick="closePaymentModal()" style="flex:1;justify-content:center">إلغاء</button>
      <button class="btn btn-purple" onclick="addPayment()" style="flex:2;justify-content:center">✅ حفظ وإشعار المقاول</button>
    </div>
  </div>
</div>

<div class="header">
  <div class="header-title">🇮🇶 الاخوان لتنفيذ واجهات</div>
  <div class="tabs">
    <button class="tab-btn" onclick="showTab('workers')" id="tab-workers">👷 العمال</button>
    <button class="tab-btn active" onclick="showTab('summary')" id="tab-summary">📌 الملخص</button>
    <button class="tab-btn" onclick="showTab('payments')" id="tab-payments">💜 المقاول</button>
  </div>
  <div style="display:flex;align-items:center;gap:6px;flex-wrap:wrap">
    <span id="roleBadge" class="viewer-badge">👁️ مشاهد</span>
    <span class="sync-label sync-ok" id="syncIndicator">☁️ محفوظ</span>
  </div>
</div>

<div class="week-bar">
  <div class="week-actions" id="weekActions">
    <button class="btn btn-blue" onclick="addWeek()">+ أسبوع</button>
    <button class="btn btn-red" onclick="deleteCurrentWeek()">🗑️</button>
  </div>
  <select class="week-label" id="weekSelect" onchange="loadWeek()"></select>
</div>

<div class="content">
  <!-- WORKERS -->
  <div id="tab-workers-content" style="display:none">
    <div id="readonlyNotice" class="readonly-notice hidden">👁️ أنت في وضع المشاهدة فقط — لا يمكن التعديل</div>
    <div id="addWorkerCard" class="card">
      <div class="card-body">
        <div style="font-size:16px;font-weight:700;color:#1565C0;margin-bottom:10px">👷 إضافة عامل جديد</div>
        <div class="form-row">
          <input id="newWorkerName" placeholder="اسم العامل">
          <input id="newWorkerWage" type="number" placeholder="الأجر اليومي (دينار)">
        </div>
        <div class="form-row">
          <input id="newWorkerPhone" placeholder="رقم واتساب">
          <button class="btn btn-green" onclick="addWorker()">إضافة ✅</button>
        </div>
      </div>
    </div>
    <div class="card">
      <div class="card-header red">
        <span>💵 سلفة المقاول</span>
        <span class="amount-badge" id="totalLoanBadge">0 دينار</span>
      </div>
      <div class="card-body">
        <div id="addLoanForm" class="form-row">
          <input id="loanAmount" type="number" placeholder="المبلغ">
          <input id="loanDate" type="date">
          <button class="btn btn-orange" onclick="addLoan()">إضافة</button>
        </div>
        <div id="loansList"></div>
      </div>
    </div>
    <div class="card">
      <div class="card-header orange">
        <span>🧾 مصروف أسبوعي</span>
        <span class="amount-badge" id="totalExpBadge">0 دينار</span>
      </div>
      <div class="card-body">
        <div id="addExpForm">
          <div class="form-row">
            <input id="expDesc" placeholder="وصف المصروف">
            <input id="expAmount" type="number" placeholder="المبلغ">
          </div>
          <div class="form-row">
            <input id="expDate" type="date">
            <button class="btn btn-blue" onclick="addExpense()">إضافة</button>
          </div>
        </div>
        <div id="expensesList"></div>
      </div>
    </div>
    <div id="workersList"></div>
  </div>

  <!-- SUMMARY -->

  <div id="tab-summary-content" style="display:block">
    <div id="summaryContent"></div>
  </div>

  <!-- PAYMENTS -->

  <div id="tab-payments-content" style="display:none">
    <div class="card">
      <div class="card-header purple">
        <span>💜 المبالغ المستلمة</span>
        <span class="amount-badge" id="totalPaymentsBadge">0 دينار</span>
      </div>
      <div class="card-body">
        <div id="contractorPhoneSection" style="margin-bottom:12px">
          <div style="font-size:13px;color:#666;margin-bottom:6px">📱 رقم واتساب المقاول:</div>
          <div class="form-row">
            <input id="contractorPhone" placeholder="مثال: 9647XXXXXXXXX" type="tel">
            <button class="btn btn-gray" onclick="saveContractorPhone()">حفظ</button>
          </div>
        </div>
        <button id="addPaymentBtn" class="btn btn-purple" style="width:100%;justify-content:center;padding:12px;margin-bottom:12px" onclick="openPaymentModal()">
          + تسجيل مبلغ مستلم وإشعار المقاول
        </button>
        <div id="paymentsList"></div>
      </div>
    </div>
  </div>
</div>

<script>
const DAYS = ['السبت','الأحد','الإثنين','الثلاثاء','الأربعاء','الخميس','الجمعة'];
let sessionKey = '', currentWeek = '', data = {}, saveTimer = null;
let isAdmin = false;
let pendingProjectName = '';

// ===== ROLE MANAGEMENT =====
function setAdminUI(admin) {
  isAdmin = admin;
  // Role badge
  const badge = document.getElementById('roleBadge');
  if (admin) {
    badge.className = 'admin-badge';
    badge.textContent = '🔑 مدير';
  } else {
    badge.className = 'viewer-badge';
    badge.textContent = '👁️ مشاهد';
  }
  // Show/hide admin controls
  const notice = document.getElementById('readonlyNotice');
  const addWorkerCard = document.getElementById('addWorkerCard');
  const addLoanForm = document.getElementById('addLoanForm');
  const addExpForm = document.getElementById('addExpForm');
  const weekActions = document.getElementById('weekActions');
  const contractorPhoneSection = document.getElementById('contractorPhoneSection');
  const addPaymentBtn = document.getElementById('addPaymentBtn');

  if (admin) {
    notice.classList.add('hidden');
    addWorkerCard.style.display = '';
    addLoanForm.style.display = '';
    addExpForm.style.display = '';
    weekActions.style.display = '';
    contractorPhoneSection.style.display = '';
    addPaymentBtn.style.display = '';
  } else {
    notice.classList.remove('hidden');
    addWorkerCard.style.display = 'none';
    addLoanForm.style.display = 'none';
    addExpForm.style.display = 'none';
    weekActions.style.display = 'none';
    contractorPhoneSection.style.display = 'none';
    addPaymentBtn.style.display = 'none';
  }
}

// ===== SESSION MODAL =====
function showAdminModal() {
  pendingProjectName = document.getElementById('sessionInput').value.trim();
  if (!pendingProjectName) { alert('أدخل اسم المشروع أولاً'); return; }
  document.getElementById('adminPassInput').value = '';
  document.getElementById('adminModal').classList.remove('hidden');
  setTimeout(() => document.getElementById('adminPassInput').focus(), 100);
}

function closeAdminModal() {
  document.getElementById('adminModal').classList.add('hidden');
}

function verifyAdmin() {
  const pass = document.getElementById('adminPassInput').value;
  if (pass === ADMIN_PASSWORD) {
    closeAdminModal();
    startSession(pendingProjectName, true);
  } else {
    alert('❌ كلمة السر غير صحيحة');
    document.getElementById('adminPassInput').value = '';
  }
}

function enterAsViewer() {
  const val = document.getElementById('sessionInput').value.trim();
  if (!val) { alert('أدخل اسم المشروع'); return; }
  startSession(val, false);
}

function enterProjectFromList(name) {
  document.getElementById('sessionInput').value = name;
  // Viewer by default from list; admin must click admin link
  startSession(name, false);
}

async function loadProjectList() {
  try {
    const projects = await window._fbGet('projects');
    const listEl = document.getElementById('projectList');
    if (projects && typeof projects === 'object') {
      const keys = Object.keys(projects);
      if (keys.length) {
        listEl.innerHTML = '<div style="font-size:12px;color:#999;margin-bottom:6px">المشاريع الموجودة — اختر للدخول:</div>' +
          keys.map(k => `<div class="project-item" onclick="enterProjectFromList('${k}')">${k.replace(/_/g,' ')}</div>`).join('');
        return;
      }
    }
    listEl.innerHTML = '';
  } catch(e) {
    document.getElementById('projectList').innerHTML = '';
  }
}

function startSession(name, admin) {
  sessionKey = name.toLowerCase().replace(/[^a-z0-9\u0600-\u06ff]/g, '_');
  localStorage.setItem('lastSession', sessionKey);
  localStorage.setItem('lastSessionAdmin', admin ? '1' : '0');
  document.getElementById('sessionModal').classList.add('hidden');
  initApp(admin);
}

// ===== FIREBASE =====
function setSyncStatus(s) {
  const el = document.getElementById('syncIndicator');
  const m = { saving:['sync-pending','⏳ جاري الحفظ...'], ok:['sync-ok','☁️ محفوظ'], error:['sync-error','❌ خطأ'] };
  el.className = 'sync-label ' + m[s][0]; el.textContent = m[s][1];
}

function saveData() {
  if (!isAdmin) return;
  setSyncStatus('saving');
  clearTimeout(saveTimer);
  saveTimer = setTimeout(async () => {
    try {
      await window._fbSet('projects/' + sessionKey, data);
      setSyncStatus('ok');
    } catch(e) {
      setSyncStatus('error');
      localStorage.setItem('fb_backup_'+sessionKey, JSON.stringify(data));
    }
  }, 700);
}

async function initApp(admin) {
  document.getElementById('loadingOverlay').classList.remove('hidden');
  try {
    const saved = await window._fbGet('projects/' + sessionKey);
    data = saved || { weeks:{}, contractorPhone:'' };
  } catch(e) {
    const local = localStorage.getItem('fb_backup_'+sessionKey);
    data = local ? JSON.parse(local) : { weeks:{}, contractorPhone:'' };
  }
  if (!data.contractorPhone) data.contractorPhone = '';
  document.getElementById('loadingOverlay').classList.add('hidden');
  setAdminUI(admin);
  buildWeekSelect();
  const weeks = Object.keys(data.weeks||{}).sort();
  currentWeek = weeks.length ? weeks[weeks.length-1] : null;
  if (!currentWeek && admin) addWeek(true);
  else if (currentWeek) document.getElementById('weekSelect').value = currentWeek;
  if (data.contractorPhone) document.getElementById('contractorPhone').value = data.contractorPhone;
  
  // Update header title with project name
  document.querySelector('.header-title').textContent = '🇮🇶 ' + sessionKey.replace(/_/g,' ');
  
  renderAll(); showTab('summary');
}

// ===== WEEKS =====
function getTodaySat() {
  const d=new Date(); const diff=(d.getDay()+1)%7; d.setDate(d.getDate()-diff); return d.toISOString().slice(0,10);
}
function buildWeekSelect() {
  const sel=document.getElementById('weekSelect'); sel.innerHTML='';
  Object.keys(data.weeks||{}).sort().reverse().forEach(w=>{
    const o=document.createElement('option'); o.value=w; o.textContent='أسبوع '+w; sel.appendChild(o);
  });
}
function addWeek(silent=false) {
  if (!isAdmin) return;
  if (!data.weeks) data.weeks={};
  const ex=Object.keys(data.weeks).sort();
  let key=!ex.length?getTodaySat():(() => { const d=new Date(ex[ex.length-1]); d.setDate(d.getDate()+7); return d.toISOString().slice(0,10); })();
  if(data.weeks[key]) return alert('هذا الأسبوع موجود');
  const base = currentWeek&&data.weeks[currentWeek] ?
    data.weeks[currentWeek].workers.map(w=>({...w,days:[false,false,false,false,false,false,false],advance:0,deduction:0})) : [];
  data.weeks[key]={workers:base,loans:[],expenses:[],payments:[]};
  currentWeek=key; buildWeekSelect(); document.getElementById('weekSelect').value=key;
  if(!silent){saveData();renderAll();}
}
function loadWeek(){ currentWeek=document.getElementById('weekSelect').value; renderAll(); }
function deleteCurrentWeek(){
  if (!isAdmin) return;
  if(!currentWeek||!confirm('حذف هذا الأسبوع؟')) return;
  delete data.weeks[currentWeek];
  const w=Object.keys(data.weeks).sort(); currentWeek=w.length?w[w.length-1]:null;
  buildWeekSelect(); if(currentWeek) document.getElementById('weekSelect').value=currentWeek;
  saveData(); renderAll();
}
function week(){ return currentWeek&&data.weeks&&data.weeks[currentWeek]?data.weeks[currentWeek]:{workers:[],loans:[],expenses:[],payments:[]}; }

// ===== WORKERS =====
function addWorker(){
  if (!isAdmin) return;
  const name=document.getElementById('newWorkerName').value.trim();
  const wage=parseFloat(document.getElementById('newWorkerWage').value)||0;
  const phone=document.getElementById('newWorkerPhone').value.trim();
  if(!name) return alert('أدخل اسم العامل');
  week().workers.push({id:Date.now(),name,wage,phone,days:[false,false,false,false,false,false,false],advance:0,deduction:0});
  ['newWorkerName','newWorkerWage','newWorkerPhone'].forEach(id=>document.getElementById(id).value='');
  saveData(); renderWorkers();
}
function toggleDay(i,di){
  if (!isAdmin) return;
  week().workers[i].days[di]=!week().workers[i].days[di]; saveData(); renderWorkers();
}
function updateWorkerField(i,f,v){
  if (!isAdmin) return;
  week().workers[i][f]=parseFloat(v)||0;
  const el=document.getElementById('final-'+i);
  if(el) el.textContent='💵 الأجر النهائي: '+calcWorkerSalary(week().workers[i])+' دينار';
  saveData();
}
function deleteWorker(i){
  if (!isAdmin) return;
  if(!confirm('حذف هذا العامل؟')) return; week().workers.splice(i,1); saveData(); renderWorkers();
}
function calcWorkerSalary(w){ return (w.days.filter(Boolean).length*w.wage)+(w.advance||0)-(w.deduction||0); }

function sendWhatsApp(i){
  const w=week().workers[i], net=calcWorkerSalary(w), cnt=w.days.filter(Boolean).length;
  const msg=`السلام عليكم ${w.name} 👷\n━━━━━━━━━━━━━━\n📅 الأسبوع: ${currentWeek}\n📆 الحضور: ${DAYS.filter((_,di)=>w.days[di]).join('، ')||'—'}\n🔢 عدد الأيام: ${cnt}\n💰 الأجر اليومي: ${w.wage} دينار\n${w.advance?'➕ سلفة: '+w.advance+' دينار\n':''}${w.deduction?'➖ خصم: '+w.deduction+' دينار\n':''}━━━━━━━━━━━━━━\n💵 الأجر النهائي: ${net} دينار\n━━━━━━━━━━━━━━\nبارك الله في جهودك وأعطاك الصحة والعافية 🇮🇶`;
  window.open('https://wa.me/'+(w.phone||'').replace(/\D/g,'')+'?text='+encodeURIComponent(msg),'_blank');
}
function printWorker(i){
  const w=week().workers[i], net=calcWorkerSalary(w);
  const win=window.open('','_blank');
  win.document.write(`<html dir="rtl"><body style="font-family:Arial;padding:24px;max-width:400px"><h2 style="color:#1565C0">كشف العامل</h2><table style="width:100%;border-collapse:collapse;margin:12px 0"><tr><td style="padding:6px;border-bottom:1px solid #eee;color:#666">الاسم</td><td style="padding:6px;border-bottom:1px solid #eee;font-weight:700">${w.name}</td></tr><tr><td style="padding:6px;border-bottom:1px solid #eee;color:#666">الأسبوع</td><td style="padding:6px;border-bottom:1px solid #eee">${currentWeek}</td></tr><tr><td style="padding:6px;border-bottom:1px solid #eee;color:#666">أيام الحضور</td><td style="padding:6px;border-bottom:1px solid #eee">${DAYS.filter((_,di)=>w.days[di]).join(' - ')||'—'}</td></tr><tr><td style="padding:6px;border-bottom:1px solid #eee;color:#666">عدد الأيام</td><td style="padding:6px;border-bottom:1px solid #eee">${w.days.filter(Boolean).length}</td></tr><tr><td style="padding:6px;border-bottom:1px solid #eee;color:#666">الأجر اليومي</td><td style="padding:6px;border-bottom:1px solid #eee">${w.wage} دينار</td></tr>${w.advance?'<tr><td style="padding:6px;border-bottom:1px solid #eee;color:#2e7d32">سلفة</td><td style="padding:6px;border-bottom:1px solid #eee;color:#2e7d32">+'+w.advance+' دينار</td></tr>':''}${w.deduction?'<tr><td style="padding:6px;border-bottom:1px solid #eee;color:#c62828">خصم</td><td style="padding:6px;border-bottom:1px solid #eee;color:#c62828">-'+w.deduction+' دينار</td></tr>':''}<tr style="background:#e8f5e9"><td style="padding:8px;font-weight:800;color:#2e7d32">الأجر النهائي</td><td style="padding:8px;font-weight:800;color:#2e7d32;font-size:18px">${net} دينار</td></tr></table><div style="text-align:center;color:#999;font-size:12px;margin-top:20px">بارك الله في جهودك وأعطاك الصحة والعافية 🇮🇶</div><script>window.print()<\/script></body></html>`);
}

function renderWorkers(){
  const w=week(), c=document.getElementById('workersList');
  if(!w.workers.length){c.innerHTML='<div class="empty-msg">لا يوجد عمال'+(isAdmin?' — أضف عاملاً جديداً 👆':'')+'</div>';return;}
  c.innerHTML=w.workers.map((wk,i)=>{
    const net=calcWorkerSalary(wk);
    const disabledAttr = isAdmin ? '' : 'disabled';
    return `<div class="worker-card"><div class="worker-name-bar"><span>${wk.name}</span><span style="font-size:13px;color:#555">${wk.wage} د/يوم</span></div><div class="worker-body"><div class="days-row">${DAYS.map((d,di)=>`<button class="day-btn${wk.days[di]?' present':''}" onclick="toggleDay(${i},${di})" ${disabledAttr}>${d}</button>`).join('')}</div><div style="font-size:13px;color:#555;margin-bottom:8px">📆 ${wk.days.filter(Boolean).length} يوم حضور</div><div class="input-grid"><div class="input-box"><label>➕ سلفة (دينار)</label><input type="number" value="${wk.advance||0}" oninput="updateWorkerField(${i},'advance',this.value)" ${disabledAttr}></div><div class="input-box"><label>➖ خصم (دينار)</label><input type="number" value="${wk.deduction||0}" oninput="updateWorkerField(${i},'deduction',this.value)" ${disabledAttr}></div></div><div class="final-salary" id="final-${i}">💵 الأجر النهائي: ${net} دينار</div><div class="worker-actions"><button class="btn btn-teal" onclick="printWorker(${i})">🖨️ طباعة</button><button class="btn btn-green" onclick="sendWhatsApp(${i})">📱 واتساب</button>${isAdmin?`<button class="btn btn-red" onclick="deleteWorker(${i})">❌ حذف</button>`:''}</div></div></div>`;
  }).join('');
}

// ===== LOANS =====
function addLoan(){
  if (!isAdmin) return;
  const a=parseFloat(document.getElementById('loanAmount').value); if(!a) return alert('أدخل المبلغ');
  const ld=document.getElementById('loanDate').value; if(!ld) return alert('يرجى إدخال التاريخ');
  week().loans.push({id:Date.now(),amount:a,date:ld});
  document.getElementById('loanAmount').value=''; saveData(); renderLoans(); renderSummary();
}
function deleteLoan(i){if (!isAdmin) return; week().loans.splice(i,1);saveData();renderLoans();renderSummary();}
function renderLoans(){
  const l=week().loans;
  document.getElementById('totalLoanBadge').textContent=l.reduce((s,x)=>s+x.amount,0)+' دينار';
  document.getElementById('loansList').innerHTML=!l.length?'<div class="empty-msg">لا توجد سلف</div>':
    l.map((x,i)=>`<div class="item-row"><span class="item-amount" style="color:#c62828">${x.amount} دينار</span><span class="item-date">${x.date}</span>${isAdmin?`<button class="delete-btn" onclick="deleteLoan(${i})">✕</button>`:''}</div>`).join('');
}

// ===== EXPENSES =====
function addExpense(){
  if (!isAdmin) return;
  const desc=document.getElementById('expDesc').value.trim(), a=parseFloat(document.getElementById('expAmount').value);
  if(!desc||!a) return alert('أدخل الوصف والمبلغ');
  const ed=document.getElementById('expDate').value; if(!ed) return alert('يرجى إدخال التاريخ');
  week().expenses.push({id:Date.now(),desc,amount:a,date:ed});
  document.getElementById('expDesc').value=''; document.getElementById('expAmount').value='';
  saveData(); renderExpenses(); renderSummary();
}
function deleteExpense(i){if (!isAdmin) return; week().expenses.splice(i,1);saveData();renderExpenses();renderSummary();}
function renderExpenses(){
  const e=week().expenses;
  document.getElementById('totalExpBadge').textContent=e.reduce((s,x)=>s+x.amount,0)+' دينار';
  document.getElementById('expensesList').innerHTML=!e.length?'<div class="empty-msg">لا توجد مصروفات</div>':
    e.map((x,i)=>`<div class="item-row"><span class="item-info">${x.desc}</span><span class="item-amount" style="color:#e65100">${x.amount} دينار</span><span class="item-date">${x.date}</span>${isAdmin?`<button class="delete-btn" onclick="deleteExpense(${i})">✕</button>`:''}</div>`).join('');
}

// ===== PAYMENTS =====
function saveContractorPhone(){
  if (!isAdmin) return;
  data.contractorPhone=document.getElementById('contractorPhone').value.trim();saveData();alert('✅ تم حفظ رقم المقاول');
}
function openPaymentModal(){
  if (!isAdmin) return;
  document.getElementById('pmtAmount').value='';document.getElementById('pmtNote').value='';document.getElementById('pmtDate').value='';document.getElementById('paymentModal').classList.remove('hidden');
}
function closePaymentModal(){document.getElementById('paymentModal').classList.add('hidden');}
function addPayment(){
  if (!isAdmin) return;
  const a=parseFloat(document.getElementById('pmtAmount').value); if(!a) return alert('أدخل المبلغ');
  const date=document.getElementById('pmtDate').value; if(!date) return alert('يرجى إدخال التاريخ');
  const note=document.getElementById('pmtNote').value.trim();
  if(!week().payments) week().payments=[];
  week().payments.push({id:Date.now(),amount:a,date,note});
  const totalR=week().payments.reduce((s,p)=>s+p.amount,0);
  const w=week(), totalC=(w.workers.reduce((s,wk)=>s+calcWorkerSalary(wk),0))+(w.loans.reduce((s,l)=>s+l.amount,0))+(w.expenses.reduce((s,e)=>s+e.amount,0));
  const bal=totalR-totalC;
  saveData(); closePaymentModal(); renderPayments(); renderSummary();
  const phone=(data.contractorPhone||'').replace(/\D/g,'');
  const msg=`السلام عليكم 🏗️\n━━━━━━━━━━━━━━\n📋 إشعار استلام مبلغ\n📅 الأسبوع: ${currentWeek}\n━━━━━━━━━━━━━━\n💜 المبلغ المستلم الآن: ${a} دينار\n${note?'📝 '+note+'\n':''}📊 إجمالي المستلم: ${totalR} دينار\n💸 إجمالي المصاريف: ${totalC} دينار\n${bal>=0?'✅ المتبقي: '+bal:'⚠️ العجز: '+Math.abs(bal)} دينار\n━━━━━━━━━━━━━━\nبارك الله في جهودك وأعطاك الصحة والعافية 🇮🇶`;
  if(phone){ if(confirm('إرسال إشعار للمقاول على واتساب؟')) window.open('https://wa.me/'+phone+'?text='+encodeURIComponent(msg),'_blank'); }
  else alert('✅ تم حفظ المبلغ!\n\nأضف رقم المقاول لإرسال إشعارات واتساب.');
}
function deletePayment(i){if (!isAdmin) return; week().payments.splice(i,1);saveData();renderPayments();renderSummary();}
function renderPayments(){
  const p=week().payments||[];
  document.getElementById('totalPaymentsBadge').textContent=p.reduce((s,x)=>s+x.amount,0)+' دينار';
  document.getElementById('paymentsList').innerHTML=!p.length?'<div class="empty-msg">لا توجد مبالغ مستلمة</div>':
    p.map((x,i)=>`<div class="payment-item"><div><div class="p-amount">${x.amount} دينار</div>${x.note?`<div class="p-note">📝 ${x.note}</div>`:''}<div class="p-date">📅 ${x.date}</div></div>${isAdmin?`<button class="delete-btn" onclick="deletePayment(${i})">✕</button>`:''}</div>`).join('');
}

// ===== EXCEL =====
function exportToExcel(){
  const wb=XLSX.utils.book_new(), w=week();
  const wRows=[['الاسم','السبت','الأحد','الإثنين','الثلاثاء','الأربعاء','الخميس','الجمعة','عدد الأيام','الأجر اليومي','السلفة','الخصم','الأجر النهائي']];
  w.workers.forEach(wk=>{ const net=calcWorkerSalary(wk); wRows.push([wk.name,...wk.days.map(d=>d?'✓':'✗'),wk.days.filter(Boolean).length,wk.wage,wk.advance||0,wk.deduction||0,net]); });
  wRows.push([]); wRows.push(['الإجمالي','','','','','','','',w.workers.reduce((s,wk)=>s+wk.days.filter(Boolean).length,0),'',w.workers.reduce((s,wk)=>s+(wk.advance||0),0),w.workers.reduce((s,wk)=>s+(wk.deduction||0),0),w.workers.reduce((s,wk)=>s+calcWorkerSalary(wk),0)]);
  const ws1=XLSX.utils.aoa_to_sheet(wRows); XLSX.utils.book_append_sheet(wb,ws1,'أجور العمال');
  const eRows=[['الوصف','المبلغ','التاريخ']]; w.expenses.forEach(e=>eRows.push([e.desc,e.amount,e.date])); eRows.push(['الإجمالي',w.expenses.reduce((s,e)=>s+e.amount,0),'']);
  const ws2=XLSX.utils.aoa_to_sheet(eRows); XLSX.utils.book_append_sheet(wb,ws2,'المصروفات');
  const pRows=[['المبلغ المستلم','ملاحظة','التاريخ']]; (w.payments||[]).forEach(p=>pRows.push([p.amount,p.note||'',p.date]));
  const ws3=XLSX.utils.aoa_to_sheet(pRows); XLSX.utils.book_append_sheet(wb,ws3,'المبالغ المستلمة');
  const tW=w.workers.reduce((s,wk)=>s+calcWorkerSalary(wk),0), tL=w.loans.reduce((s,l)=>s+l.amount,0), tE=w.expenses.reduce((s,e)=>s+e.amount,0), tR=(w.payments||[]).reduce((s,p)=>s+p.amount,0), tC=tW+tL+tE, bal=tR-tC;
  const sRows=[['ملخص',sessionKey.replace(/_/g,' ')],[],['البند','المبلغ'],['أجور العمال',tW],['المصروفات',tE],['سلف المقاول',tL],['الإجمالي',tC],[],['المستلم',tR],[bal>=0?'المتبقي':'العجز',Math.abs(bal)]];
  const ws4=XLSX.utils.aoa_to_sheet(sRows); XLSX.utils.book_append_sheet(wb,ws4,'الملخص');
  XLSX.writeFile(wb,`${sessionKey}_${currentWeek}.xlsx`);
}

// ===== SUMMARY =====
function renderSummary(){
  const w=week(), tW=w.workers.reduce((s,wk)=>s+calcWorkerSalary(wk),0), tL=w.loans.reduce((s,l)=>s+l.amount,0), tE=w.expenses.reduce((s,e)=>s+e.amount,0), tC=tW+tL+tE, tR=(w.payments||[]).reduce((s,p)=>s+p.amount,0), bal=tR-tC;
  document.getElementById('summaryContent').innerHTML=`
    <div class="action-grid">
      <button class="action-btn-big btn-excel" onclick="exportToExcel()"><span class="icon">📊</span><span>تصدير Excel</span></button>
      <button class="action-btn-big btn-gray" onclick="printSummary()"><span class="icon">🖨️</span><span>طباعة</span></button>
      <button class="action-btn-big btn-purple" onclick="showTab('payments')"><span class="icon">💜</span><span>إشعار المقاول</span></button>
      <button class="action-btn-big" style="background:#455a64" onclick="changeSession()"><span class="icon">🔄</span><span>تغيير المشروع</span></button>
    </div>
    <div class="summary-box green"><div class="summary-title">💰 أجور العمال</div>${w.workers.length?w.workers.map(wk=>`<div class="summary-row"><span>${wk.name} (${wk.days.filter(Boolean).length} يوم)</span><span style="color:#2e7d32;font-weight:700">${calcWorkerSalary(wk)} دينار</span></div>`).join(''):'<div class="empty-msg">لا يوجد عمال</div>'}<div class="summary-row"><span>الإجمالي:</span><span style="color:#2e7d32">${tW} دينار</span></div></div>
    <div class="summary-box orange"><div class="summary-title">🧾 المصروفات</div>${w.expenses.length?w.expenses.map(e=>`<div class="summary-row"><span>${e.desc}</span><span style="color:#e65100;font-weight:700">${e.amount} دينار</span></div>`).join(''):'<div class="empty-msg">لا توجد مصروفات</div>'}<div class="summary-row"><span>الإجمالي:</span><span style="color:#e65100">${tE} دينار</span></div></div>
    <div class="summary-box red"><div class="summary-title">💵 سلف المقاول</div>${w.loans.length?w.loans.map(l=>`<div class="summary-row"><span>${l.date}</span><span style="color:#c62828;font-weight:700">${l.amount} دينار</span></div>`).join(''):'<div class="empty-msg">لا توجد سلف</div>'}<div class="summary-row"><span>الإجمالي:</span><span style="color:#c62828">${tL} دينار</span></div></div>
    <div class="summary-box purple"><div class="summary-title">💜 المبالغ المستلمة</div>${(w.payments||[]).length?(w.payments||[]).map(p=>`<div class="summary-row"><span>${p.date}${p.note?' — '+p.note:''}</span><span style="color:#6a1b9a;font-weight:700">${p.amount} دينار</span></div>`).join(''):'<div class="empty-msg">لا توجد مبالغ</div>'}<div class="summary-row"><span>الإجمالي:</span><span style="color:#6a1b9a">${tR} دينار</span></div></div>
    <div class="summary-box blue"><div class="summary-title">📌 ملخص — ${currentWeek||'—'}</div><div class="summary-row"><span>💰 أجور العمال:</span><span>${tW} دينار</span></div><div class="summary-row"><span>🧾 المصروفات:</span><span>${tE} دينار</span></div><div class="summary-row"><span>💵 سلف المقاول:</span><span>${tL} دينار</span></div><div class="summary-row"><span>💸 إجمالي المصاريف:</span><span style="color:#c62828;font-weight:800">${tC} دينار</span></div><div class="summary-row"><span>💜 إجمالي المستلم:</span><span style="color:#6a1b9a">${tR} دينار</span></div><div class="summary-row"><span>${bal>=0?'✅ المتبقي':'⚠️ العجز'}:</span><span style="color:${bal>=0?'#2e7d32':'#c62828'};font-size:22px;font-weight:800">${Math.abs(bal)} دينار</span></div></div>`;
}

function printSummary(){
  const w=week(), tW=w.workers.reduce((s,wk)=>s+calcWorkerSalary(wk),0), tL=w.loans.reduce((s,l)=>s+l.amount,0), tE=w.expenses.reduce((s,e)=>s+e.amount,0), tR=(w.payments||[]).reduce((s,p)=>s+p.amount,0), tC=tW+tL+tE, bal=tR-tC;
  const win=window.open('','_blank');
  win.document.write(`<html dir="rtl"><body style="font-family:Arial;padding:24px"><h2 style="color:#1565C0">ملخص — ${sessionKey.replace(/_/g,' ')} — ${currentWeek}</h2><h3>أجور العمال:</h3>${w.workers.map(wk=>`<p>${wk.name}: ${calcWorkerSalary(wk)} دينار (${wk.days.filter(Boolean).length} يوم)</p>`).join('')}<p><b>الإجمالي: ${tW} دينار</b></p><h3>المصروفات:</h3>${w.expenses.map(e=>`<p>${e.desc}: ${e.amount} دينار</p>`).join('')}<p><b>الإجمالي: ${tE} دينار</b></p><h3>سلف المقاول:</h3>${w.loans.map(l=>`<p>${l.date}: ${l.amount} دينار</p>`).join('')}<p><b>الإجمالي: ${tL} دينار</b></p><hr><h2 style="color:#c62828">إجمالي المصاريف: ${tC} دينار</h2><h2 style="color:${bal>=0?'#2e7d32':'#c62828'}">${bal>=0?'المتبقي':'العجز'}: ${Math.abs(bal)} دينار</h2><script>window.print()<\/script></body></html>`);
}

// ===== TABS =====
function showTab(t){
  ['workers','summary','payments'].forEach(x=>{
    document.getElementById('tab-'+x+'-content').style.display=x===t?'block':'none';
    document.getElementById('tab-'+x).classList.toggle('active',x===t);
  });
  if(t==='summary') renderSummary();
  if(t==='payments') renderPayments();
}
function changeSession(){
  if(!confirm('تغيير المشروع؟')) return;
  localStorage.removeItem('lastSession');
  localStorage.removeItem('lastSessionAdmin');
  location.reload();
}
function renderAll(){ renderWorkers(); renderLoans(); renderExpenses(); renderSummary(); renderPayments(); }

// ===== BOOT =====
document.addEventListener('DOMContentLoaded', async () => {
  const last = localStorage.getItem('lastSession');
  const lastAdmin = localStorage.getItem('lastSessionAdmin') === '1';
  if (last) {
    sessionKey = last;
    document.getElementById('sessionModal').classList.add('hidden');
    await initApp(lastAdmin);
  } else {
    document.getElementById('loadingOverlay').classList.add('hidden');
    document.getElementById('sessionModal').classList.remove('hidden');
    loadProjectList();
  }
});

document.getElementById('adminPassInput').addEventListener('keydown', e => { if(e.key==='Enter') verifyAdmin(); });
document.getElementById('sessionInput').addEventListener('keydown', e => { if(e.key==='Enter') enterAsViewer(); });

setTimeout(()=>{
  if(document.getElementById('loadingOverlay').classList.contains('hidden')) return;
  document.getElementById('loadingOverlay').classList.add('hidden');
  document.getElementById('sessionModal').classList.remove('hidden');
  loadProjectList();
}, 5000);
</script>

</body>
</html>
