<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Daily Goals</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Orbitron:wght@400;700;900&family=Share+Tech+Mono&display=swap" rel="stylesheet">
<style>
  :root {
    --black:#0a0a0a; --deep:#111111; --card:#161616; --border:#1f1f1f;
    --orange:#ff6a00; --orange-hot:#ff8c00; --orange-glow:#ffaa00; --orange-dim:#c24e00;
    --text:#ff6a00; --text-dim:#a04400; --text-muted:#5a3000;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  body{background:var(--black);color:var(--text);font-family:'Share Tech Mono',monospace;min-height:100vh;overflow-x:hidden;font-weight:700;-webkit-font-smoothing:antialiased;}
  body::before{content:'';position:fixed;inset:0;background:repeating-linear-gradient(0deg,transparent,transparent 2px,rgba(255,106,0,0.013) 2px,rgba(255,106,0,0.013) 4px);pointer-events:none;z-index:0;}

  /* HEADER */
  header{position:relative;text-align:center;padding:34px 20px 22px;border-bottom:1px solid var(--border);background:linear-gradient(180deg,#1a0800 0%,transparent 100%);}
  header::after{content:'';position:absolute;bottom:-1px;left:50%;transform:translateX(-50%);width:200px;height:2px;background:linear-gradient(90deg,transparent,var(--orange),transparent);}
  .logo{font-family:'Bebas Neue',sans-serif;font-size:clamp(30px,7vw,66px);letter-spacing:0.12em;color:var(--orange-hot);text-shadow:0 0 30px rgba(255,106,0,0.5),0 0 80px rgba(255,106,0,0.2);line-height:1;}
  .logo span{color:var(--orange-glow);}
  .tagline{font-family:'Orbitron',sans-serif;font-size:10px;letter-spacing:0.4em;color:var(--text-dim);margin-top:6px;font-weight:900;}
  .date-bar{display:flex;justify-content:center;align-items:center;gap:18px;padding:12px 20px;border-bottom:1px solid var(--border);font-family:'Orbitron',sans-serif;font-size:11px;letter-spacing:0.15em;color:var(--text-dim);font-weight:700;}
  #live-time{color:var(--orange);font-size:14px;font-weight:700;}

  /* TABS */
  .nav-tabs{display:flex;border-bottom:1px solid var(--border);background:var(--deep);position:relative;z-index:1;}
  .nav-tab{padding:13px 26px;cursor:pointer;font-family:'Orbitron',sans-serif;font-size:10px;font-weight:700;letter-spacing:0.2em;color:var(--text-muted);border-bottom:2px solid transparent;transition:all 0.2s;user-select:none;}
  .nav-tab:hover{color:var(--text-dim);}
  .nav-tab.active{color:var(--orange);border-bottom-color:var(--orange);}

  /* PAGES */
  .page{display:none;} .page.active{display:block;}
  .container{max-width:1200px;margin:0 auto;padding:26px 20px;position:relative;z-index:1;}

  .section-title{font-family:'Orbitron',sans-serif;font-size:10px;letter-spacing:0.3em;color:var(--text-muted);text-transform:uppercase;margin-bottom:13px;display:flex;align-items:center;gap:12px;}
  .section-title::after{content:'';flex:1;height:1px;background:var(--border);}

  /* MAIN GRID */
  .main-grid{display:grid;grid-template-columns:1fr 300px;gap:20px;align-items:start;}
  @media(max-width:768px){.main-grid{grid-template-columns:1fr;}}

  /* PANELS */
  .panel{background:var(--card);border:1px solid var(--border);border-radius:4px;overflow:hidden;}
  .panel-header{padding:12px 18px;border-bottom:1px solid var(--border);background:rgba(255,106,0,0.04);display:flex;align-items:center;justify-content:space-between;}
  .panel-header-title{font-family:'Orbitron',sans-serif;font-size:12px;font-weight:700;letter-spacing:0.1em;color:var(--orange);}

  /* GOAL ITEMS */
  .goal-category{padding:16px 16px 4px;}
  .cat-label{font-family:'Orbitron',sans-serif;font-size:9px;letter-spacing:0.35em;color:var(--text-muted);margin-bottom:9px;}
  .goals-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:4px;}
  .goal-item input[type="checkbox"]{display:none;}
  .goal-label{display:flex;align-items:center;gap:9px;padding:11px 13px;background:var(--deep);border:1px solid var(--border);border-radius:3px;cursor:pointer;transition:all 0.2s;user-select:none;}
  .goal-label:hover{border-color:var(--orange-dim);background:rgba(255,106,0,0.05);}
  .goal-item input:checked+.goal-label{border-color:var(--orange);background:rgba(255,106,0,0.1);box-shadow:0 0 10px rgba(255,106,0,0.15),inset 0 0 20px rgba(255,106,0,0.04);}
  .check-box{width:16px;height:16px;border:1.5px solid var(--border);border-radius:2px;flex-shrink:0;display:flex;align-items:center;justify-content:center;transition:all 0.2s;}
  .goal-item input:checked+.goal-label .check-box{border-color:var(--orange);background:var(--orange);}
  .check-box::after{content:'';width:9px;height:5px;border-left:2px solid #000;border-bottom:2px solid #000;transform:rotate(-45deg) translateY(-1px);opacity:0;transition:opacity 0.15s;}
  .goal-item input:checked+.goal-label .check-box::after{opacity:1;}
  .goal-icon{font-size:15px;flex-shrink:0;}
  .goal-text{font-size:10px;line-height:1.4;color:var(--text-dim);letter-spacing:0.04em;transition:color 0.2s;font-weight:700;}
  .goal-item input:checked+.goal-label .goal-text{color:var(--orange-hot);}
  .goal-pts{margin-left:auto;font-family:'Orbitron',sans-serif;font-size:9px;color:var(--text-muted);flex-shrink:0;font-weight:900;}
  .goal-item input:checked+.goal-label .goal-pts{color:var(--orange-dim);}
  .cat-divider{height:1px;background:var(--border);margin:2px 16px;}

  /* PROGRESS */
  .progress-section{padding:16px;border-top:1px solid var(--border);}
  .progress-row{display:flex;justify-content:space-between;align-items:baseline;margin-bottom:10px;}
  .progress-label{font-family:'Orbitron',sans-serif;font-size:10px;letter-spacing:0.15em;color:var(--text-dim);}
  .progress-value{font-family:'Bebas Neue',sans-serif;font-size:46px;line-height:1;color:var(--orange);text-shadow:0 0 20px rgba(255,106,0,0.4);transition:all 0.3s;}
  .progress-value.winner{color:var(--orange-glow);text-shadow:0 0 40px rgba(255,170,0,0.8),0 0 80px rgba(255,106,0,0.4);animation:pulse-glow 1.5s ease-in-out infinite;}
  @keyframes pulse-glow{0%,100%{text-shadow:0 0 40px rgba(255,170,0,0.8),0 0 80px rgba(255,106,0,0.4);}50%{text-shadow:0 0 60px rgba(255,170,0,1),0 0 120px rgba(255,106,0,0.6);}}
  .progress-bar-track{height:5px;background:var(--border);border-radius:3px;overflow:hidden;margin-bottom:12px;}
  .progress-bar-fill{height:100%;border-radius:3px;background:linear-gradient(90deg,var(--orange-dim),var(--orange-hot));transition:width 0.5s cubic-bezier(0.4,0,0.2,1);box-shadow:0 0 8px rgba(255,106,0,0.5);width:0%;}
  .winner-banner{display:none;text-align:center;padding:13px;background:linear-gradient(135deg,rgba(255,106,0,0.15),rgba(255,170,0,0.1));border:1px solid var(--orange);border-radius:3px;margin-top:8px;animation:banner-in 0.4s ease;}
  @keyframes banner-in{from{transform:scale(0.95);opacity:0;}to{transform:scale(1);opacity:1;}}
  .winner-banner.show{display:block;}
  .winner-text{font-family:'Bebas Neue',sans-serif;font-size:22px;letter-spacing:0.15em;color:var(--orange-glow);text-shadow:0 0 20px rgba(255,170,0,0.6);}
  .winner-sub{font-size:9px;color:var(--text-dim);letter-spacing:0.2em;margin-top:4px;font-weight:700;}
  .save-btn{width:100%;padding:12px;background:transparent;border:1px solid var(--orange);color:var(--orange);font-family:'Orbitron',sans-serif;font-size:11px;font-weight:700;letter-spacing:0.25em;cursor:pointer;border-radius:2px;transition:all 0.2s;margin-top:12px;}
  .save-btn:hover{background:var(--orange);color:#000;box-shadow:0 0 20px rgba(255,106,0,0.4);}

  /* RIGHT PANEL */
  .right-panel{display:flex;flex-direction:column;gap:16px;}
  .stats-grid{display:grid;grid-template-columns:1fr 1fr;gap:1px;background:var(--border);}
  .stat-cell{background:var(--card);padding:13px;text-align:center;}
  .stat-num{font-family:'Bebas Neue',sans-serif;font-size:30px;color:var(--orange);line-height:1;}
  .stat-label{font-size:8px;color:var(--text-muted);letter-spacing:0.15em;margin-top:3px;text-transform:uppercase;font-weight:900;}
  .records-list{max-height:360px;overflow-y:auto;}
  .records-list::-webkit-scrollbar{width:3px;}
  .records-list::-webkit-scrollbar-track{background:var(--deep);}
  .records-list::-webkit-scrollbar-thumb{background:var(--orange-dim);border-radius:2px;}
  .record-item{padding:11px 15px;border-bottom:1px solid var(--border);transition:background 0.15s;}
  .record-item:last-child{border-bottom:none;}
  .record-item:hover{background:rgba(255,106,0,0.04);}
  .record-top{display:flex;justify-content:space-between;align-items:center;margin-bottom:5px;}
  .record-date{font-family:'Orbitron',sans-serif;font-size:9px;color:var(--text-dim);letter-spacing:0.08em;font-weight:700;}
  .record-pct{font-family:'Bebas Neue',sans-serif;font-size:20px;color:var(--orange);line-height:1;}
  .record-pct.perfect{color:var(--orange-glow);}
  .record-bar-track{height:3px;background:var(--border);border-radius:2px;overflow:hidden;}
  .record-bar-fill{height:100%;border-radius:2px;background:linear-gradient(90deg,var(--orange-dim),var(--orange-hot));}
  .record-goals{display:flex;flex-wrap:wrap;gap:3px;margin-top:6px;}
  .goal-tag{font-size:8px;padding:2px 5px;border:1px solid var(--border);border-radius:2px;color:var(--text-muted);font-weight:700;}
  .goal-tag.done{border-color:var(--orange-dim);color:var(--orange-dim);}
  .no-records{padding:24px 20px;text-align:center;font-size:10px;color:var(--text-muted);letter-spacing:0.1em;font-weight:700;}

  /* ====== MONTHLY DASHBOARD ====== */
  .monthly-container{max-width:1200px;margin:0 auto;padding:26px 20px;position:relative;z-index:1;}

  /* Month nav */
  .month-nav{display:flex;align-items:center;justify-content:center;gap:18px;margin-bottom:26px;}
  .month-arrow{background:none;border:1px solid var(--border);color:var(--orange);font-size:18px;width:36px;height:36px;cursor:pointer;border-radius:3px;display:flex;align-items:center;justify-content:center;transition:all 0.2s;}
  .month-arrow:hover{border-color:var(--orange);background:rgba(255,106,0,0.1);}
  .month-label{font-family:'Bebas Neue',sans-serif;font-size:34px;letter-spacing:0.12em;color:var(--orange-hot);text-shadow:0 0 20px rgba(255,106,0,0.3);min-width:280px;text-align:center;}

  /* Monthly stat cards */
  .monthly-stats-row{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:26px;}
  @media(max-width:600px){.monthly-stats-row{grid-template-columns:1fr 1fr;}}
  .m-stat{background:var(--card);border:1px solid var(--border);border-radius:4px;padding:18px 16px;text-align:center;}
  .m-stat-num{font-family:'Bebas Neue',sans-serif;font-size:38px;color:var(--orange);line-height:1;}
  .m-stat-label{font-size:9px;color:var(--text-muted);letter-spacing:0.15em;margin-top:4px;text-transform:uppercase;font-weight:900;}

  /* Trend chart */
  .trend-wrap{background:var(--card);border:1px solid var(--border);border-radius:4px;overflow:hidden;margin-bottom:22px;}
  .trend-body{padding:16px 18px;}
  .trend-chart{display:flex;align-items:flex-end;gap:4px;height:80px;}
  .trend-bar-col{display:flex;flex-direction:column;align-items:center;flex:1;gap:4px;min-width:0;}
  .trend-bar{width:100%;border-radius:2px 2px 0 0;background:linear-gradient(180deg,var(--orange-hot),var(--orange-dim));transition:height 0.4s ease;min-height:2px;box-shadow:0 0 4px rgba(255,106,0,0.3);}
  .trend-bar.perfect{background:linear-gradient(180deg,var(--orange-glow),var(--orange));}
  .trend-bar.nodata{background:var(--border);box-shadow:none;}
  .trend-day{font-size:7px;color:var(--text-muted);font-family:'Orbitron',sans-serif;font-weight:700;}

  /* Calendar */
  .calendar-wrap{background:var(--card);border:1px solid var(--border);border-radius:4px;overflow:hidden;margin-bottom:22px;}
  .cal-body{padding:16px 18px;}
  .cal-weekdays{display:grid;grid-template-columns:repeat(7,1fr);gap:5px;margin-bottom:7px;}
  .cal-day-name{text-align:center;font-family:'Orbitron',sans-serif;font-size:8px;letter-spacing:0.1em;color:var(--text-muted);padding:4px 0;}
  .cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:5px;}
  .cal-cell{aspect-ratio:1;border-radius:3px;background:var(--deep);border:1px solid var(--border);display:flex;flex-direction:column;align-items:center;justify-content:center;cursor:default;transition:all 0.15s;position:relative;}
  .cal-cell.has-data{cursor:pointer;}
  .cal-cell.has-data:hover{border-color:var(--orange);transform:scale(1.08);z-index:2;box-shadow:0 0 12px rgba(255,106,0,0.3);}
  .cal-cell.empty{background:transparent;border-color:transparent;}
  .cal-cell.today{border-color:var(--orange-dim);}
  .cal-day-num{font-family:'Orbitron',sans-serif;font-size:8px;color:var(--text-muted);line-height:1;font-weight:900;}
  .cal-pct{font-family:'Bebas Neue',sans-serif;font-size:12px;line-height:1;margin-top:2px;}
  /* Heat map colors */
  .heat-0{background:var(--deep);}
  .heat-1{background:#1c0900;}
  .heat-2{background:#2e1200;}
  .heat-3{background:#421a00;}
  .heat-4{background:#5e2500;}
  .heat-5{background:#7e3200;}
  .heat-6{background:#a54200;}
  .heat-perfect{background:rgba(255,106,0,0.22);border-color:var(--orange)!important;}

  /* Goal breakdown */
  .goal-breakdown-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:22px;}
  @media(max-width:600px){.goal-breakdown-grid{grid-template-columns:1fr;}}
  .goal-break-item{background:var(--card);border:1px solid var(--border);border-radius:4px;padding:13px 15px;}
  .gb-top{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px;}
  .gb-name{font-size:11px;color:var(--text-dim);letter-spacing:0.04em;display:flex;align-items:center;gap:7px;font-weight:700;}
  .gb-count{font-family:'Bebas Neue',sans-serif;font-size:24px;color:var(--orange);}
  .gb-bar-track{height:4px;background:var(--border);border-radius:2px;overflow:hidden;}
  .gb-bar-fill{height:100%;border-radius:2px;background:linear-gradient(90deg,var(--orange-dim),var(--orange-hot));transition:width 0.6s;}
  .gb-label{font-size:9px;color:var(--text-muted);margin-top:5px;letter-spacing:0.06em;font-weight:700;}

  /* Weekly summary table */
  .week-table-wrap{background:var(--card);border:1px solid var(--border);border-radius:4px;overflow:hidden;margin-bottom:22px;}
  .week-table{width:100%;border-collapse:collapse;}
  .week-table th{padding:10px 14px;font-family:'Orbitron',sans-serif;font-size:9px;letter-spacing:0.12em;color:var(--text-muted);border-bottom:1px solid var(--border);text-align:left;background:rgba(255,106,0,0.03);font-weight:900;}
  .week-table td{padding:10px 14px;font-size:10px;color:var(--text-dim);border-bottom:1px solid var(--border);font-weight:700;}
  .week-table tr:last-child td{border-bottom:none;}
  .week-table tr:hover td{background:rgba(255,106,0,0.03);}
  .week-pct{font-family:'Bebas Neue',sans-serif;font-size:20px;color:var(--orange);}
  .week-pct.perfect{color:var(--orange-glow);}
  .week-mini-bar{height:3px;background:var(--border);border-radius:2px;overflow:hidden;margin-top:4px;width:100px;}
  .week-mini-fill{height:100%;border-radius:2px;background:linear-gradient(90deg,var(--orange-dim),var(--orange-hot));}

  /* Tooltip */
  .cal-tooltip{position:fixed;background:#1a0800;border:1px solid var(--orange);padding:10px 14px;border-radius:4px;pointer-events:none;z-index:999;font-size:10px;color:var(--text-dim);min-width:165px;display:none;font-weight:700;}
  .cal-tooltip.show{display:block;}
  .tt-date{font-family:'Orbitron',sans-serif;font-size:10px;color:var(--orange);margin-bottom:5px;font-weight:900;}
  .tt-pct{font-family:'Bebas Neue',sans-serif;font-size:26px;color:var(--orange-hot);line-height:1;margin-bottom:6px;}
  .tt-goal{display:flex;align-items:center;gap:6px;margin-bottom:3px;font-size:9px;}
  .tt-dot{width:6px;height:6px;border-radius:50%;flex-shrink:0;}
  .tt-dot.done{background:var(--orange);}
  .tt-dot.miss{background:var(--border);}

  /* Sparkles */
  .sparkle{position:fixed;pointer-events:none;font-size:20px;animation:sparkle-float 2s ease forwards;z-index:999;}
  @keyframes sparkle-float{0%{opacity:1;transform:translateY(0) rotate(0deg);}100%{opacity:0;transform:translateY(-150px) rotate(360deg);}}
</style>
</head>
<body>

<header>
  <div class="logo">My <span>Daily</span> Goals</div>
  <div class="tagline">Track &bull; Achieve &bull; Conquer</div>
</header>
<div class="date-bar">
  <span id="live-date"></span> &mdash; <span id="live-time"></span>
</div>
<div class="nav-tabs">
  <div class="nav-tab active" onclick="switchTab('daily')">⬡ Daily Tracker</div>
  <div class="nav-tab" onclick="switchTab('monthly')">◈ Monthly Dashboard</div>
</div>

<!-- ===== DAILY PAGE ===== -->
<div class="page active" id="page-daily">
  <div class="container">
    <div class="main-grid">
      <div>
        <div class="section-title">Today's Mission</div>
        <div class="panel">
          <div class="panel-header">
            <span class="panel-header-title">Daily Checklist</span>
            <span style="font-size:10px;color:var(--text-dim)" id="panel-date"></span>
          </div>
          <div class="goal-category">
            <div class="cat-label">💊 Medicine</div>
            <div class="goals-grid">
              <div class="goal-item"><input type="checkbox" id="g1"><label class="goal-label" for="g1"><span class="check-box"></span><span class="goal-icon">🌅</span><span class="goal-text">Morning<br>Medicine</span><span class="goal-pts">13%</span></label></div>
              <div class="goal-item"><input type="checkbox" id="g2"><label class="goal-label" for="g2"><span class="check-box"></span><span class="goal-icon">☀️</span><span class="goal-text">Afternoon<br>Medicine</span><span class="goal-pts">12%</span></label></div>
              <div class="goal-item" style="grid-column:span 2"><input type="checkbox" id="g3"><label class="goal-label" for="g3"><span class="check-box"></span><span class="goal-icon">🌙</span><span class="goal-text">Night Medicine</span><span class="goal-pts">13%</span></label></div>
            </div>
          </div>
          <div class="cat-divider"></div>
          <div class="goal-category">
            <div class="cat-label">🏋️ Fitness</div>
            <div class="goals-grid">
              <div class="goal-item"><input type="checkbox" id="g4"><label class="goal-label" for="g4"><span class="check-box"></span><span class="goal-icon">🏋️</span><span class="goal-text">Weight<br>Training</span><span class="goal-pts">13%</span></label></div>
              <div class="goal-item"><input type="checkbox" id="g5"><label class="goal-label" for="g5"><span class="check-box"></span><span class="goal-icon">🏃</span><span class="goal-text">Cardio</span><span class="goal-pts">12%</span></label></div>
            </div>
          </div>
          <div class="cat-divider"></div>
          <div class="goal-category">
            <div class="cat-label">🌿 Lifestyle</div>
            <div class="goals-grid">
              <div class="goal-item"><input type="checkbox" id="g6"><label class="goal-label" for="g6"><span class="check-box"></span><span class="goal-icon">😴</span><span class="goal-text">Proper<br>Sleep</span><span class="goal-pts">13%</span></label></div>
              <div class="goal-item"><input type="checkbox" id="g7"><label class="goal-label" for="g7"><span class="check-box"></span><span class="goal-icon">🥗</span><span class="goal-text">No<br>Junk Food</span><span class="goal-pts">12%</span></label></div>
              <div class="goal-item" style="grid-column:span 2"><input type="checkbox" id="g8"><label class="goal-label" for="g8"><span class="check-box"></span><span class="goal-icon">⚡</span><span class="goal-text">No Bad Habits</span><span class="goal-pts">12%</span></label></div>
            </div>
          </div>
          <div class="progress-section">
            <div class="progress-row">
              <span class="progress-label">COMPLETION</span>
              <span class="progress-value" id="pct-display">0%</span>
            </div>
            <div class="progress-bar-track"><div class="progress-bar-fill" id="progress-fill"></div></div>
            <div class="winner-banner" id="winner-banner">
              <div class="winner-text">🏆 YOU ARE A TRUE WINNER! 🏆</div>
              <div class="winner-sub">All goals achieved today. Exceptional!</div>
            </div>
            <button class="save-btn" onclick="saveRecord()">⬡ Save Today's Record ⬡</button>
          </div>
        </div>
      </div>
      <div class="right-panel">
        <div>
          <div class="section-title">All-Time Stats</div>
          <div class="panel">
            <div class="stats-grid">
              <div class="stat-cell"><div class="stat-num" id="stat-days">0</div><div class="stat-label">Days Tracked</div></div>
              <div class="stat-cell"><div class="stat-num" id="stat-perfect">0</div><div class="stat-label">Perfect Days</div></div>
              <div class="stat-cell"><div class="stat-num" id="stat-streak">0</div><div class="stat-label">Best Streak</div></div>
              <div class="stat-cell"><div class="stat-num" id="stat-avg">0%</div><div class="stat-label">Avg Score</div></div>
            </div>
          </div>
        </div>
        <div>
          <div class="section-title">Recent Records</div>
          <div class="panel">
            <div class="panel-header">
              <span class="panel-header-title">History</span>
              <button onclick="clearRecords()" style="background:none;border:none;color:var(--text-muted);font-size:10px;cursor:pointer;font-family:'Share Tech Mono',monospace;letter-spacing:0.1em;">CLEAR ALL</button>
            </div>
            <div class="records-list" id="records-list"><div class="no-records">No records yet.<br>Complete goals and save.</div></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ===== MONTHLY PAGE ===== -->
<div class="page" id="page-monthly">
  <div class="monthly-container">

    <div class="month-nav">
      <button class="month-arrow" onclick="changeMonth(-1)">&#8592;</button>
      <div class="month-label" id="month-label">FEBRUARY 2026</div>
      <button class="month-arrow" onclick="changeMonth(1)">&#8594;</button>
    </div>

    <!-- Monthly KPIs -->
    <div class="monthly-stats-row">
      <div class="m-stat"><div class="m-stat-num" id="m-days">0</div><div class="m-stat-label">Days Logged</div></div>
      <div class="m-stat"><div class="m-stat-num" id="m-perfect">0</div><div class="m-stat-label">Perfect Days</div></div>
      <div class="m-stat"><div class="m-stat-num" id="m-avg">0%</div><div class="m-stat-label">Monthly Avg</div></div>
      <div class="m-stat"><div class="m-stat-num" id="m-best">0%</div><div class="m-stat-label">Best Day</div></div>
    </div>

    <!-- Score trend -->
    <div class="section-title">Daily Performance Trend</div>
    <div class="trend-wrap">
      <div class="panel-header">
        <span class="panel-header-title">Score Trend — Each Day of Month</span>
        <span style="font-size:9px;color:var(--text-muted)">GOLD = 100% &nbsp; ORANGE = Partial &nbsp; DARK = No data</span>
      </div>
      <div class="trend-body"><div class="trend-chart" id="trend-chart"></div></div>
    </div>

    <!-- Heatmap calendar -->
    <div class="section-title">Heatmap Calendar</div>
    <div class="calendar-wrap">
      <div class="panel-header"><span class="panel-header-title">Month at a Glance — Hover for details</span></div>
      <div class="cal-body">
        <div class="cal-weekdays">
          <div class="cal-day-name">SUN</div><div class="cal-day-name">MON</div>
          <div class="cal-day-name">TUE</div><div class="cal-day-name">WED</div>
          <div class="cal-day-name">THU</div><div class="cal-day-name">FRI</div>
          <div class="cal-day-name">SAT</div>
        </div>
        <div class="cal-grid" id="cal-grid"></div>
      </div>
    </div>

    <!-- Weekly summary -->
    <div class="section-title">Weekly Summary</div>
    <div class="week-table-wrap">
      <div class="panel-header"><span class="panel-header-title">Week-by-Week Breakdown</span></div>
      <table class="week-table" id="week-table">
        <thead><tr><th>WEEK</th><th>DAYS LOGGED</th><th>PERFECT</th><th>AVG SCORE</th><th>PROGRESS</th></tr></thead>
        <tbody id="week-tbody"></tbody>
      </table>
    </div>

    <!-- Per-goal breakdown -->
    <div class="section-title">Goal Completion Breakdown</div>
    <div class="goal-breakdown-grid" id="goal-breakdown"></div>

  </div>
</div>

<!-- Tooltip -->
<div class="cal-tooltip" id="cal-tooltip"></div>

<script>
const GOALS=[
  {id:'g1',name:'Morning Medicine',  icon:'🌅',pts:13},
  {id:'g2',name:'Afternoon Medicine',icon:'☀️',pts:12},
  {id:'g3',name:'Night Medicine',    icon:'🌙',pts:13},
  {id:'g4',name:'Weight Training',   icon:'🏋️',pts:13},
  {id:'g5',name:'Cardio',            icon:'🏃',pts:12},
  {id:'g6',name:'Proper Sleep',      icon:'😴',pts:13},
  {id:'g7',name:'No Junk Food',      icon:'🥗',pts:12},
  {id:'g8',name:'No Bad Habits',     icon:'⚡',pts:12},
];

let viewMonth=new Date().getMonth(), viewYear=new Date().getFullYear();

// CLOCK
function updateClock(){
  const now=new Date();
  document.getElementById('live-time').textContent=now.toLocaleTimeString('en-US',{hour12:false});
  document.getElementById('live-date').textContent=now.toLocaleDateString('en-US',{weekday:'long',year:'numeric',month:'long',day:'numeric'});
  document.getElementById('panel-date').textContent=now.toLocaleDateString('en-US',{month:'short',day:'numeric',year:'numeric'});
}
updateClock(); setInterval(updateClock,1000);

// TABS
function switchTab(tab){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nav-tab').forEach(t=>t.classList.remove('active'));
  document.getElementById('page-'+tab).classList.add('active');
  document.querySelectorAll('.nav-tab')[tab==='daily'?0:1].classList.add('active');
  if(tab==='monthly') renderMonthly();
}

// REAL-TIME PROGRESS
function updateProgress(){
  let total=0;
  GOALS.forEach(g=>{if(document.getElementById(g.id).checked)total+=g.pts;});
  total=Math.min(total,100);
  document.getElementById('pct-display').textContent=total+'%';
  document.getElementById('progress-fill').style.width=total+'%';
  const pctEl=document.getElementById('pct-display');
  const banner=document.getElementById('winner-banner');
  if(total===100){pctEl.classList.add('winner');banner.classList.add('show');spawnSparkles();}
  else{pctEl.classList.remove('winner');banner.classList.remove('show');}
}
GOALS.forEach(g=>document.getElementById(g.id).addEventListener('change',updateProgress));

// SPARKLES
function spawnSparkles(){
  const emojis=['🏆','⭐','✨','🔥','💪','🎯'];
  for(let i=0;i<12;i++){
    setTimeout(()=>{
      const el=document.createElement('div');el.className='sparkle';
      el.textContent=emojis[Math.floor(Math.random()*emojis.length)];
      el.style.left=Math.random()*window.innerWidth+'px';
      el.style.top=(window.innerHeight*0.3+Math.random()*300)+'px';
      document.body.appendChild(el);setTimeout(()=>el.remove(),2000);
    },i*130);
  }
}

// STORAGE
function getRecords(){return JSON.parse(localStorage.getItem('dailyGoalsRecords')||'[]');}
function saveRecords(r){localStorage.setItem('dailyGoalsRecords',JSON.stringify(r));}

function saveRecord(){
  const now=new Date();
  const dateKey=now.toLocaleDateString('en-US',{month:'short',day:'numeric',year:'numeric'});
  let total=0;const done={};
  GOALS.forEach(g=>{const c=document.getElementById(g.id).checked;done[g.id]=c;if(c)total+=g.pts;});
  total=Math.min(total,100);
  const records=getRecords();
  const idx=records.findIndex(r=>r.dateKey===dateKey);
  const entry={dateKey,timestamp:now.toISOString(),pct:total,goals:done};
  if(idx>=0)records[idx]=entry;else records.unshift(entry);
  saveRecords(records);renderDashboard();
  const btn=document.querySelector('.save-btn');
  btn.textContent='✓ Saved!';btn.style.background='var(--orange)';btn.style.color='#000';
  setTimeout(()=>{btn.textContent='⬡ Save Today\'s Record ⬡';btn.style.background='';btn.style.color='';},1500);
}

function clearRecords(){
  if(!confirm('Clear ALL records? This cannot be undone.'))return;
  localStorage.removeItem('dailyGoalsRecords');renderDashboard();
}

// DAILY DASHBOARD
function renderDashboard(){
  const records=getRecords();
  const list=document.getElementById('records-list');
  if(!records.length){list.innerHTML='<div class="no-records">No records yet.<br>Complete goals and save.</div>';updateStats([]);return;}
  list.innerHTML=records.slice(0,30).map(r=>{
    const ip=r.pct===100;
    const tags=GOALS.map(g=>`<span class="goal-tag ${r.goals&&r.goals[g.id]?'done':''}">${g.name.split(' ')[0]}</span>`).join('');
    return `<div class="record-item">
      <div class="record-top"><span class="record-date">${r.dateKey}</span><span class="record-pct ${ip?'perfect':''}">${r.pct}%${ip?' 🏆':''}</span></div>
      <div class="record-bar-track"><div class="record-bar-fill" style="width:${r.pct}%"></div></div>
      <div class="record-goals">${tags}</div></div>`;
  }).join('');
  updateStats(records);
}

function updateStats(records){
  const total=records.length,perfect=records.filter(r=>r.pct===100).length;
  const avg=total?Math.round(records.reduce((s,r)=>s+r.pct,0)/total):0;
  let streak=0;for(const r of records){if(r.pct===100)streak++;else break;}
  document.getElementById('stat-days').textContent=total;
  document.getElementById('stat-perfect').textContent=perfect;
  document.getElementById('stat-streak').textContent=streak;
  document.getElementById('stat-avg').textContent=avg+'%';
}

// ======= MONTHLY =======
const MONTH_NAMES=['JANUARY','FEBRUARY','MARCH','APRIL','MAY','JUNE','JULY','AUGUST','SEPTEMBER','OCTOBER','NOVEMBER','DECEMBER'];

function changeMonth(d){
  viewMonth+=d;
  if(viewMonth>11){viewMonth=0;viewYear++;}
  if(viewMonth<0){viewMonth=11;viewYear--;}
  renderMonthly();
}

function getMonthRecords(month,year){
  return getRecords().filter(r=>{const d=new Date(r.timestamp);return d.getMonth()===month&&d.getFullYear()===year;});
}

function renderMonthly(){
  document.getElementById('month-label').textContent=MONTH_NAMES[viewMonth]+' '+viewYear;
  const mRecs=getMonthRecords(viewMonth,viewYear);
  const byDay={};
  mRecs.forEach(r=>{const d=new Date(r.timestamp);byDay[d.getDate()]=r;});

  // KPIs
  const mDays=mRecs.length,mPerf=mRecs.filter(r=>r.pct===100).length;
  const mAvg=mDays?Math.round(mRecs.reduce((s,r)=>s+r.pct,0)/mDays):0;
  const mBest=mDays?Math.max(...mRecs.map(r=>r.pct)):0;
  document.getElementById('m-days').textContent=mDays;
  document.getElementById('m-perfect').textContent=mPerf;
  document.getElementById('m-avg').textContent=mAvg+'%';
  document.getElementById('m-best').textContent=mBest+'%';

  renderTrend(byDay);
  renderCalendar(byDay);
  renderWeeklyTable(byDay);
  renderGoalBreakdown(mRecs);
}

function heatClass(pct){
  if(pct===undefined)return'heat-0';
  if(pct===100)return'heat-perfect';
  if(pct>=85)return'heat-6';
  if(pct>=70)return'heat-5';
  if(pct>=55)return'heat-4';
  if(pct>=40)return'heat-3';
  if(pct>=20)return'heat-2';
  return'heat-1';
}
function pctColor(pct){
  if(pct===100)return'var(--orange-glow)';
  if(pct>=70)return'var(--orange-hot)';
  if(pct>=40)return'var(--orange)';
  return'var(--orange-dim)';
}

function renderTrend(byDay){
  const dim=new Date(viewYear,viewMonth+1,0).getDate();
  let html='';
  for(let d=1;d<=dim;d++){
    const rec=byDay[d];
    const pct=rec?rec.pct:0;
    const cls=rec?(pct===100?'perfect':''):'nodata';
    html+=`<div class="trend-bar-col">
      <div class="trend-bar ${cls}" style="height:${Math.max(pct,2)}%"></div>
      <div class="trend-day">${d}</div></div>`;
  }
  document.getElementById('trend-chart').innerHTML=html;
}

function renderCalendar(byDay){
  const dim=new Date(viewYear,viewMonth+1,0).getDate();
  const fdow=new Date(viewYear,viewMonth,1).getDay();
  const today=new Date();
  const isCur=today.getMonth()===viewMonth&&today.getFullYear()===viewYear;
  let html='';
  for(let i=0;i<fdow;i++)html+=`<div class="cal-cell empty"></div>`;
  for(let d=1;d<=dim;d++){
    const rec=byDay[d];
    const isToday=isCur&&today.getDate()===d;
    const hc=heatClass(rec?rec.pct:undefined);
    const hasData=!!rec;
    const color=rec?pctColor(rec.pct):'var(--text-muted)';
    html+=`<div class="cal-cell ${hc} ${hasData?'has-data':''} ${isToday?'today':''}"
      ${hasData?`onmouseenter="showTooltip(event,${d})" onmouseleave="hideTooltip()"`:''}>
      <span class="cal-day-num" style="${isToday?'color:var(--orange)':''}">${d}</span>
      ${rec?`<span class="cal-pct" style="color:${color}">${rec.pct}%</span>`:''}
    </div>`;
  }
  document.getElementById('cal-grid').innerHTML=html;
}

function renderWeeklyTable(byDay){
  const dim=new Date(viewYear,viewMonth+1,0).getDate();
  const fdow=new Date(viewYear,viewMonth,1).getDay();
  const weeks=[];let week={days:[],start:0};
  // fill leading empty days
  for(let i=0;i<fdow;i++)week.days.push(null);
  for(let d=1;d<=dim;d++){
    if(week.days.length===0)week.start=d;
    week.days.push(d);
    if(week.days.length===7){weeks.push(week);week={days:[],start:0};}
  }
  if(week.days.length>0)weeks.push(week);

  const tbody=document.getElementById('week-tbody');
  tbody.innerHTML=weeks.map((w,wi)=>{
    const realDays=w.days.filter(d=>d!==null);
    const recs=realDays.map(d=>byDay[d]).filter(Boolean);
    const logged=recs.length,perfect=recs.filter(r=>r.pct===100).length;
    const avg=logged?Math.round(recs.reduce((s,r)=>s+r.pct,0)/logged):0;
    const startD=realDays[0],endD=realDays[realDays.length-1];
    const label=`Week ${wi+1} &nbsp;<span style="color:var(--text-muted);font-size:9px">(${MONTH_NAMES[viewMonth].slice(0,3)} ${startD}–${endD})</span>`;
    return `<tr>
      <td>${label}</td>
      <td>${logged} / ${realDays.length}</td>
      <td style="color:${perfect>0?'var(--orange-glow)':'var(--text-muted)'}">${perfect}</td>
      <td><span class="week-pct ${avg===100?'perfect':''}">${logged?avg+'%':'—'}</span></td>
      <td><div class="week-mini-bar"><div class="week-mini-fill" style="width:${avg}%"></div></div></td>
    </tr>`;
  }).join('');
}

function renderGoalBreakdown(mRecs){
  const gb=document.getElementById('goal-breakdown');
  if(!mRecs.length){
    gb.innerHTML=`<div style="grid-column:span 2;padding:20px;text-align:center;font-size:10px;color:var(--text-muted);">No data for this month.</div>`;
    return;
  }
  gb.innerHTML=GOALS.map(g=>{
    const count=mRecs.filter(r=>r.goals&&r.goals[g.id]).length;
    const ratePct=Math.round((count/mRecs.length)*100);
    return `<div class="goal-break-item">
      <div class="gb-top">
        <span class="gb-name">${g.icon} ${g.name}</span>
        <span class="gb-count">${count}<span style="font-size:14px;color:var(--text-muted)">/${mRecs.length}</span></span>
      </div>
      <div class="gb-bar-track"><div class="gb-bar-fill" style="width:${ratePct}%"></div></div>
      <div class="gb-label">${ratePct}% completion rate among logged days</div>
    </div>`;
  }).join('');
}

// TOOLTIP
function showTooltip(e,day){
  const rec=getRecords().find(r=>{const d=new Date(r.timestamp);return d.getDate()===day&&d.getMonth()===viewMonth&&d.getFullYear()===viewYear;});
  if(!rec)return;
  const tt=document.getElementById('cal-tooltip');
  const ds=new Date(rec.timestamp).toLocaleDateString('en-US',{weekday:'short',month:'long',day:'numeric'});
  const rows=GOALS.map(g=>`<div class="tt-goal"><div class="tt-dot ${rec.goals&&rec.goals[g.id]?'done':'miss'}"></div><span style="color:${rec.goals&&rec.goals[g.id]?'var(--text-dim)':'var(--text-muted)'}">${g.icon} ${g.name}</span></div>`).join('');
  tt.innerHTML=`<div class="tt-date">${ds}</div><div class="tt-pct">${rec.pct}%${rec.pct===100?' 🏆':''}</div>${rows}`;
  tt.classList.add('show');
  const x=e.clientX+14,y=e.clientY-10;
  tt.style.left=(x+180>window.innerWidth?x-195:x)+'px';
  tt.style.top=(y+260>window.innerHeight?y-260:y)+'px';
}
function hideTooltip(){document.getElementById('cal-tooltip').classList.remove('show');}

// INIT
renderDashboard();
</script>
</body>
</html>
