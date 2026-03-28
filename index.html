# my-calendar-app
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,600&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
:root{--bg:#f7f3ee;--surface:#fdfaf6;--surface2:#f0ebe2;--border:#e0d6c8;--text:#2d2820;--muted:#9a8e82;--accent:#6b7fd4;--danger:#c05a38;}
body{font-family:'Raleway',sans-serif;background:var(--bg);color:var(--text);min-height:100vh;display:flex;flex-direction:column;}
.hdr{background:var(--surface);border-bottom:1.5px solid var(--border);padding:10px 18px;display:flex;align-items:center;gap:8px;position:sticky;top:0;z-index:100;flex-wrap:wrap;}
.brand{display:flex;align-items:baseline;gap:7px;margin-right:auto;}
.brand h1{font-style:italic;font-size:1.35rem;font-weight:300;letter-spacing:.04em;}
.brand-pill{font-size:.54rem;font-weight:800;letter-spacing:.18em;text-transform:uppercase;background:var(--accent);color:#fff;padding:2px 7px;border-radius:50px;}
.hdr-right{display:flex;align-items:center;gap:5px;flex-wrap:wrap;}
.nbtn{background:var(--surface2);border:1.5px solid var(--border);border-radius:50px;padding:4px 11px;font-family:'Raleway',sans-serif;font-size:.66rem;font-weight:700;color:var(--muted);cursor:pointer;transition:all .15s;letter-spacing:.03em;}
.nbtn:hover{background:var(--border);color:var(--text);}
.nbtn.active{background:var(--accent);color:#fff;border-color:var(--accent);}
.nbtn.danger{color:var(--danger);border-color:#f0c0b0;}
.nbtn.danger:hover{background:#f0c0b0;}
.wklbl{font-size:.78rem;font-weight:600;color:var(--text);padding:4px 12px;min-width:158px;text-align:center;letter-spacing:.02em;}
.vtgl{display:flex;background:var(--surface2);border:1.5px solid var(--border);border-radius:50px;padding:2px;gap:2px;}
.vbtn{font-family:'Raleway',sans-serif;font-size:.62rem;font-weight:800;background:none;border:none;border-radius:50px;padding:4px 11px;cursor:pointer;color:var(--muted);transition:all .15s;letter-spacing:.07em;}
.vbtn.on{background:var(--surface);color:var(--text);box-shadow:0 1px 4px rgba(0,0,0,.08);}
.search-bar{background:var(--surface);border-bottom:1px solid var(--border);padding:7px 18px;display:flex;align-items:center;gap:8px;flex-wrap:wrap;}
.search-wrap{position:relative;width:260px;flex-shrink:0;}
.search-icon{position:absolute;left:10px;top:50%;transform:translateY(-50%);font-size:.75rem;color:var(--muted);pointer-events:none;}
.search-input{width:100%;background:var(--surface2);border:1.5px solid var(--border);border-radius:50px;padding:6px 28px;font-family:'Raleway',sans-serif;font-size:.72rem;font-weight:500;color:var(--text);outline:none;transition:border-color .15s;}
.search-input:focus{border-color:var(--accent);}
.search-input::placeholder{color:var(--muted);}
.search-clear{position:absolute;right:8px;top:50%;transform:translateY(-50%);background:none;border:none;cursor:pointer;color:var(--muted);font-size:.7rem;padding:2px 4px;display:none;}
.search-clear.show{display:block;}
.match-count{font-size:.63rem;font-weight:700;color:var(--accent);white-space:nowrap;}
.toolbar{display:flex;align-items:center;gap:6px;margin-left:auto;flex-wrap:wrap;}
.sel-info{font-size:.65rem;font-weight:700;color:var(--accent);letter-spacing:.03em;white-space:nowrap;}
.mass-bar{background:#eef0fa;border-bottom:1.5px solid #c8cfe8;padding:7px 18px;display:flex;align-items:center;gap:8px;flex-wrap:wrap;}
.mass-label{font-size:.6rem;font-weight:800;text-transform:uppercase;letter-spacing:.12em;color:var(--accent);}
.mass-field{display:flex;align-items:center;gap:5px;}
.mass-field label{font-size:.58rem;font-weight:700;text-transform:uppercase;letter-spacing:.07em;color:var(--muted);}
.mass-field select,.mass-field input{background:var(--surface);border:1.5px solid #c8cfe8;border-radius:7px;padding:4px 8px;font-family:'Raleway',sans-serif;font-size:.7rem;color:var(--text);outline:none;}
.mdiv{width:1px;height:20px;background:var(--border);}
.lgnd{display:flex;gap:5px;padding:6px 18px;background:var(--surface);border-bottom:1px solid var(--border);flex-wrap:wrap;align-items:center;}
.lgnd-lbl{font-size:.54rem;font-weight:800;text-transform:uppercase;letter-spacing:.13em;color:var(--muted);margin-right:3px;}
.lgnd-item{display:flex;align-items:center;gap:4px;font-size:.64rem;font-weight:500;color:var(--muted);padding:2px 7px 2px 4px;border-radius:50px;border:1.5px solid transparent;cursor:pointer;}
.lgnd-item:hover{border-color:var(--border);}
.lgnd-dot{width:7px;height:7px;border-radius:50%;}
.lgnd-edit-btn{font-size:.55rem;font-weight:800;color:var(--accent);background:none;border:none;cursor:pointer;padding:0 2px;letter-spacing:.04em;opacity:0;transition:opacity .13s;}
.lgnd-item:hover .lgnd-edit-btn{opacity:1;}
.lgnd-add{font-size:.6rem;font-weight:700;color:var(--accent);background:none;border:1.5px dashed var(--accent);border-radius:50px;padding:2px 9px;cursor:pointer;opacity:.7;}
.lgnd-add:hover{opacity:1;background:#eef0fa;}
.main{flex:1;padding:12px 18px 160px;overflow-y:auto;}
.week-wrap,.month-scroll-wrap{display:flex;flex-direction:column;gap:5px;max-width:1200px;margin:0 auto;}
.day-row{background:var(--surface);border-radius:13px;border:1.5px solid var(--border);display:grid;grid-template-columns:78px 1fr;height:108px;box-shadow:0 1px 6px rgba(80,60,40,.05);overflow:hidden;transition:box-shadow .18s;}
.day-row:hover{box-shadow:0 2px 14px rgba(80,60,40,.09);}
.day-row.today .day-lbl{background:linear-gradient(160deg,#6b7fd4,#8b9fe4);}
.day-row.today .day-name,.day-row.today .day-num,.day-row.today .day-ct{color:#fff;}
.day-row.weekend .day-lbl{background:#f5f0e8;}
.day-row.weekend .day-name,.day-row.weekend .day-num,.day-row.weekend .day-ct{color:var(--muted);}
.day-row.day-sel .day-lbl{background:linear-gradient(160deg,#e8c86a,#f0d87a)!important;}
.day-row.day-sel .day-name,.day-row.day-sel .day-num,.day-row.day-sel .day-ct{color:#5a4a10!important;}
.day-lbl{background:var(--surface2);border-right:1.5px solid var(--border);display:flex;flex-direction:column;align-items:center;justify-content:center;padding:8px 0;flex-shrink:0;cursor:pointer;user-select:none;transition:filter .13s;}
.day-lbl:hover{filter:brightness(.95);}
.day-name{font-size:.54rem;font-weight:800;text-transform:uppercase;letter-spacing:.14em;color:var(--muted);}
.day-num{font-size:1.85rem;line-height:1.05;color:var(--text);font-weight:300;}
.day-ct{font-size:.49rem;font-weight:700;color:var(--muted);background:rgba(0,0,0,.07);border-radius:50px;padding:1px 5px;margin-top:3px;letter-spacing:.04em;}
.day-lane{overflow-x:auto;overflow-y:hidden;display:flex;align-items:center;gap:5px;padding:8px 10px;scrollbar-width:thin;scrollbar-color:var(--border) transparent;}
.day-lane::-webkit-scrollbar{height:4px;}
.day-lane::-webkit-scrollbar-thumb{background:var(--border);border-radius:4px;}
.add-cube{width:82px;height:82px;flex-shrink:0;border:1.5px dashed var(--border);border-radius:10px;display:flex;flex-direction:column;align-items:center;justify-content:center;cursor:pointer;background:none;transition:all .13s;font-family:'Raleway',sans-serif;font-size:.58rem;font-weight:700;color:var(--muted);gap:3px;letter-spacing:.05em;}
.add-cube:hover{border-color:var(--accent);color:var(--accent);background:#eef0fa;}
.add-cube-plus{font-size:1.1rem;line-height:1;font-weight:300;}
.task-cube{width:82px;height:82px;flex-shrink:0;border-radius:10px;border:1.5px solid transparent;padding:7px 6px 5px;cursor:pointer;display:flex;flex-direction:column;gap:2px;position:relative;transition:all .13s;user-select:none;}
.task-cube:hover{border-color:var(--border);box-shadow:0 2px 8px rgba(80,60,40,.1);transform:translateY(-1px);}
.task-cube.selected{border-color:var(--accent)!important;box-shadow:0 0 0 2.5px rgba(107,127,212,.4)!important;transform:translateY(-1px);}
.task-cube.done{opacity:.45;}
.task-cube.done .cube-text{text-decoration:line-through;color:var(--muted);}
.cube-recur{position:absolute;bottom:4px;left:5px;width:6px;height:6px;border-radius:50%;background:rgba(107,127,212,.55);}
.cube-strip{height:3px;border-radius:2px;width:100%;flex-shrink:0;margin-bottom:1px;}
.cube-cat{font-size:.46rem;font-weight:800;letter-spacing:.1em;text-transform:uppercase;opacity:.85;line-height:1;}
.cube-text{font-size:.62rem;font-weight:500;line-height:1.28;color:var(--text);flex:1;overflow:hidden;display:-webkit-box;-webkit-line-clamp:3;-webkit-box-orient:vertical;word-break:break-word;}
.cube-bottom{display:flex;align-items:center;justify-content:flex-end;margin-top:auto;}
.cube-check{width:12px;height:12px;border-radius:50%;border:1.5px solid var(--border);cursor:pointer;flex-shrink:0;display:flex;align-items:center;justify-content:center;transition:all .13s;}
.cube-check:hover{border-color:var(--accent);}
.task-cube.done .cube-check{background:#a0b8a0;border-color:#a0b8a0;}
.cube-check-dot{width:5px;height:5px;background:#fff;border-radius:50%;display:none;}
.task-cube.done .cube-check-dot{display:block;}
.cube-actions{position:absolute;top:3px;right:3px;display:flex;gap:2px;opacity:0;transition:opacity .13s;}
.task-cube:hover .cube-actions{opacity:1;}
.cube-act{background:rgba(253,250,246,.93);border:none;cursor:pointer;color:var(--muted);font-size:.58rem;width:15px;height:15px;border-radius:4px;display:flex;align-items:center;justify-content:center;transition:all .12s;}
.cube-act:hover{background:var(--border);color:var(--text);}
.ai-bar{position:fixed;bottom:0;left:0;right:0;background:rgba(253,250,246,.95);backdrop-filter:blur(14px);border-top:1.5px solid var(--border);padding:9px 18px 11px;z-index:90;box-shadow:0 -4px 20px rgba(80,60,40,.07);}
.ai-inner{max-width:1200px;margin:0 auto;display:flex;flex-direction:column;gap:6px;}
.ai-lbl{font-size:.54rem;font-weight:800;letter-spacing:.14em;text-transform:uppercase;color:var(--muted);}
.ai-row{display:flex;gap:6px;}
.ai-input{flex:1;background:var(--surface);border:1.5px solid var(--border);border-radius:11px;padding:9px 13px;font-family:'Raleway',sans-serif;font-size:.8rem;font-weight:400;color:var(--text);outline:none;transition:border-color .15s;}
.ai-input:focus{border-color:var(--accent);}
.ai-input::placeholder{color:var(--muted);}
.ai-btn{background:var(--accent);color:#fff;border:none;border-radius:11px;padding:9px 15px;font-family:'Raleway',sans-serif;font-size:.7rem;font-weight:800;cursor:pointer;transition:background .15s;white-space:nowrap;display:flex;align-items:center;gap:4px;letter-spacing:.05em;}
.ai-btn:hover{background:#5a6ec4;}
.ai-btn:disabled{opacity:.5;cursor:default;}
.dots span{display:inline-block;width:4px;height:4px;border-radius:50%;background:currentColor;margin:0 2px;animation:bounce 1s ease infinite;}
.dots span:nth-child(2){animation-delay:.15s;}
.dots span:nth-child(3){animation-delay:.3s;}
@keyframes bounce{0%,80%,100%{transform:scale(.6);opacity:.4}40%{transform:scale(1);opacity:1}}
.ai-prev{background:var(--surface);border:1.5px solid var(--border);border-radius:11px;padding:9px 13px;display:flex;flex-direction:column;gap:6px;}
.ai-prev-title{font-size:.54rem;font-weight:800;text-transform:uppercase;letter-spacing:.12em;color:var(--accent);}
.ai-flds{display:grid;grid-template-columns:2fr 1fr 1fr 1fr 1fr;gap:6px;align-items:end;}
.ai-fld{display:flex;flex-direction:column;gap:2px;}
.ai-fld label{font-size:.52rem;font-weight:800;text-transform:uppercase;letter-spacing:.09em;color:var(--muted);}
.ai-fld input,.ai-fld select{background:var(--bg);border:1.5px solid var(--border);border-radius:7px;padding:5px 8px;font-family:'Raleway',sans-serif;font-size:.72rem;color:var(--text);outline:none;}
.ai-recur-note{font-size:.61rem;font-weight:600;color:var(--accent);}
.ai-acts{display:flex;gap:6px;justify-content:flex-end;align-items:center;}
.btn-ok{background:var(--accent);color:#fff;border:none;border-radius:50px;padding:6px 14px;font-family:'Raleway',sans-serif;font-size:.67rem;font-weight:800;cursor:pointer;}
.btn-ok:hover{background:#5a6ec4;}
.btn-x{background:var(--surface2);color:var(--muted);border:1.5px solid var(--border);border-radius:50px;padding:6px 11px;font-family:'Raleway',sans-serif;font-size:.67rem;font-weight:600;cursor:pointer;}
.btn-x:hover{background:var(--border);}
.modal-bg{position:fixed;inset:0;background:rgba(45,40,32,.3);z-index:200;display:flex;align-items:center;justify-content:center;backdrop-filter:blur(5px);}
.modal{background:var(--surface);border-radius:18px;padding:22px;width:440px;max-width:95vw;max-height:90vh;overflow-y:auto;box-shadow:0 20px 60px rgba(60,40,20,.18);border:1.5px solid var(--border);animation:mIn .2s ease;}
@keyframes mIn{from{opacity:0;transform:scale(.96) translateY(8px)}to{opacity:1;transform:scale(1) translateY(0)}}
.modal h2{font-size:1.1rem;font-weight:300;font-style:italic;letter-spacing:.03em;margin-bottom:14px;}
.modal p{font-size:.72rem;color:var(--muted);margin-bottom:12px;line-height:1.5;}
.modal label.field-label{display:block;font-size:.54rem;font-weight:800;text-transform:uppercase;letter-spacing:.11em;color:var(--muted);margin-bottom:3px;margin-top:10px;}
.modal label.field-label:first-of-type{margin-top:0;}
.modal input,.modal textarea,.modal select{width:100%;background:var(--surface2);border:1.5px solid var(--border);border-radius:8px;padding:7px 10px;font-family:'Raleway',sans-serif;font-size:.78rem;color:var(--text);outline:none;transition:border-color .15s;resize:vertical;}
.modal input:focus,.modal textarea:focus,.modal select:focus{border-color:var(--accent);}
.mbtns{display:flex;gap:6px;margin-top:14px;}
.btn-save{flex:1;background:var(--accent);color:#fff;border:none;border-radius:50px;padding:8px;font-family:'Raleway',sans-serif;font-size:.72rem;font-weight:800;cursor:pointer;}
.btn-save:hover{background:#5a6ec4;}
.btn-cancel{background:var(--surface2);color:var(--muted);border:1.5px solid var(--border);border-radius:50px;padding:8px 13px;font-family:'Raleway',sans-serif;font-size:.72rem;font-weight:600;cursor:pointer;}
.btn-cancel:hover{background:var(--border);}
.cat-grid{display:grid;grid-template-columns:1fr 1fr;gap:5px;margin-top:4px;}
.cat-opt{padding:6px 8px;border-radius:8px;border:2px solid transparent;cursor:pointer;font-size:.67rem;font-family:'Raleway',sans-serif;font-weight:700;transition:all .12s;}
.cat-opt.on{border-color:var(--text);}
.recur-toggle{display:flex;align-items:center;gap:8px;margin-top:4px;}
.recur-toggle input[type=checkbox]{accent-color:var(--accent);width:14px;height:14px;cursor:pointer;}
.recur-toggle label{font-size:.72rem;font-weight:500;color:var(--text);cursor:pointer;}
.recur-fields{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:8px;padding:10px;background:var(--surface2);border-radius:9px;border:1.5px solid var(--border);}
.recur-field{display:flex;flex-direction:column;gap:3px;}
.recur-field label{font-size:.52rem;font-weight:800;text-transform:uppercase;letter-spacing:.09em;color:var(--muted);}
.recur-field input{background:var(--surface);border:1.5px solid var(--border);border-radius:7px;padding:5px 8px;font-family:'Raleway',sans-serif;font-size:.72rem;color:var(--text);outline:none;}
.recur-field input:focus{border-color:var(--accent);}
.scope-picker{display:flex;flex-direction:column;gap:6px;margin-top:4px;}
.scope-opt{display:flex;align-items:flex-start;gap:9px;padding:9px 11px;border-radius:9px;border:1.5px solid var(--border);cursor:pointer;transition:all .13s;}
.scope-opt:hover,.scope-opt.on{border-color:var(--accent);background:#eef0fa;}
.scope-opt input[type=radio]{margin-top:2px;accent-color:var(--accent);}
.scope-title{font-size:.72rem;font-weight:700;color:var(--text);}
.scope-sub{font-size:.6rem;color:var(--muted);margin-top:1px;}
.toast{position:fixed;bottom:165px;left:50%;transform:translateX(-50%);background:#2d2820;color:#fff;padding:7px 18px;border-radius:50px;font-size:.68rem;font-weight:700;letter-spacing:.04em;z-index:300;opacity:0;transition:opacity .2s;pointer-events:none;white-space:nowrap;}
.toast.show{opacity:1;}
.search-page{max-width:1200px;margin:0 auto;}
.search-page-hdr{display:flex;align-items:center;gap:10px;margin-bottom:14px;}
.search-page-title{font-size:1rem;font-weight:300;font-style:italic;color:var(--text);flex:1;}
.search-page-close{background:var(--surface2);border:1.5px solid var(--border);border-radius:50px;padding:5px 13px;font-family:'Raleway',sans-serif;font-size:.66rem;font-weight:700;color:var(--muted);cursor:pointer;}
.search-page-close:hover{background:var(--border);color:var(--text);}
.search-day-group{background:var(--surface);border-radius:13px;border:1.5px solid var(--border);margin-bottom:8px;overflow:hidden;}
.search-day-hdr{background:var(--surface2);border-bottom:1.5px solid var(--border);padding:7px 14px;display:flex;align-items:center;gap:8px;}
.search-day-name{font-size:.6rem;font-weight:800;text-transform:uppercase;letter-spacing:.12em;color:var(--muted);}
.search-day-date{font-size:.78rem;font-weight:600;color:var(--text);}
.search-day-lane{display:flex;gap:5px;padding:10px 12px;flex-wrap:wrap;}
.color-picker-row{display:flex;gap:5px;flex-wrap:wrap;margin-top:4px;}
.color-swatch-opt{width:18px;height:18px;border-radius:50%;cursor:pointer;border:2px solid transparent;transition:all .12s;}
.color-swatch-opt:hover,.color-swatch-opt.on{border-color:var(--text);transform:scale(1.15);}
</style>
</head>
<body>
<div id="app"></div>
<div class="toast" id="toast"></div>
<script>
const DEFAULT_CATS=[{id:1,name:'Class Action',sh:'Class',c:'#b8d4e8',d:'#4a7ab5'},{id:2,name:'Personal Health',sh:'Health',c:'#b8e2b8',d:'#4a9e5a'},{id:3,name:'The Regulars',sh:'Regulars',c:'#f5d9a0',d:'#c08030'},{id:4,name:'DSA × WFP',sh:'DSA/WFP',c:'#d4c0e8',d:'#7a50b0'},{id:5,name:'Paraform',sh:'Paraform',c:'#ffc0a0',d:'#c05a38'},{id:6,name:'Misc',sh:'Misc',c:'#b8ddd0',d:'#3a8a72'}];
const PALETTE=[{c:'#b8d4e8',d:'#4a7ab5'},{c:'#b8e2b8',d:'#4a9e5a'},{c:'#f5d9a0',d:'#c08030'},{c:'#d4c0e8',d:'#7a50b0'},{c:'#ffc0a0',d:'#c05a38'},{c:'#b8ddd0',d:'#3a8a72'},{c:'#f5b8c8',d:'#b04070'},{c:'#e8d4b8',d:'#8a6030'},{c:'#c8e8f5',d:'#2a7aa0'},{c:'#e8e8b8',d:'#7a7a20'},{c:'#f0c8e8',d:'#9040a0'},{c:'#d0e8c8',d:'#407840'}];
let CATS=[...DEFAULT_CATS];
const D7=['Mon','Tue','Wed','Thu','Fri','Sat','Sun'];
const D7F=['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday'];
const MON=['January','February','March','April','May','June','July','August','September','October','November','December'];
const MONS=['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'];

function dk(d){return d.getFullYear()+'-'+String(d.getMonth()+1).padStart(2,'0')+'-'+String(d.getDate()).padStart(2,'0');}
function uid(){return Math.random().toString(36).slice(2,10);}
function esc(s){if(!s)return'';return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');}
function todayK(){return dk(new Date());}
function addDays(ds,n){var d=new Date(ds+'T12:00:00');d.setDate(d.getDate()+n);return dk(d);}
function weekDates(a){var d=new Date(a),day=d.getDay(),m=new Date(d);m.setDate(d.getDate()-((day+6)%7));return Array.from({length:7},function(_,i){var n=new Date(m);n.setDate(m.getDate()+i);return n;});}
function getCat(id){return CATS.find(function(c){return c.id===id;})||CATS[CATS.length-1]||{name:'?',sh:'?',c:'#ccc',d:'#999'};}

// ── Gist sync ───────────────────────────────────────────────────────────────
var GIST_TOKEN=localStorage.getItem('jas_gh_token')||'';
var GIST_ID=localStorage.getItem('jas_gh_gist')||'';
var syncStatus='idle'; // idle | syncing | ok | err

async function gistLoad(){
  if(!GIST_TOKEN||!GIST_ID)return null;
  try{
    var r=await fetch('https://api.github.com/gists/'+GIST_ID,{headers:{Authorization:'token '+GIST_TOKEN,Accept:'application/vnd.github.v3+json'}});
    if(!r.ok)return null;
    var data=await r.json();
    var files=data.files;
    var key=Object.keys(files)[0];
    return files[key]?JSON.parse(files[key].content):null;
  }catch(e){return null;}
}

async function gistSave(payload){
  if(!GIST_TOKEN||!GIST_ID)return;
  syncStatus='syncing';updateSyncBadge();
  try{
    var r=await fetch('https://api.github.com/gists/'+GIST_ID,{
      method:'PATCH',
      headers:{Authorization:'token '+GIST_TOKEN,Accept:'application/vnd.github.v3+json','Content-Type':'application/json'},
      body:JSON.stringify({files:{'calendar-data.json':{content:JSON.stringify(payload)}}})
    });
    syncStatus=r.ok?'ok':'err';
  }catch(e){syncStatus='err';}
  updateSyncBadge();
  setTimeout(function(){syncStatus='idle';updateSyncBadge();},2500);
}

function updateSyncBadge(){
  var el=document.getElementById('syncBadge');
  if(!el)return;
  var map={idle:['',true],syncing:['⟳ syncing',false],ok:['✓ synced',false],err:['✕ sync failed',false]};
  var v=map[syncStatus]||map.idle;
  el.textContent=v[0];
  el.style.opacity=v[1]?'0':'1';
  el.style.color=syncStatus==='err'?'var(--danger)':syncStatus==='ok'?'#4a9e5a':'var(--muted)';
}

function getAllData(){return {tasks:tasks,view:view,anchor:anchor.toISOString(),cats:CATS};}

async function saveAll(){
  localStorage.setItem('jas_t7',JSON.stringify(tasks));
  localStorage.setItem('jas_s7',JSON.stringify({anchor:anchor.toISOString(),view:view}));
  localStorage.setItem('jas_cats',JSON.stringify(CATS));
  await gistSave(getAllData());
}

// legacy wrappers so existing code still works
async function saveT(t){tasks=t;await saveAll();}
async function saveS(s){if(s.anchor)anchor=new Date(s.anchor);if(s.view)view=s.view;await saveAll();}
async function saveCats(){await saveAll();}

// local fallbacks
async function loadT(){try{var r=localStorage.getItem('jas_t7');if(r)return JSON.parse(r);}catch(e){}return{};}
async function loadS(){try{var r=localStorage.getItem('jas_s7');if(r)return JSON.parse(r);}catch(e){}return null;}
async function loadCats(){try{var r=localStorage.getItem('jas_cats');if(r)return JSON.parse(r);}catch(e){}return null;}

function openSyncSettings(){
  var ov=document.createElement('div');ov.id='syncOv';
  ov.style.cssText='position:fixed;inset:0;background:rgba(45,40,32,.45);z-index:500;display:flex;align-items:center;justify-content:center;backdrop-filter:blur(6px);';
  ov.innerHTML='<div style="background:var(--surface);border-radius:20px;padding:28px 32px;width:460px;max-width:94vw;box-shadow:0 24px 64px rgba(60,40,20,.2);border:1.5px solid var(--border);position:relative;">'
    +'<button id="syncClose" style="position:absolute;top:14px;right:16px;background:var(--surface2);border:1.5px solid var(--border);border-radius:50%;width:28px;height:28px;font-size:.8rem;cursor:pointer;color:var(--muted);">\u2715</button>'
    +'<h2 style="font-size:1.1rem;font-weight:300;font-style:italic;margin-bottom:6px;">gist sync settings</h2>'
    +'<p style="font-size:.68rem;color:var(--muted);margin-bottom:16px;line-height:1.5;">Your token and Gist ID are stored only in this browser\'s localStorage — never sent anywhere except the GitHub API.</p>'
    +'<label style="display:block;font-size:.54rem;font-weight:800;text-transform:uppercase;letter-spacing:.11em;color:var(--muted);margin-bottom:3px;">GitHub Personal Access Token</label>'
    +'<input id="syncToken" type="password" style="width:100%;background:var(--surface2);border:1.5px solid var(--border);border-radius:8px;padding:7px 10px;font-family:\'Raleway\',sans-serif;font-size:.78rem;color:var(--text);outline:none;margin-bottom:12px;" placeholder="ghp_..." value="'+GIST_TOKEN+'">'
    +'<label style="display:block;font-size:.54rem;font-weight:800;text-transform:uppercase;letter-spacing:.11em;color:var(--muted);margin-bottom:3px;">Gist ID</label>'
    +'<input id="syncGist" type="text" style="width:100%;background:var(--surface2);border:1.5px solid var(--border);border-radius:8px;padding:7px 10px;font-family:\'Raleway\',sans-serif;font-size:.78rem;color:var(--text);outline:none;margin-bottom:16px;" placeholder="51f074..." value="'+GIST_ID+'">'
    +'<div style="display:flex;gap:8px;justify-content:flex-end;">'
    +'<button id="syncClear" style="background:var(--surface2);color:var(--danger);border:1.5px solid #f0c0b0;border-radius:50px;padding:7px 14px;font-family:\'Raleway\',sans-serif;font-size:.7rem;font-weight:700;cursor:pointer;">clear</button>'
    +'<button id="syncSave" style="background:var(--accent);color:#fff;border:none;border-radius:50px;padding:7px 18px;font-family:\'Raleway\',sans-serif;font-size:.7rem;font-weight:800;cursor:pointer;">save &amp; sync now</button>'
    +'</div></div>';
  document.body.appendChild(ov);
  document.getElementById('syncClose').addEventListener('click',function(){ov.remove();});
  ov.addEventListener('click',function(e){if(e.target===ov)ov.remove();});
  document.getElementById('syncClear').addEventListener('click',function(){
    localStorage.removeItem('jas_gh_token');localStorage.removeItem('jas_gh_gist');
    GIST_TOKEN='';GIST_ID='';ov.remove();toast('Sync credentials cleared');updateSyncBadge();
  });
  document.getElementById('syncSave').addEventListener('click',async function(){
    GIST_TOKEN=document.getElementById('syncToken').value.trim();
    GIST_ID=document.getElementById('syncGist').value.trim();
    localStorage.setItem('jas_gh_token',GIST_TOKEN);
    localStorage.setItem('jas_gh_gist',GIST_ID);
    ov.remove();
    toast('Credentials saved — syncing now...');
    await gistSave(getAllData());
    toast('Synced to Gist \u2713');
  });
}

var tasks={},anchor=new Date(),view='week',modal=null,drag=null;
var ai={inp:'',loading:false,prev:null};
var selCat=null,searchQ='',searchActive=false;
var selTasks=new Set(),selDays=new Set(),clipboard=[];
var lastClickedDay=null;
var toastTmr=null;

function toast(msg,dur){
  dur=dur||2400;
  var t=document.getElementById('toast');
  t.textContent=msg;t.classList.add('show');
  clearTimeout(toastTmr);
  toastTmr=setTimeout(function(){t.classList.remove('show');},dur);
}

function matchQ(t){
  if(!searchQ)return true;
  var q=searchQ.toLowerCase();
  return (t.text||'').toLowerCase().includes(q)||(t.desc||'').toLowerCase().includes(q);
}

function getMatches(){
  if(!searchQ)return[];
  var r=[];
  Object.entries(tasks).forEach(function(e){
    var k=e[0],ts=e[1];
    ts.forEach(function(t,i){if(matchQ(t))r.push({k:k,i:i,t:t});});
  });
  return r;
}

function isRecur(t){return !!(t&&t.recurId);}

function getFollowing(recurId,fromKey){
  var r=[];
  Object.entries(tasks).forEach(function(e){
    var k=e[0],ts=e[1];
    if(k>=fromKey)ts.forEach(function(t,i){if(t.recurId===recurId)r.push({k:k,i:i,t:t});});
  });
  return r;
}

function csvEscape(v){
  var s=String(v||'');
  return (s.includes(',')||s.includes('"')||s.includes('\n'))?'"'+s.replace(/"/g,'""')+'"':s;
}

function exportCSV(){
  var rows=[['Date','Day','Category','Task','Done','Notes']];
  var data=[];
  if(searchActive){
    var matches=getMatches(),byDay={};
    matches.forEach(function(m){if(!byDay[m.k])byDay[m.k]=[];byDay[m.k].push(m.t);});
    Object.keys(byDay).sort().forEach(function(k){byDay[k].forEach(function(t){data.push({k:k,t:t});});});
  } else if(view==='week'){
    weekDates(anchor).forEach(function(d){var k=dk(d);(tasks[k]||[]).forEach(function(t){data.push({k:k,t:t});});});
  } else {
    var y=anchor.getFullYear(),mo=anchor.getMonth();
    for(var day=1;day<=31;day++){var dt=new Date(y,mo,day);if(dt.getMonth()!==mo)break;var k=dk(dt);(tasks[k]||[]).forEach(function(t){data.push({k:k,t:t});});}
  }
  data.forEach(function(item){
    var d=new Date(item.k+'T12:00:00'),dayIdx=(d.getDay()+6)%7;
    var cat=getCat(item.t.cat);
    rows.push([item.k,D7F[dayIdx],cat.name,item.t.text,item.t.done?'yes':'no',item.t.desc||'']);
  });
  var csv=rows.map(function(r){return r.map(csvEscape).join(',');}).join('\n');
  var blob=new Blob([csv],{type:'text/csv'});
  var url=URL.createObjectURL(blob);
  var a=document.createElement('a');a.href=url;
  var label=searchActive?'search-'+searchQ:view==='week'?'week-'+dk(weekDates(anchor)[0]):anchor.getFullYear()+'-'+String(anchor.getMonth()+1).padStart(2,'0');
  a.download='jasmine-calendar-'+label+'.csv';
  a.click();URL.revokeObjectURL(url);
  toast('Exported '+data.length+' task'+(data.length!==1?'s':'')+' to CSV');
}

function scrollToToday(){
  setTimeout(function(){
    var el=document.querySelector('.day-row.today');
    if(el)el.scrollIntoView({behavior:'smooth',block:'center'});
  },80);
}

function render(){
  var app=document.getElementById('app');
  app.innerHTML='';
  var root=document.createElement('div');
  root.style.cssText='display:flex;flex-direction:column;min-height:100vh;';
  root.appendChild(bHdr());
  root.appendChild(bSearchBar());
  if(selTasks.size>0)root.appendChild(bMassBar());
  root.appendChild(bLgnd());
  var main=document.createElement('div');main.className='main';main.id='mainScroll';
  if(searchActive)main.appendChild(bSearchPage());
  else if(view==='week')main.appendChild(bWeek());
  else main.appendChild(bMonthScroll());
  root.appendChild(main);
  root.appendChild(bAIBar());
  if(modal)root.appendChild(bModal());
  app.appendChild(root);
  attachAll();
}

function bHdr(){
  var wd=weekDates(anchor),f=wd[0],l=wd[6];
  var lbl=view==='week'
    ?(MONS[f.getMonth()]+' '+f.getDate()+' \u2013 '+(f.getMonth()!==l.getMonth()?MONS[l.getMonth()]+' ':'')+l.getDate()+', '+l.getFullYear())
    :(MON[anchor.getMonth()]+' '+anchor.getFullYear());
  var h=document.createElement('div');h.className='hdr';
  h.innerHTML='<div class="brand"><h1>jasmine\'s calendar</h1><span class="brand-pill">personal</span></div>'
    +'<div class="hdr-right">'
    +'<button class="nbtn" id="prevB">\u2190 prev</button>'
    +'<span class="wklbl">'+lbl+'</span>'
    +'<button class="nbtn" id="nextB">next \u2192</button>'
    +'<button class="nbtn" id="todayB">today</button>'
    +'<div class="vtgl"><button class="vbtn '+(view==='week'?'on':'')+'" id="weekB">WEEK</button>'
    +'<button class="vbtn '+(view==='month'?'on':'')+'" id="monthB">MONTH</button></div>'
    +'<button class="nbtn" id="syncBtn" title="Gist sync settings">\u2601</button>'
    +'<span id="syncBadge" style="font-size:.58rem;font-weight:700;letter-spacing:.04em;transition:opacity .3s;opacity:0;"></span>'
    +'</div>';
  return h;
}

function bSearchBar(){
  var matches=getMatches(),mc=matches.length;
  var taskSel=selTasks.size,daySel=selDays.size,hasSel=taskSel>0||daySel>0,hasClip=clipboard.length>0;
  var bar=document.createElement('div');bar.className='search-bar';
  bar.innerHTML='<div class="search-wrap"><span class="search-icon">\u2315</span>'
    +'<input class="search-input" id="searchI" type="text" placeholder="search tasks\u2026 press Enter to view results" value="'+esc(searchQ)+'">'
    +'<button class="search-clear '+(searchQ?'show':'')+'" id="searchClr">\u2715</button></div>'
    +(searchQ&&mc>0&&!searchActive?'<span class="match-count">'+mc+' match'+(mc!==1?'es':'')+'</span>':'');
  var tb=document.createElement('div');tb.className='toolbar';
  if(hasSel){
    if(taskSel>0)tb.innerHTML+='<span class="sel-info">'+taskSel+' task'+(taskSel>1?'s':'')+' selected</span>';
    if(daySel>0)tb.innerHTML+='<span class="sel-info">'+daySel+' day'+(daySel>1?'s':'')+' highlighted</span>';
    tb.innerHTML+='<button class="nbtn" id="copySelBtn">\u2318 copy</button><button class="nbtn danger" id="delSelBtn">\u2715 delete</button><button class="nbtn" id="clearSelBtn">clear</button>';
  }
  if(hasClip)tb.innerHTML+='<button class="nbtn active" id="pasteBtn">\uD83D\uDCCB paste '+clipboard.length+'</button>';
  var csvBtn=document.createElement('button');csvBtn.className='nbtn';csvBtn.id='csvBtn';csvBtn.title='Export to CSV';csvBtn.innerHTML='&#9113;';csvBtn.style.fontSize='.82rem';
  tb.appendChild(csvBtn);
  var kbBtn=document.createElement('button');kbBtn.className='nbtn';kbBtn.id='kbBtn';kbBtn.title='View shortcuts here';kbBtn.textContent='\u2328';
  tb.appendChild(kbBtn);
  bar.appendChild(tb);
  return bar;
}

function bMassBar(){
  var bar=document.createElement('div');bar.className='mass-bar';
  bar.innerHTML='<span class="mass-label">\u270e mass edit '+selTasks.size+' tasks</span>'
    +'<div class="mdiv"></div>'
    +'<div class="mass-field"><label>rename to</label><input id="massText" type="text" placeholder="leave blank to keep" style="width:160px"></div>'
    +'<div class="mdiv"></div>'
    +'<div class="mass-field"><label>category</label><select id="massCat"><option value="">\u2014 keep \u2014</option>'+CATS.map(function(c){return '<option value="'+c.id+'">'+esc(c.name)+'</option>';}).join('')+'</select></div>'
    +'<div class="mdiv"></div>'
    +'<div class="mass-field"><label>status</label><select id="massDone"><option value="">\u2014 keep \u2014</option><option value="done">\u2713 done</option><option value="undone">\u25cb not done</option></select></div>'
    +'<div class="mdiv"></div>'
    +'<button class="nbtn active" id="applyMassBtn">apply</button><button class="nbtn" id="cancelMassBtn">cancel</button>';
  return bar;
}

function bLgnd(){
  var l=document.createElement('div');l.className='lgnd';l.innerHTML='<span class="lgnd-lbl">categories</span>';
  CATS.forEach(function(c){
    var i=document.createElement('div');i.className='lgnd-item';
    i.innerHTML='<div class="lgnd-dot" style="background:'+c.d+'"></div>'+esc(c.name)+'<button class="lgnd-edit-btn" data-editcat="'+c.id+'">edit</button>';
    l.appendChild(i);
  });
  var addBtn=document.createElement('button');addBtn.className='lgnd-add';addBtn.id='addCatBtn';addBtn.textContent='+ new category';
  l.appendChild(addBtn);
  return l;
}

function bSearchPage(){
  var matches=getMatches(),byDay={};
  matches.forEach(function(m){if(!byDay[m.k])byDay[m.k]=[];byDay[m.k].push({i:m.i,t:m.t});});
  var sortedKeys=Object.keys(byDay).sort();
  var wrap=document.createElement('div');wrap.className='search-page';
  var hdr=document.createElement('div');hdr.className='search-page-hdr';
  hdr.innerHTML='<div class="search-page-title">results for "<strong>'+esc(searchQ)+'</strong>" \u2014 '+matches.length+' match'+(matches.length!==1?'es':'')+'</div>'
    +'<button class="search-page-close" id="searchPageClose">\u2715 back to calendar</button>';
  wrap.appendChild(hdr);
  if(!sortedKeys.length){var e=document.createElement('div');e.style.cssText='color:var(--muted);font-size:.78rem;padding:20px 0;';e.textContent='No matches found.';wrap.appendChild(e);}
  sortedKeys.forEach(function(k){
    var d=new Date(k+'T12:00:00'),dayIdx=(d.getDay()+6)%7;
    var group=document.createElement('div');group.className='search-day-group';
    var ghdr=document.createElement('div');ghdr.className='search-day-hdr';
    ghdr.innerHTML='<span class="search-day-name">'+D7[dayIdx]+'</span><span class="search-day-date">'+MONS[d.getMonth()]+' '+d.getDate()+', '+d.getFullYear()+'</span>';
    group.appendChild(ghdr);
    var lane=document.createElement('div');lane.className='search-day-lane';
    byDay[k].forEach(function(item){lane.appendChild(bCube(item.t,k,item.i,selTasks.has(k+':'+item.i)));});
    group.appendChild(lane);wrap.appendChild(group);
  });
  return wrap;
}

function bMonthScroll(){
  var wrap=document.createElement('div');wrap.className='month-scroll-wrap';
  var today=todayK(),y=anchor.getFullYear(),mo=anchor.getMonth();
  for(var day=1;day<=31;day++){
    var d=new Date(y,mo,day);
    if(d.getMonth()!==mo)break;
    var key=dk(d),ts=tasks[key]||[],isToday=key===today,dayIdx=(d.getDay()+6)%7,isWknd=dayIdx>=5,isDaySel=selDays.has(key);
    var row=document.createElement('div');
    row.className='day-row'+(isToday?' today':'')+(isWknd?' weekend':'')+(isDaySel?' day-sel':'');
    var lbl=document.createElement('div');lbl.className='day-lbl';lbl.dataset.daykey=key;
    lbl.innerHTML='<div class="day-name">'+D7[dayIdx]+'</div><div class="day-num">'+d.getDate()+'</div><div class="day-ct">'+ts.length+'/20</div>';
    row.appendChild(lbl);
    var lane=document.createElement('div');lane.className='day-lane';lane.dataset.key=key;
    ts.forEach(function(t,idx){lane.appendChild(bCube(t,key,idx,selTasks.has(key+':'+idx)));});
    if(ts.length<20){var ab=document.createElement('button');ab.className='add-cube';ab.dataset.key=key;ab.innerHTML='<span class="add-cube-plus">+</span><span>add task</span>';lane.appendChild(ab);}
    row.appendChild(lane);wrap.appendChild(row);
  }
  return wrap;
}

function bWeek(){
  var wd=weekDates(anchor),today=todayK();
  var wrap=document.createElement('div');wrap.className='week-wrap';
  wd.forEach(function(d,i){
    var key=dk(d),ts=tasks[key]||[],isToday=key===today,isWknd=i>=5,isDaySel=selDays.has(key);
    var row=document.createElement('div');
    row.className='day-row'+(isToday?' today':'')+(isWknd?' weekend':'')+(isDaySel?' day-sel':'');
    var lbl=document.createElement('div');lbl.className='day-lbl';lbl.dataset.daykey=key;
    lbl.innerHTML='<div class="day-name">'+D7[i]+'</div><div class="day-num">'+d.getDate()+'</div><div class="day-ct">'+ts.length+'/20</div>';
    row.appendChild(lbl);
    var lane=document.createElement('div');lane.className='day-lane';lane.dataset.key=key;
    ts.forEach(function(t,idx){lane.appendChild(bCube(t,key,idx,selTasks.has(key+':'+idx)));});
    if(ts.length<20){var ab=document.createElement('button');ab.className='add-cube';ab.dataset.key=key;ab.innerHTML='<span class="add-cube-plus">+</span><span>add task</span>';lane.appendChild(ab);}
    row.appendChild(lane);wrap.appendChild(row);
  });
  return wrap;
}

function bCube(t,key,idx,isSel){
  var cat=getCat(t.cat);
  var cls='task-cube'+(t.done?' done':'')+(isSel?' selected':'');
  var div=document.createElement('div');div.className=cls;div.draggable=true;div.dataset.key=key;div.dataset.idx=idx;
  div.style.background='color-mix(in srgb, '+cat.c+' 30%, var(--surface2))';
  div.innerHTML='<div class="cube-strip" style="background:'+cat.d+'"></div>'
    +'<div class="cube-cat" style="color:'+cat.d+'">'+esc(cat.sh)+'</div>'
    +'<div class="cube-text">'+esc(t.text)+'</div>'
    +'<div class="cube-bottom"><div class="cube-check" data-chk="'+key+':'+idx+'"><div class="cube-check-dot"></div></div></div>'
    +(isRecur(t)?'<div class="cube-recur" title="recurring"></div>':'')
    +'<div class="cube-actions"><button class="cube-act" data-edit="'+key+':'+idx+'">\u270e</button><button class="cube-act" data-del="'+key+':'+idx+'">\u2715</button></div>';
  return div;
}

function bAIBar(){
  var bar=document.createElement('div');bar.className='ai-bar';
  var inner=document.createElement('div');inner.className='ai-inner';
  inner.innerHTML='<div class="ai-lbl">\u2736 ai task entry \u2014 dates, categories, recurrence all understood</div>';
  var row=document.createElement('div');row.className='ai-row';
  row.innerHTML='<input class="ai-input" id="aiI" type="text" placeholder=\'e.g. "march 18 paraform add enya" \u00b7 "gym every day for 4 weeks"\' value="'+esc(ai.inp)+'">'
    +'<button class="ai-btn" id="aiS" '+(ai.loading?'disabled':'')+'>'+(ai.loading?'<span class="dots"><span></span><span></span><span></span></span>':'\u2736 parse')+'</button>';
  inner.appendChild(row);
  if(ai.prev){
    var p=ai.prev,total=p.recur||1,isR=total>1,last=isR?addDays(p.date,(total-1)*(p.every||1)):'';
    var prev=document.createElement('div');prev.className='ai-prev';
    prev.innerHTML='<div class="ai-prev-title">\u2736 parsed'+(isR?' \u00b7 <strong>'+total+' tasks</strong> ending '+last:'')+' \u2014 edit if needed</div>'
      +'<div class="ai-flds">'
      +'<div class="ai-fld"><label>Task name</label><input id="pText" value="'+esc(p.text)+'" maxlength="200"></div>'
      +'<div class="ai-fld"><label>Category</label><select id="pCat">'+CATS.map(function(c){return '<option value="'+c.id+'"'+(c.id===p.cat?' selected':'')+'>'+esc(c.name)+'</option>';}).join('')+'</select></div>'
      +'<div class="ai-fld"><label>Start date</label><input type="date" id="pDate" value="'+p.date+'"></div>'
      +'<div class="ai-fld"><label>Every N days</label><input type="number" id="pEvery" min="1" max="365" value="'+(p.every||1)+'"></div>'
      +'<div class="ai-fld"><label>Repeat times</label><input type="number" id="pRecur" min="1" max="365" value="'+(p.recur||1)+'"></div>'
      +'</div>'
      +(isR?'<div class="ai-recur-note">every '+(p.every||1)+' day(s) \u00d7 '+total+' times \u2192 ends '+last+'</div>':'')
      +'<div class="ai-acts"><button class="btn-x" id="aiX">discard</button><button class="btn-ok" id="aiOk">add to calendar \u2736</button></div>';
    inner.appendChild(prev);
  }
  bar.appendChild(inner);
  return bar;
}

function bModal(){
  if(modal.mode==='recurScope'){
    var ov=document.createElement('div');ov.className='modal-bg';ov.id='mOv';
    ov.innerHTML='<div class="modal"><h2>edit recurring event</h2>'
      +'<p>"<strong>'+esc(modal.task.text)+'</strong>" is part of a repeating series.</p>'
      +'<div class="scope-picker">'
      +'<label class="scope-opt on" id="scopeThis"><input type="radio" name="scope" value="this" checked><div><div class="scope-title">This event only</div><div class="scope-sub">Only the '+modal.dateKey+' occurrence</div></div></label>'
      +'<label class="scope-opt" id="scopeFollow"><input type="radio" name="scope" value="following"><div><div class="scope-title">This and all following</div><div class="scope-sub">Updates every event from '+modal.dateKey+' onward</div></div></label>'
      +'</div>'
      +'<div class="mbtns"><button class="btn-cancel" id="mCan">cancel</button><button class="btn-save" id="scopeGo">continue \u2192</button></div>'
      +'</div>';
    return ov;
  }
  if(modal.mode==='catEditor'){
    var ov=document.createElement('div');ov.className='modal-bg';ov.id='mOv';
    var isNew=modal.isNew,cat=modal.cat;
    var palOpts=PALETTE.map(function(p,pi){return '<div class="color-swatch-opt'+(cat.d===p.d?' on':'')+'" style="background:'+p.d+'" data-pi="'+pi+'"></div>';}).join('');
    ov.innerHTML='<div class="modal"><h2>'+(isNew?'new category':'edit category')+'</h2>'
      +'<label class="field-label">Name</label><input id="catNameI" type="text" maxlength="40" value="'+esc(cat.name)+'" placeholder="Category name">'
      +'<label class="field-label">Short label</label><input id="catShI" type="text" maxlength="12" value="'+esc(cat.sh)+'" placeholder="Short name">'
      +'<label class="field-label">Color</label>'
      +'<div class="color-picker-row" id="colorPicker">'+palOpts+'</div>'
      +'<div style="margin-top:8px;display:flex;align-items:center;gap:8px;">'
      +'<div id="catPreview" style="background:'+cat.c+';color:'+cat.d+';padding:5px 10px;border-radius:7px;font-size:.67rem;font-weight:700;border:2px solid '+cat.d+'">'+esc(cat.sh||'Preview')+'</div>'
      +'<span style="font-size:.6rem;color:var(--muted);">preview</span></div>'
      +'<div class="mbtns">'
      +(!isNew?'<button class="btn-cancel" id="catDelBtn" style="color:var(--danger);border-color:#f0c0b0;">delete</button>':'')
      +'<button class="btn-cancel" id="mCan">cancel</button>'
      +'<button class="btn-save" id="catSaveBtn">'+(isNew?'create':'save')+'</button>'
      +'</div></div>';
    return ov;
  }
  // add / edit task
  var isEdit=modal.mode==='edit',t=isEdit?modal.task:null;
  var curCatId=t?t.cat:(selCat||CATS[0].id);
  var ov=document.createElement('div');ov.className='modal-bg';ov.id='mOv';
  var catO=CATS.map(function(c){return '<div class="cat-opt'+(curCatId===c.id?' on':'')+'" style="background:'+c.c+';color:'+c.d+'" data-catid="'+c.id+'">'+esc(c.name)+'</div>';}).join('');
  var recurChecked=modal.recurOn||false;
  ov.innerHTML='<div class="modal"><h2>'+(isEdit?'edit task':'add task')+'</h2>'
    +'<label class="field-label">Task</label>'
    +'<input id="mT" type="text" maxlength="200" value="'+(t?esc(t.text):'')+'" placeholder="What needs doing?">'
    +'<label class="field-label">Category</label>'
    +'<div class="cat-grid" id="catG">'+catO+'</div>'
    +'<label class="field-label">Description / link (optional)</label>'
    +'<textarea id="mD" rows="2">'+(t&&t.desc?esc(t.desc):'')+'</textarea>'
    +'<label class="field-label" style="margin-top:12px">Recurring?</label>'
    +'<div class="recur-toggle"><input type="checkbox" id="recurChk" '+(recurChecked?'checked':'')+'><label for="recurChk">Repeat this task</label></div>'
    +'<div class="recur-fields" id="recurFields" style="display:'+(recurChecked?'grid':'none')+'">'
    +'<div class="recur-field"><label>Every N days</label><input type="number" id="mEvery" min="1" max="365" value="'+(modal.every||1)+'"></div>'
    +'<div class="recur-field"><label>Repeat times</label><input type="number" id="mRecur" min="2" max="365" value="'+(modal.recur||2)+'"></div>'
    +'</div>'
    +'<div class="mbtns"><button class="btn-cancel" id="mCan">cancel</button><button class="btn-save" id="mSav">'+(isEdit?'save':'add task')+'</button></div>'
    +'</div>';
  return ov;
}

async function parseAI(inp){
  ai.loading=true;ai.prev=null;render();
  var today=new Date(),todayStr=dk(today),yr=today.getFullYear();
  var wd=weekDates(anchor),wctx=wd.map(function(d,i){return D7F[i]+'='+dk(d);}).join(', ');
  var catCtx=CATS.map(function(c){return c.id+'='+c.name;}).join(', ');
  var prompt='Task parser. Today: '+todayStr+' ('+D7F[(today.getDay()+6)%7]+', '+yr+'). Week: '+wctx+'.\nCategories: '+catCtx+'\nInput: "'+inp+'"\nReply ONLY JSON: {"text":"","cat":1,"date":"YYYY-MM-DD","desc":"","recur":1,"every":1}';
  try{
    var r=await fetch('https://api.anthropic.com/v1/messages',{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify({model:'claude-sonnet-4-20250514',max_tokens:200,messages:[{role:'user',content:prompt}]})});
    var data=await r.json();
    var raw=(data.content&&data.content.find(function(b){return b.type==='text';})||{}).text||'';
    raw=raw.trim().replace(/^```[\w]*\n?/,'').replace(/\n?```$/,'').trim();
    var p=JSON.parse(raw);
    ai.prev={text:(p.text||inp).trim(),cat:parseInt(p.cat)||CATS[0].id,date:p.date||todayStr,desc:p.desc||'',recur:Math.max(1,parseInt(p.recur)||1),every:Math.max(1,parseInt(p.every)||1)};
  }catch(e){ai.prev={text:inp.trim(),cat:CATS[0].id,date:todayStr,desc:'',recur:1,every:1};}
  ai.loading=false;render();
  setTimeout(function(){var el=document.getElementById('pText');if(el)el.focus();},50);
}

function copySelected(){
  clipboard=[];
  selTasks.forEach(function(id){var parts=id.split(':'),k=parts[0],i=parseInt(parts[1]),t=tasks[k]&&tasks[k][i];if(t)clipboard.push({text:t.text,cat:t.cat,desc:t.desc||''});});
  if(clipboard.length){toast(clipboard.length+' task'+(clipboard.length>1?'s':'')+' copied');selTasks.clear();render();}
}

function pasteToDays(){
  if(!clipboard.length||!selDays.size)return;
  var count=0;
  selDays.forEach(function(k){
    if(!tasks[k])tasks[k]=[];
    clipboard.forEach(function(t){if(tasks[k].length<20){tasks[k].push({id:uid(),text:t.text,cat:t.cat,desc:t.desc||'',done:false});count++;}});
  });
  saveT(tasks);toast('Pasted into '+selDays.size+' day'+(selDays.size>1?'s':'')+' ('+count+' tasks)');selDays.clear();render();
}

async function deleteSelected(){
  if(!selTasks.size)return;
  var count=selTasks.size,byKey={};
  selTasks.forEach(function(id){var parts=id.split(':'),k=parts[0],i=parseInt(parts[1]);if(!byKey[k])byKey[k]=[];byKey[k].push(i);});
  Object.entries(byKey).forEach(function(e){var k=e[0],idxs=e[1];idxs.sort(function(a,b){return b-a;}).forEach(function(i){if(tasks[k])tasks[k].splice(i,1);});});
  await saveT(tasks);toast(count+' task'+(count!==1?'s':'')+' deleted');selTasks.clear();selDays.clear();render();
}

function attachAll(){
  document.getElementById('prevB').addEventListener('click',async function(){
    if(view==='week')anchor.setDate(anchor.getDate()-7);else anchor.setMonth(anchor.getMonth()-1);
    await saveS({anchor:anchor.toISOString(),view:view});render();
  });
  document.getElementById('nextB').addEventListener('click',async function(){
    if(view==='week')anchor.setDate(anchor.getDate()+7);else anchor.setMonth(anchor.getMonth()+1);
    await saveS({anchor:anchor.toISOString(),view:view});render();
  });
  document.getElementById('todayB').addEventListener('click',async function(){
    anchor=new Date();searchActive=false;
    await saveS({anchor:anchor.toISOString(),view:view});render();scrollToToday();
  });
  document.getElementById('weekB').addEventListener('click',async function(){view='week';searchActive=false;await saveS({anchor:anchor.toISOString(),view:view});render();});
  document.getElementById('monthB').addEventListener('click',async function(){view='month';searchActive=false;await saveS({anchor:anchor.toISOString(),view:view});render();scrollToToday();});

  var si=document.getElementById('searchI');
  if(si){
    si.addEventListener('input',function(e){
      searchQ=e.target.value;
      var pos=e.target.selectionStart;
      if(!searchQ)searchActive=false;
      render();
      var inp=document.getElementById('searchI');
      if(inp){inp.focus();inp.setSelectionRange(pos,pos);}
    });
    si.addEventListener('keydown',function(e){if(e.key==='Enter'&&searchQ.trim()){searchActive=true;render();}});
  }
  var sc=document.getElementById('searchClr');if(sc)sc.addEventListener('click',function(){searchQ='';searchActive=false;selTasks.clear();render();});
  var spc=document.getElementById('searchPageClose');if(spc)spc.addEventListener('click',function(){searchActive=false;render();});
  var csvBtn=document.getElementById('csvBtn');if(csvBtn)csvBtn.addEventListener('click',exportCSV);
  var copyBtn=document.getElementById('copySelBtn');if(copyBtn)copyBtn.addEventListener('click',copySelected);
  var delBtn=document.getElementById('delSelBtn');if(delBtn)delBtn.addEventListener('click',deleteSelected);
  var clrBtn=document.getElementById('clearSelBtn');if(clrBtn)clrBtn.addEventListener('click',function(){selTasks.clear();selDays.clear();render();});
  var pasteBtn=document.getElementById('pasteBtn');if(pasteBtn)pasteBtn.addEventListener('click',function(){if(selDays.size>0)pasteToDays();else toast('Click day labels first to select target days');});
  var cancelMass=document.getElementById('cancelMassBtn');if(cancelMass)cancelMass.addEventListener('click',function(){selTasks.clear();render();});
  var applyMass=document.getElementById('applyMassBtn');
  if(applyMass)applyMass.addEventListener('click',async function(){
    var newText=document.getElementById('massText').value.trim();
    var newCat=document.getElementById('massCat').value;
    var newDone=document.getElementById('massDone').value;
    var changed=0;
    selTasks.forEach(function(id){var parts=id.split(':'),k=parts[0],i=parseInt(parts[1]),t=tasks[k]&&tasks[k][i];if(!t)return;if(newText)t.text=newText;if(newCat)t.cat=parseInt(newCat);if(newDone==='done')t.done=true;if(newDone==='undone')t.done=false;changed++;});
    await saveT(tasks);toast('Updated '+changed+' task'+(changed!==1?'s':''));selTasks.clear();render();
  });

  document.querySelectorAll('[data-editcat]').forEach(function(btn){
    btn.addEventListener('click',function(e){
      e.stopPropagation();
      var cat=CATS.find(function(c){return c.id===parseInt(btn.dataset.editcat);});
      if(!cat)return;
      modal={mode:'catEditor',isNew:false,cat:Object.assign({},cat)};render();
    });
  });
  var addCatBtn=document.getElementById('addCatBtn');
  if(addCatBtn)addCatBtn.addEventListener('click',function(){
    var newId=Math.max.apply(null,[0].concat(CATS.map(function(c){return c.id;})))+1;
    modal={mode:'catEditor',isNew:true,cat:{id:newId,name:'',sh:'',c:PALETTE[0].c,d:PALETTE[0].d}};
    render();setTimeout(function(){var el=document.getElementById('catNameI');if(el)el.focus();},30);
  });

  document.querySelectorAll('[data-daykey]').forEach(function(lbl){
    lbl.addEventListener('click',function(){
      var key=lbl.dataset.daykey;
      if(selDays.has(key)){selDays.delete(key);lastClickedDay=null;}
      else{selDays.add(key);lastClickedDay=key;}
      render();
    });
  });

  document.querySelectorAll('.task-cube').forEach(function(cube){
    cube.addEventListener('click',function(e){
      if(e.target.closest('[data-chk]')||e.target.closest('[data-edit]')||e.target.closest('[data-del]'))return;
      var id=cube.dataset.key+':'+cube.dataset.idx;
      if(selTasks.has(id))selTasks.delete(id);else selTasks.add(id);render();
    });
    cube.addEventListener('dragstart',function(e){
      if(e.target.closest('[data-chk]')||e.target.closest('[data-edit]')||e.target.closest('[data-del]')){e.preventDefault();return;}
      drag={fromKey:cube.dataset.key,fromIdx:parseInt(cube.dataset.idx)};
      setTimeout(function(){cube.classList.add('dragging');},0);e.dataTransfer.effectAllowed='move';
    });
    cube.addEventListener('dragend',function(){drag=null;document.querySelectorAll('.task-cube').forEach(function(c){c.classList.remove('dragging','drag-over');});});
    cube.addEventListener('dragover',function(e){e.preventDefault();document.querySelectorAll('.task-cube').forEach(function(c){c.classList.remove('drag-over');});cube.classList.add('drag-over');});
    cube.addEventListener('drop',async function(e){
      e.preventDefault();if(!drag)return;
      var toKey=cube.dataset.key,toIdx=parseInt(cube.dataset.idx);
      if(drag.fromKey===toKey&&drag.fromIdx===toIdx)return;
      var fa=tasks[drag.fromKey]||[];if(!tasks[toKey])tasks[toKey]=[];
      var moved=fa.splice(drag.fromIdx,1)[0];
      if(drag.fromKey===toKey)fa.splice(toIdx,0,moved);else tasks[toKey].splice(toIdx,0,moved);
      await saveT(tasks);drag=null;render();
    });
  });

  document.querySelectorAll('.day-lane').forEach(function(lane){
    lane.addEventListener('dragover',function(e){e.preventDefault();});
    lane.addEventListener('drop',async function(e){
      if(!drag)return;var toKey=lane.dataset.key;
      if(!tasks[toKey])tasks[toKey]=[];if(drag.fromKey===toKey)return;
      var fa=tasks[drag.fromKey]||[];var moved=fa.splice(drag.fromIdx,1)[0];
      tasks[toKey].push(moved);await saveT(tasks);drag=null;render();
    });
  });

  document.querySelectorAll('[data-chk]').forEach(function(el){
    el.addEventListener('click',async function(e){
      e.stopPropagation();var parts=el.dataset.chk.split(':'),k=parts[0],idx=parseInt(parts[1]);
      if(tasks[k]&&tasks[k][idx]!=null){tasks[k][idx].done=!tasks[k][idx].done;await saveT(tasks);render();}
    });
  });

  document.querySelectorAll('[data-edit]').forEach(function(el){
    el.addEventListener('click',function(e){
      e.stopPropagation();var parts=el.dataset.edit.split(':'),k=parts[0],idx=parseInt(parts[1]),t=tasks[k]&&tasks[k][idx];if(!t)return;
      if(isRecur(t)){modal={mode:'recurScope',dateKey:k,taskIdx:idx,task:t,scope:'this'};}
      else{modal={mode:'edit',dateKey:k,task:t,taskIdx:idx,recurOn:false};}
      render();setTimeout(function(){var el=document.getElementById('mT');if(el)el.focus();},30);
    });
  });

  document.querySelectorAll('[data-del]').forEach(function(el){
    el.addEventListener('click',async function(e){
      e.stopPropagation();var parts=el.dataset.del.split(':'),k=parts[0],i=parseInt(parts[1]);
      if(tasks[k]){tasks[k].splice(i,1);await saveT(tasks);render();}
    });
  });

  document.querySelectorAll('input[name="scope"]').forEach(function(r){
    r.addEventListener('change',function(){modal.scope=r.value;document.querySelectorAll('.scope-opt').forEach(function(o){o.classList.remove('on');});r.closest('.scope-opt').classList.add('on');});
  });
  var scopeGo=document.getElementById('scopeGo');
  if(scopeGo)scopeGo.addEventListener('click',function(){
    modal={mode:'edit',dateKey:modal.dateKey,task:modal.task,taskIdx:modal.taskIdx,scope:modal.scope||'this',recurOn:false};
    render();setTimeout(function(){var el=document.getElementById('mT');if(el)el.focus();},30);
  });

  document.querySelectorAll('.color-swatch-opt').forEach(function(sw){
    sw.addEventListener('click',function(){
      var pi=parseInt(sw.dataset.pi);modal.cat.c=PALETTE[pi].c;modal.cat.d=PALETTE[pi].d;
      document.querySelectorAll('.color-swatch-opt').forEach(function(s){s.classList.remove('on');});sw.classList.add('on');
      var prev=document.getElementById('catPreview');
      var sh=(document.getElementById('catShI')||{}).value||modal.cat.sh||'Preview';
      if(prev){prev.style.background=modal.cat.c;prev.style.color=modal.cat.d;prev.style.borderColor=modal.cat.d;prev.textContent=sh;}
    });
  });
  var catShI=document.getElementById('catShI');if(catShI)catShI.addEventListener('input',function(e){var prev=document.getElementById('catPreview');if(prev)prev.textContent=e.target.value||'Preview';});
  var catDelBtn=document.getElementById('catDelBtn');
  if(catDelBtn)catDelBtn.addEventListener('click',async function(){
    if(CATS.length<=1){toast('Must keep at least one category');return;}
    var id=modal.cat.id;CATS=CATS.filter(function(c){return c.id!==id;});
    var fallback=CATS[0].id;
    Object.values(tasks).forEach(function(ts){ts.forEach(function(t){if(t.cat===id)t.cat=fallback;});});
    await saveCats();await saveT(tasks);modal=null;render();toast('Category deleted');
  });
  var catSaveBtn=document.getElementById('catSaveBtn');
  if(catSaveBtn)catSaveBtn.addEventListener('click',async function(){
    var name=(document.getElementById('catNameI')||{}).value&&document.getElementById('catNameI').value.trim();
    var sh=((document.getElementById('catShI')||{}).value&&document.getElementById('catShI').value.trim())||name&&name.slice(0,8)||'?';
    if(!name){if(document.getElementById('catNameI'))document.getElementById('catNameI').focus();return;}
    var isNew=modal.isNew;
    if(isNew){CATS.push({id:modal.cat.id,name:name,sh:sh,c:modal.cat.c,d:modal.cat.d});}
    else{var idx=CATS.findIndex(function(c){return c.id===modal.cat.id;});if(idx>=0)CATS[idx]=Object.assign({},CATS[idx],{name:name,sh:sh,c:modal.cat.c,d:modal.cat.d});}
    await saveCats();modal=null;render();toast(isNew?'Category created':'Category saved');
  });

  var recurChk=document.getElementById('recurChk');
  if(recurChk)recurChk.addEventListener('change',function(e){
    modal.recurOn=e.target.checked;
    var rf=document.getElementById('recurFields');if(rf)rf.style.display=e.target.checked?'grid':'none';
  });
  document.querySelectorAll('.cat-opt').forEach(function(o){
    o.addEventListener('click',function(){selCat=parseInt(o.dataset.catid);document.querySelectorAll('.cat-opt').forEach(function(x){x.classList.remove('on');});o.classList.add('on');});
  });
  var mCan=document.getElementById('mCan');if(mCan)mCan.addEventListener('click',function(){modal=null;render();});
  var mOv=document.getElementById('mOv');if(mOv)mOv.addEventListener('click',function(e){if(e.target.id==='mOv'){modal=null;render();}});
  var mSav=document.getElementById('mSav');
  if(mSav)mSav.addEventListener('click',async function(){
    var text=(document.getElementById('mT')||{}).value&&document.getElementById('mT').value.trim();if(!text)return;
    var desc=((document.getElementById('mD')||{}).value&&document.getElementById('mD').value.trim())||'';
    var key=modal.dateKey,catId=selCat||CATS[0].id;
    var recurOn=(document.getElementById('recurChk')||{}).checked;
    var every=Math.max(1,parseInt(((document.getElementById('mEvery')||{}).value)||1));
    var recur=recurOn?Math.max(2,parseInt(((document.getElementById('mRecur')||{}).value)||2)):1;
    if(modal.mode==='add'){
      var seriesId=recur>1?uid():null;
      for(var i=0;i<recur;i++){
        var d=addDays(key,i*every);if(!tasks[d])tasks[d]=[];
        if(tasks[d].length<20){var entry={id:uid(),text:text,cat:catId,done:false,desc:desc};if(seriesId){entry.recurId=seriesId;entry.recurEvery=every;}tasks[d].push(entry);}
      }
    } else {
      var scope=modal.scope||'this',orig=modal.task;
      if(scope==='this'||!isRecur(orig)){
        var t=tasks[key][modal.taskIdx];
        if(t){t.text=text;t.cat=catId;t.desc=desc;if(scope==='this'&&isRecur(orig))delete t.recurId;}
      } else {
        getFollowing(orig.recurId,key).forEach(function(item){var t=tasks[item.k][item.i];if(t){t.text=text;t.cat=catId;t.desc=desc;}});
      }
    }
    await saveT(tasks);modal=null;if(recur>1)toast('\u2736 '+recur+' recurring tasks added');render();
  });
  var mT=document.getElementById('mT');if(mT)mT.addEventListener('keydown',function(e){if(e.key==='Enter'&&!e.shiftKey){var s=document.getElementById('mSav');if(s)s.click();}});
  document.querySelectorAll('.add-cube').forEach(function(b){
    b.addEventListener('click',function(){modal={mode:'add',dateKey:b.dataset.key,recurOn:false};selCat=CATS[0].id;render();setTimeout(function(){var el=document.getElementById('mT');if(el)el.focus();},30);});
  });

  var aiI=document.getElementById('aiI');
  if(aiI){
    aiI.addEventListener('input',function(e){ai.inp=e.target.value;});
    aiI.addEventListener('keydown',function(e){if(e.key==='Enter'&&!ai.loading&&ai.inp.trim()){e.preventDefault();var s=document.getElementById('aiS');if(s)s.click();}});
  }
  var aiS=document.getElementById('aiS');if(aiS)aiS.addEventListener('click',function(){var v=ai.inp.trim();if(!v||ai.loading)return;parseAI(v);});
  var aiX=document.getElementById('aiX');if(aiX)aiX.addEventListener('click',function(){ai={inp:'',loading:false,prev:null};render();});
  var aiOk=document.getElementById('aiOk');
  if(aiOk)aiOk.addEventListener('click',async function(){
    var text=(document.getElementById('pText')||{}).value&&document.getElementById('pText').value.trim();
    var cat=parseInt(((document.getElementById('pCat')||{}).value)||CATS[0].id);
    var date=(document.getElementById('pDate')||{}).value;
    var recur=Math.max(1,parseInt(((document.getElementById('pRecur')||{}).value)||1));
    var every=Math.max(1,parseInt(((document.getElementById('pEvery')||{}).value)||1));
    if(!text||!date)return;
    var seriesId=recur>1?uid():null;var created=0;
    for(var i=0;i<recur;i++){var d=addDays(date,i*every);if(!tasks[d])tasks[d]=[];if(tasks[d].length<20){var entry={id:uid(),text:text,cat:cat,done:false,desc:''};if(seriesId){entry.recurId=seriesId;entry.recurEvery=every;}tasks[d].push(entry);created++;}}
    await saveT(tasks);ai={inp:'',loading:false,prev:null};anchor=new Date(date+'T12:00:00');view='week';searchActive=false;
    await saveS({anchor:anchor.toISOString(),view:view});toast('\u2736 '+created+' task'+(created!==1?'s':'')+' added'+(seriesId?' (recurring)':''));render();
  });

  var kbBtn=document.getElementById('kbBtn');
  if(kbBtn)kbBtn.addEventListener('click',function(){
    var ov=document.createElement('div');ov.id='kbOv';
    ov.style.cssText='position:fixed;inset:0;background:rgba(45,40,32,.45);z-index:500;display:flex;align-items:center;justify-content:center;backdrop-filter:blur(6px);';
    ov.innerHTML='<div style="background:var(--surface);border-radius:20px;padding:28px 32px;width:480px;max-width:94vw;max-height:88vh;overflow-y:auto;box-shadow:0 24px 64px rgba(60,40,20,.2);border:1.5px solid var(--border);position:relative;">'
      +'<button id="kbClose" style="position:absolute;top:14px;right:16px;background:var(--surface2);border:1.5px solid var(--border);border-radius:50%;width:28px;height:28px;font-size:.8rem;cursor:pointer;color:var(--muted);display:flex;align-items:center;justify-content:center;">\u2715</button>'
      +'<h2 style="font-size:1.1rem;font-weight:300;font-style:italic;letter-spacing:.03em;margin-bottom:18px;">keyboard shortcuts</h2>'
      +[['Selecting',''],['Click a task cube','Select that task'],['Click a day label','Anchor day for paste target'],['Shift + \u2193','Extend day selection downward'],['Copying & Pasting',''],['Ctrl + C','Copy selected task(s)'],['Ctrl + V','Paste into all selected days'],['General',''],['Escape','Clear selection / close modal'],['Backspace / Delete','Delete selected task(s)']].map(function(kv){
        return kv[1]===''
          ?'<div style="font-size:.52rem;font-weight:800;text-transform:uppercase;letter-spacing:.13em;color:var(--muted);margin:14px 0 6px;">'+kv[0]+'</div>'
          :'<div style="display:flex;align-items:center;justify-content:space-between;padding:7px 0;border-bottom:1px solid var(--border);"><span style="font-size:.72rem;font-weight:500;color:var(--muted);">'+kv[1]+'</span><kbd style="background:var(--surface2);border:1.5px solid var(--border);border-radius:6px;padding:3px 10px;font-family:monospace;font-size:.68rem;color:var(--text);white-space:nowrap;">'+kv[0]+'</kbd></div>';
      }).join('')+'</div>';
    document.body.appendChild(ov);
    document.getElementById('kbClose').addEventListener('click',function(){ov.remove();});
    ov.addEventListener('click',function(e){if(e.target===ov)ov.remove();});
  });

  var syncBtn=document.getElementById('syncBtn');
  if(syncBtn)syncBtn.addEventListener('click',openSyncSettings);
  updateSyncBadge();
  document.removeEventListener('keydown',gKey);
  document.addEventListener('keydown',gKey);
}

function gKey(e){
  var tag=document.activeElement&&document.activeElement.tagName,inInput=tag==='INPUT'||tag==='TEXTAREA'||tag==='SELECT';
  if(inInput)return;
  if((e.metaKey||e.ctrlKey)&&e.key==='c'){e.preventDefault();if(selTasks.size>0)copySelected();return;}
  if((e.metaKey||e.ctrlKey)&&e.key==='v'){e.preventDefault();if(clipboard.length&&selDays.size>0)pasteToDays();else if(clipboard.length)toast('Click a day label first, then Ctrl+V');return;}
  if(e.shiftKey&&e.key==='ArrowDown'){
    e.preventDefault();
    var wd=weekDates(anchor),keys=wd.map(function(d){return dk(d);});
    if(!lastClickedDay&&selDays.size>0)lastClickedDay=Array.from(selDays)[0];
    if(!lastClickedDay)return;
    var anchorIdx=keys.indexOf(lastClickedDay);if(anchorIdx===-1)return;
    var furthest=anchorIdx;keys.forEach(function(k,i){if(i>=anchorIdx&&selDays.has(k))furthest=i;});
    var next=furthest+1;if(next<keys.length){selDays.add(keys[next]);render();}
    return;
  }
  if(e.key==='Escape'){
    if(modal){modal=null;render();return;}
    if(selTasks.size>0||selDays.size>0){selTasks.clear();selDays.clear();lastClickedDay=null;render();return;}
    if(searchActive){searchActive=false;render();return;}
    if(searchQ){searchQ='';render();}
    return;
  }
  if((e.key==='Delete'||e.key==='Backspace')&&selTasks.size>0&&!modal){e.preventDefault();deleteSelected();}
}

(async function(){
  try{tasks=await loadT();}catch(e){tasks={};}
  try{var s=await loadS();if(s){if(s.anchor){var a=new Date(s.anchor);anchor=isNaN(a)?new Date():a;}if(s.view)view=s.view;}}catch(e){}
  try{var sc=await loadCats();if(sc&&sc.length)CATS=sc;}catch(e){}
  selCat=CATS[0]?CATS[0].id:1;
  // Try loading from Gist (overwrites local if available)
  try{
    var gdata=await gistLoad();
    if(gdata){
      if(gdata.tasks)tasks=gdata.tasks;
      if(gdata.cats&&gdata.cats.length)CATS=gdata.cats;
      if(gdata.anchor){var ga=new Date(gdata.anchor);if(!isNaN(ga))anchor=ga;}
      if(gdata.view)view=gdata.view;
      // mirror to localStorage
      localStorage.setItem('jas_t7',JSON.stringify(tasks));
      localStorage.setItem('jas_cats',JSON.stringify(CATS));
      localStorage.setItem('jas_s7',JSON.stringify({anchor:anchor.toISOString(),view:view}));
    }
  }catch(e){}
  selCat=CATS[0]?CATS[0].id:1;
  render();
  if(view==='month')scrollToToday();
})();
</script>
</body>
</html>
