<!DOCTYPE html>
<html lang="km">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no, viewport-fit=cover">
<title>ក្តារលទ្ធផលផ្ទាល់</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Kantumruy+Pro:wght@400;600;700&family=Noto+Sans+Khmer:wght@400;500;600;700&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
<style>
  :root{
    --bg:#14161B;
    --panel:#1C1F27;
    --panel-line:#2A2E38;
    --blue:#2E6BE0;
    --red:#E4484B;
    --text:#F2F3F5;
    --text-muted:#8890A0;
    --green:#3BC17A;
  }
  *{box-sizing:border-box; -webkit-tap-highlight-color:transparent;}
  html,body{
    margin:0; padding:0; min-height:100%;
    background:var(--bg); color:var(--text);
    font-family:'Noto Sans Khmer','Kantumruy Pro',sans-serif;
    overscroll-behavior:none;
  }
  #app{
    max-width:520px; margin:0 auto;
    min-height:100dvh;
    padding: max(16px, env(safe-area-inset-top)) 16px max(28px, env(safe-area-inset-bottom));
    display:flex; flex-direction:column; gap:14px;
  }
  header{ text-align:center; padding-top:4px; }
  header .eyebrow{
    font-family:'Space Mono', monospace;
    font-size:11px; letter-spacing:.18em; text-transform:uppercase;
    color:var(--text-muted); margin:0 0 4px;
    display:flex; align-items:center; justify-content:center; gap:6px;
  }
  .live-dot{
    width:7px; height:7px; border-radius:50%; background:var(--green);
    box-shadow:0 0 0 0 rgba(59,193,122,.6);
    animation: pulse 1.8s infinite;
  }
  @keyframes pulse{
    0%{ box-shadow:0 0 0 0 rgba(59,193,122,.55); }
    70%{ box-shadow:0 0 0 7px rgba(59,193,122,0); }
    100%{ box-shadow:0 0 0 0 rgba(59,193,122,0); }
  }
  header h1{
    font-family:'Kantumruy Pro', sans-serif;
    font-weight:700; font-size:20px; margin:0; letter-spacing:.01em;
  }

  /* ---- live board ---- */
  .board{
    background:var(--panel); border:1.5px solid var(--panel-line); border-radius:18px;
    padding:16px;
  }
  .board-top{
    display:flex; justify-content:space-between; align-items:baseline; margin-bottom:10px;
  }
  .board-top .title{
    font-family:'Space Mono', monospace; font-size:11px; letter-spacing:.14em;
    text-transform:uppercase; color:var(--text-muted);
  }
  .board-top .respondents{
    font-family:'Space Mono', monospace; font-size:12px; color:var(--text-muted);
  }
  .board-top .respondents b{ color:var(--text); font-size:14px; }

  .meter{
    height:14px; border-radius:8px; overflow:hidden; display:flex;
    background:var(--panel-line); margin-bottom:12px;
  }
  .meter .seg-o{ background:var(--blue); height:100%; transition:width .4s ease; }
  .meter .seg-x{ background:var(--red); height:100%; transition:width .4s ease; }

  .stat-nums{ display:flex; justify-content:space-between; font-family:'Space Mono', monospace; }
  .stat-nums .cell{ text-align:center; flex:1; }
  .stat-nums .cell .n{ font-size:26px; font-weight:700; line-height:1.1; }
  .stat-nums .cell.o .n{ color:var(--blue); }
  .stat-nums .cell.x .n{ color:var(--red); }
  .stat-nums .cell.t .n{ color:var(--text); }
  .stat-nums .cell .l{ font-size:10px; color:var(--text-muted); margin-top:2px; letter-spacing:.04em; }

  /* ---- vote section ---- */
  .vote-section{
    display:flex; flex-direction:column; gap:10px;
  }
  .verdict-btn{
    border:none; border-radius:18px;
    display:flex; align-items:center; gap:14px; padding:16px 18px;
    cursor:pointer; -webkit-user-select:none; user-select:none;
    background:var(--panel); border:1.5px solid var(--panel-line);
    transition: transform .12s ease, opacity .2s ease;
  }
  .verdict-btn:active{ transform:scale(.98); }
  .verdict-btn:disabled{ opacity:.35; pointer-events:none; }
  .verdict-btn .glyph{ width:44px; height:44px; flex-shrink:0; }
  .verdict-btn .label{ display:flex; flex-direction:column; gap:2px; text-align:left; }
  .verdict-btn .label .primary{ font-family:'Kantumruy Pro'; font-weight:700; font-size:17px; }
  .verdict-btn .label .secondary{ font-family:'Space Mono', monospace; font-size:11px; color:var(--text-muted); }
  #btn-o .primary{ color:var(--blue); }
  #btn-x .primary{ color:var(--red); }
  svg.glyph circle, svg.glyph line{ fill:none; stroke-linecap:round; }

  .voted-banner{
    display:none; align-items:center; justify-content:center; gap:8px;
    padding:14px; border-radius:18px; background:var(--panel); border:1.5px solid var(--panel-line);
    font-family:'Space Mono', monospace; font-size:13px; color:var(--text-muted);
  }
  .voted-banner b{ color:var(--text); }

  /* ---- share ---- */
  .share-box{
    background:var(--panel); border:1.5px solid var(--panel-line); border-radius:18px;
    padding:16px; display:flex; flex-direction:column; align-items:center; gap:12px;
  }
  .share-box .title{
    font-family:'Space Mono', monospace; font-size:11px; letter-spacing:.14em;
    text-transform:uppercase; color:var(--text-muted); align-self:flex-start;
  }
  #qr{ background:#fff; padding:10px; border-radius:12px; line-height:0; }
  .link-row{
    display:flex; gap:8px; width:100%;
  }
  .link-row input{
    flex:1; min-width:0; background:var(--bg); border:1.5px solid var(--panel-line);
    color:var(--text-muted); border-radius:10px; padding:10px 12px;
    font-family:'Space Mono', monospace; font-size:11px;
  }
  .link-row button{
    flex-shrink:0; background:var(--blue); color:#fff; border:none; border-radius:10px;
    padding:0 16px; font-family:'Noto Sans Khmer'; font-weight:600; font-size:13px; cursor:pointer;
  }
  .link-row button:active{ opacity:.8; }

  footer{
    text-align:center; margin-top:auto;
  }
  footer .reset{
    font-family:'Space Mono', monospace; font-size:11px; letter-spacing:.05em;
    background:none; border:none; color:var(--text-muted);
    text-decoration:underline; text-underline-offset:3px; cursor:pointer; padding:6px;
  }
</style>
</head>
<body>
<div id="app">
  <header>
    <p class="eyebrow"><span class="live-dot"></span> ស្ថិតិផ្ទាល់</p>
    <h1>ក្តារលទ្ធផលរួម</h1>
  </header>

  <div class="board">
    <div class="board-top">
      <span class="title">លទ្ធផលសរុប</span>
      <span class="respondents"><b id="resp-count">0</b> អ្នកឆ្លើយ</span>
    </div>
    <div class="meter">
      <div class="seg-o" id="seg-o" style="width:0%"></div>
      <div class="seg-x" id="seg-x" style="width:0%"></div>
    </div>
    <div class="stat-nums">
      <div class="cell o">
        <div class="n" id="count-o">0</div>
        <div class="l">O (<span id="pct-o">0</span>%)</div>
      </div>
      <div class="cell t">
        <div class="n" id="count-total">0</div>
        <div class="l">សរុប</div>
      </div>
      <div class="cell x">
        <div class="n" id="count-x">0</div>
        <div class="l">X (<span id="pct-x">0</span>%)</div>
      </div>
    </div>
  </div>

  <div class="vote-section" id="vote-section">
    <button class="verdict-btn" id="btn-o">
      <svg class="glyph" viewBox="0 0 100 100"><circle cx="50" cy="50" r="38" stroke="#2E6BE0" stroke-width="12"/></svg>
      <span class="label">
        <span class="primary">ត្រឹមត្រូវ / យល់ព្រម</span>
        <span class="secondary">ចុចដើម្បីបញ្ជូនចម្លើយរបស់អ្នក</span>
      </span>
    </button>
    <button class="verdict-btn" id="btn-x">
      <svg class="glyph" viewBox="0 0 100 100">
        <line x1="20" y1="20" x2="80" y2="80" stroke="#E4484B" stroke-width="12"/>
        <line x1="80" y1="20" x2="20" y2="80" stroke="#E4484B" stroke-width="12"/>
      </svg>
      <span class="label">
        <span class="primary">មិនត្រឹមត្រូវ / បដិសេធ</span>
        <span class="secondary">ចុចដើម្បីបញ្ជូនចម្លើយរបស់អ្នក</span>
      </span>
    </button>
  </div>

  <div class="voted-banner" id="voted-banner">
    អ្នកបានឆ្លើយរួចហើយ៖ <b id="my-vote"></b> — លទ្ធផលកំពុងធ្វើសមកាលកម្មផ្ទាល់
  </div>

  <div class="share-box">
    <span class="title">ចែករំលែកទៅអ្នកឆ្លើយផ្សេងទៀត</span>
    <div id="qr"></div>
    <div class="link-row">
      <input type="text" id="link-input" readonly>
      <button id="copy-btn">ចម្លង</button>
    </div>
  </div>

  <footer>
    <button class="reset" id="reset-btn">សម្អាតលទ្ធផលទាំងអស់ (សម្រាប់អ្នករៀបចំ)</button>
  </footer>
</div>

<script>
(function(){
  var BOARD_KEY = 'board:votes';
  var respondentId = (crypto && crypto.randomUUID) ? crypto.randomUUID() : String(Date.now())+Math.random();
  var myVote = null;
  var pollTimer = null;

  // --- share link + QR ---
  var link = window.location.href;
  document.getElementById('link-input').value = link;
  try{
    new QRCode(document.getElementById('qr'), {
      text: link, width: 148, height: 148,
      colorDark: '#14161B', colorLight: '#ffffff'
    });
  }catch(e){ document.getElementById('qr').textContent = 'QR មិនអាចបង្កើតបានទេ'; }

  document.getElementById('copy-btn').addEventListener('click', function(){
    var input = document.getElementById('link-input');
    input.select(); input.setSelectionRange(0, 99999);
    if(navigator.clipboard){
      navigator.clipboard.writeText(link).then(function(){
        var btn = document.getElementById('copy-btn');
        var prev = btn.textContent; btn.textContent = 'បានចម្លង!';
        setTimeout(function(){ btn.textContent = prev; }, 1400);
      }).catch(function(){ document.execCommand('copy'); });
    } else {
      document.execCommand('copy');
    }
  });

  // --- storage helpers ---
  async function readBoard(){
    try{
      var res = await window.storage.get(BOARD_KEY, true);
      if(!res) return {};
      return JSON.parse(res.value || '{}');
    }catch(e){
      return {};
    }
  }

  function render(votes){
    var o = 0, x = 0;
    Object.keys(votes).forEach(function(k){
      if(votes[k] === 'o') o++;
      else if(votes[k] === 'x') x++;
    });
    var total = o + x;
    var pctO = total ? Math.round((o/total)*100) : 0;
    var pctX = total ? 100 - pctO : 0;
    document.getElementById('count-o').textContent = o;
    document.getElementById('count-x').textContent = x;
    document.getElementById('count-total').textContent = total;
    document.getElementById('pct-o').textContent = pctO;
    document.getElementById('pct-x').textContent = pctX;
    document.getElementById('seg-o').style.width = pctO + '%';
    document.getElementById('seg-x').style.width = pctX + '%';
    document.getElementById('resp-count').textContent = total;
  }

  async function refresh(){
    var votes = await readBoard();
    render(votes);
    if(votes[respondentId]) applyVotedState(votes[respondentId]);
  }

  function applyVotedState(kind){
    myVote = kind;
    document.getElementById('vote-section').style.display = 'none';
    document.getElementById('voted-banner').style.display = 'flex';
    document.getElementById('my-vote').textContent = kind === 'o' ? 'ត្រឹមត្រូវ / យល់ព្រម (O)' : 'មិនត្រឹមត្រូវ / បដិសេធ (X)';
  }

  async function submitVote(kind){
    if(myVote) return;
    var btnO = document.getElementById('btn-o');
    var btnX = document.getElementById('btn-x');
    btnO.disabled = true; btnX.disabled = true;
    try{
      var votes = await readBoard();
      votes[respondentId] = kind;
      await window.storage.set(BOARD_KEY, JSON.stringify(votes), true);
      applyVotedState(kind);
      render(votes);
    }catch(e){
      btnO.disabled = false; btnX.disabled = false;
      alert('មិនអាចបញ្ជូនចម្លើយបានទេ សូមព្យាយាមម្តងទៀត');
    }
  }

  document.getElementById('btn-o').addEventListener('click', function(){ submitVote('o'); });
  document.getElementById('btn-x').addEventListener('click', function(){ submitVote('x'); });

  document.getElementById('reset-btn').addEventListener('click', async function(){
    if(!confirm('លុបលទ្ធផលទាំងអស់របស់អ្នកឆ្លើយទាំងអស់មែនទេ?')) return;
    try{
      await window.storage.set(BOARD_KEY, JSON.stringify({}), true);
      myVote = null;
      document.getElementById('vote-section').style.display = 'flex';
      document.getElementById('voted-banner').style.display = 'none';
      document.getElementById('btn-o').disabled = false;
      document.getElementById('btn-x').disabled = false;
      refresh();
    }catch(e){
      alert('មិនអាចសម្អាតបានទេ');
    }
  });

  refresh();
  pollTimer = setInterval(refresh, 2000);
})();
</script>
</body>
</html>
