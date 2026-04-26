<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>稲葉化 週間トレーニング票</title>
<style>
  :root {
    --gold: #c9a84c;
    --gold-light: #f0d080;
    --bg: #0d0d0d;
    --surface: #1a1a1a;
    --surface2: #222;
    --border: #333;
    --text: #e8e8e8;
    --muted: #888;
    --red: #e05555;
    --blue: #5588e0;
    --green: #55aa66;
    --purple: #9988ff;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Meiryo', sans-serif;
    font-size: 14px;
    line-height: 1.5;
    padding: 24px 16px 48px;
  }

  /* ── HEADER ── */
  header {
    text-align: center;
    margin-bottom: 24px;
    padding: 28px 16px;
    background: linear-gradient(135deg, #111 0%, #1e1a0e 100%);
    border: 1px solid var(--gold);
    border-radius: 12px;
    position: relative;
    overflow: hidden;
    max-width: 1400px;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 20px;
  }
  header::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse at 50% 0%, rgba(201,168,76,0.12) 0%, transparent 70%);
    pointer-events: none;
  }
  header h1 {
    font-size: clamp(20px, 5vw, 32px);
    font-weight: 900;
    letter-spacing: 0.08em;
    color: var(--gold-light);
    text-shadow: 0 0 20px rgba(201,168,76,0.6);
    margin-bottom: 6px;
  }
  header .subtitle { font-size: 13px; color: var(--muted); letter-spacing: 0.05em; }
  header .badges {
    display: flex; gap: 8px; justify-content: center; margin-top: 12px; flex-wrap: wrap;
  }
  .badge {
    font-size: 11px; padding: 3px 10px; border-radius: 20px;
    border: 1px solid var(--gold); color: var(--gold);
    background: rgba(201,168,76,0.08); letter-spacing: 0.03em;
  }

  /* ── NUTRITION ── */
  .nutrition-section {
    max-width: 1400px;
    margin: 0 auto 24px;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    overflow: hidden;
  }
  .nutrition-header {
    padding: 12px 18px;
    background: linear-gradient(90deg, rgba(85,170,102,0.2) 0%, transparent 100%);
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .nutrition-header h2 {
    font-size: 14px;
    font-weight: 700;
    letter-spacing: 0.04em;
    color: var(--green);
  }
  .nutrition-header .nut-sub {
    font-size: 11px;
    color: var(--muted);
  }
  .nutrition-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 0;
  }
  .nut-card {
    padding: 16px 18px;
    border-right: 1px solid var(--border);
    text-align: center;
  }
  .nut-card:last-child { border-right: none; }
  .nut-label {
    font-size: 10px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 4px;
  }
  .nut-main {
    font-size: 22px;
    font-weight: 900;
    line-height: 1.1;
    margin-bottom: 2px;
  }
  .nut-sub-val { font-size: 11px; color: var(--muted); }
  .nut-bar {
    margin-top: 8px;
    height: 4px;
    border-radius: 2px;
    background: var(--border);
    overflow: hidden;
  }
  .nut-bar-fill { height: 100%; border-radius: 2px; }
  .nut-p .nut-main { color: #66aaff; }
  .nut-p .nut-bar-fill { background: #66aaff; width: 34.9%; }
  .nut-f .nut-main { color: #ffaa55; }
  .nut-f .nut-bar-fill { background: #ffaa55; width: 20%; }
  .nut-c .nut-main { color: #66cc88; }
  .nut-c .nut-bar-fill { background: #66cc88; width: 45.1%; }
  .nut-total .nut-main { color: var(--gold-light); }
  .nut-total { background: rgba(201,168,76,0.04); }

  /* ── TABS ── */
  .tabs-wrap {
    max-width: 1400px;
    margin: 0 auto 20px;
    display: flex;
    gap: 8px;
  }
  .tab-btn {
    padding: 10px 20px;
    border-radius: 8px 8px 0 0;
    border: 1px solid var(--border);
    border-bottom: none;
    background: var(--surface2);
    color: var(--muted);
    font-size: 13px;
    font-weight: 600;
    cursor: pointer;
    letter-spacing: 0.03em;
    transition: all 0.15s;
    display: flex;
    align-items: center;
    gap: 6px;
  }
  .tab-btn:hover { color: var(--text); background: var(--surface); }
  .tab-btn.active {
    background: var(--surface);
    color: var(--gold-light);
    border-color: var(--gold);
    border-bottom: 1px solid var(--surface);
    position: relative;
    z-index: 1;
  }
  .tab-panel { display: none; }
  .tab-panel.active { display: block; }

  /* ── WEEK GRID ── */
  .week-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    max-width: 1400px;
    margin: 0 auto;
  }

  /* ── DAY CARD ── */
  .day-card {
    background: var(--surface);
    border-radius: 10px;
    border: 1px solid var(--border);
    overflow: hidden;
    display: flex;
    flex-direction: column;
  }
  .day-card.rest { border-color: #444; opacity: 0.8; }

  .day-header {
    padding: 14px 18px;
    display: flex;
    align-items: center;
    gap: 12px;
    border-bottom: 1px solid var(--border);
  }
  .day-label { font-size: 22px; font-weight: 900; min-width: 40px; }
  .day-info { flex: 1; }
  .day-info .day-name { font-size: 12px; color: var(--muted); letter-spacing: 0.05em; }
  .day-info .day-theme { font-size: 15px; font-weight: 700; color: var(--text); letter-spacing: 0.02em; }

  /* ── day color accents – 4-day ── */
  .w4 .mon .day-header { background: linear-gradient(90deg, rgba(80,60,200,0.18) 0%, transparent 100%); }
  .w4 .tue .day-header { background: linear-gradient(90deg, rgba(200,80,60,0.18) 0%, transparent 100%); }
  .w4 .wed .day-header { background: linear-gradient(90deg, rgba(60,140,80,0.18) 0%, transparent 100%); }
  .w4 .thu .day-header { background: linear-gradient(90deg, rgba(60,140,200,0.18) 0%, transparent 100%); }
  .w4 .fri .day-header { background: linear-gradient(90deg, rgba(201,168,76,0.22) 0%, transparent 100%); }
  .w4 .mon .day-label { color: #9988ff; }
  .w4 .tue .day-label { color: #ff7766; }
  .w4 .wed .day-label { color: #66cc88; }
  .w4 .thu .day-label { color: #66aaff; }
  .w4 .fri .day-label { color: var(--gold-light); }

  /* ── day color accents – 3-day ── */
  .w3 .mon .day-header { background: linear-gradient(90deg, rgba(220,60,60,0.2) 0%, transparent 100%); }
  .w3 .wed .day-header { background: linear-gradient(90deg, rgba(60,180,100,0.18) 0%, transparent 100%); }
  .w3 .fri .day-header { background: linear-gradient(90deg, rgba(201,168,76,0.22) 0%, transparent 100%); }
  .w3 .mon .day-label { color: #ff6666; }
  .w3 .wed .day-label { color: #66cc88; }
  .w3 .fri .day-label { color: var(--gold-light); }

  /* intensity badges */
  .intensity {
    font-size: 10px;
    padding: 2px 8px;
    border-radius: 10px;
    letter-spacing: 0.04em;
    font-weight: 700;
    white-space: nowrap;
  }
  .intensity.high { background: rgba(224,85,85,0.15); border: 1px solid #e05555; color: #e05555; }
  .intensity.mid  { background: rgba(201,168,76,0.12); border: 1px solid var(--gold); color: var(--gold); }
  .intensity.low  { background: rgba(85,170,102,0.15); border: 1px solid #55aa66; color: #55aa66; }

  /* ── TABLE ── */
  .exercises { padding: 0; flex: 1; }
  table { width: 100%; border-collapse: collapse; }
  thead th {
    padding: 8px 10px;
    font-size: 10px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--muted);
    text-align: left;
    border-bottom: 1px solid var(--border);
    background: var(--surface2);
  }
  thead th:not(:first-child):not(:nth-child(2)) { text-align: center; }
  tbody tr { border-bottom: 1px solid #2a2a2a; transition: background 0.15s; }
  tbody tr:last-child { border-bottom: none; }
  tbody tr:hover { background: rgba(255,255,255,0.03); }
  td { padding: 10px 10px; vertical-align: top; }

  td.exercise-name {
    font-weight: 600;
    font-size: 13px;
    display: flex;
    align-items: flex-start;
    gap: 6px;
  }
  td.exercise-name .icon { font-size: 14px; line-height: 1.4; flex-shrink: 0; }
  td.weight { text-align: center; font-size: 12px; font-weight: 700; color: var(--gold); white-space: nowrap; }
  td.sets   { text-align: center; font-size: 12px; color: #ccc; white-space: nowrap; }
  td.note   { font-size: 11px; color: var(--muted); line-height: 1.4; }

  .cardio-row { background: rgba(201,168,76,0.04); }
  .cardio-row td.exercise-name { color: var(--gold); }

  td.check { text-align: center; width: 32px; }
  input[type="checkbox"] {
    width: 16px; height: 16px; accent-color: var(--gold); cursor: pointer; margin-top: 2px;
  }

  /* ── REST CARD ── */
  .rest-body { padding: 24px 18px; display: flex; flex-direction: column; gap: 14px; flex: 1; }
  .rest-item {
    display: flex; align-items: flex-start; gap: 12px;
    padding: 12px 14px; background: var(--surface2); border-radius: 8px;
    border-left: 3px solid var(--green);
  }
  .rest-icon { font-size: 20px; }
  .rest-label { font-size: 12px; color: var(--muted); margin-bottom: 2px; }
  .rest-value { font-size: 14px; font-weight: 600; color: var(--text); }

  .total-timer {
    margin: 0 10px 10px;
    padding: 8px 12px;
    background: rgba(201,168,76,0.06);
    border: 1px solid rgba(201,168,76,0.2);
    border-radius: 6px;
    display: flex; align-items: center; gap: 8px;
    font-size: 11px; color: var(--muted);
  }
  .total-timer strong { color: var(--gold); }

  /* ── LEGEND ── */
  .legend {
    max-width: 1400px;
    margin: 28px auto 0;
    padding: 14px 18px;
    background: var(--surface);
    border-radius: 8px;
    border: 1px solid var(--border);
    font-size: 12px;
    color: var(--muted);
    display: flex; flex-wrap: wrap; gap: 16px; align-items: center;
  }
  .legend strong { color: var(--text); }

  /* ── RESPONSIVE ── */
  @media (max-width: 600px) {
    .nutrition-grid { grid-template-columns: repeat(2, 1fr); }
    .nut-card:nth-child(2) { border-right: none; }
    .nut-card:nth-child(3) { border-right: 1px solid var(--border); border-top: 1px solid var(--border); }
    .nut-card:nth-child(4) { border-top: 1px solid var(--border); }
  }

  @media print {
    body { background: white; color: black; padding: 12px; }
    .day-card { border: 1px solid #ccc; break-inside: avoid; }
    .day-header { background: none !important; }
    .day-label { color: #333 !important; }
    header { background: none; border: 1px solid #999; }
    header h1 { color: #333; text-shadow: none; }
    td.weight { color: #555; }
    input[type="checkbox"] { display: none; }
    .tab-btn { display: none; }
    .tab-panel { display: block !important; }
  }
</style>
</head>
<body>

<!-- HEADER -->
<header>
  <h1>⚡ 稲葉化 週間トレーニング票</h1>
  <div class="subtitle">2026 / 04 / 27（月）〜　完全版</div>
  <div class="badges">
    <span class="badge">⏱ 全日1時間以内</span>
    <span class="badge">🔁 インターバル 1〜2分</span>
    <span class="badge">🥗 目標 1,800 kcal</span>
  </div>
</header>

<!-- NUTRITION -->
<section class="nutrition-section">
  <div class="nutrition-header">
    <h2>🥗 PFCバランス（日次栄養目標）</h2>
    <span class="nut-sub">— 1,800 kcal / 日</span>
  </div>
  <div class="nutrition-grid">
    <div class="nut-card nut-p">
      <div class="nut-label">P ／ タンパク質</div>
      <div class="nut-main">157g</div>
      <div class="nut-sub-val">628 kcal（34.9%）</div>
      <div class="nut-bar"><div class="nut-bar-fill"></div></div>
    </div>
    <div class="nut-card nut-f">
      <div class="nut-label">F ／ 脂質</div>
      <div class="nut-main">40g</div>
      <div class="nut-sub-val">360 kcal（20.0%）</div>
      <div class="nut-bar"><div class="nut-bar-fill"></div></div>
    </div>
    <div class="nut-card nut-c">
      <div class="nut-label">C ／ 炭水化物</div>
      <div class="nut-main">203g</div>
      <div class="nut-sub-val">812 kcal（45.1%）</div>
      <div class="nut-bar"><div class="nut-bar-fill"></div></div>
    </div>
    <div class="nut-card nut-total">
      <div class="nut-label">合計</div>
      <div class="nut-main">1,800</div>
      <div class="nut-sub-val">kcal / 日</div>
      <div class="nut-bar" style="background:transparent"></div>
    </div>
  </div>
</section>

<!-- TABS -->
<div class="tabs-wrap">
  <button class="tab-btn active" onclick="switchTab('w4')">💪 週4日版</button>
  <button class="tab-btn" onclick="switchTab('w3')">⚡ 週3日版</button>
</div>

<!-- ════════════════════════════
     週4日版
════════════════════════════ -->
<div class="tab-panel active" id="panel-w4">
<div class="week-grid w4">

  <!-- MON -->
  <div class="day-card mon">
    <div class="day-header">
      <div class="day-label">月</div>
      <div class="day-info">
        <div class="day-name">MONDAY · 04/27</div>
        <div class="day-theme">全身覚醒 · BIG2 ＋ 翼</div>
      </div>
    </div>
    <div class="exercises">
      <table>
        <thead><tr><th></th><th>種目</th><th>重量</th><th>回数×セット</th><th>備考</th></tr></thead>
        <tbody>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>デッドリフト</td>
            <td class="weight">100〜120kg</td>
            <td class="sets">5〜8回 × 3</td>
            <td class="note">全身のパワーを呼び起こす</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">💪</span>ベンチプレス</td>
            <td class="weight">70〜80kg</td>
            <td class="sets">5〜8回 × 3</td>
            <td class="note">厚みのある胸板を作る</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦅</span>チンニング</td>
            <td class="weight">自重 (or補助)</td>
            <td class="sets">限界 × 3</td>
            <td class="note">背中の広がりと二頭筋への刺激</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦵</span>カーフレイズ</td>
            <td class="weight">80kg</td>
            <td class="sets">限界 × 3</td>
            <td class="note">毎日継続</td>
          </tr>
          <tr class="cardio-row">
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🔥</span>トレッドミル</td>
            <td class="weight">傾斜 10〜15%</td>
            <td class="sets">4.5km/h × 20分</td>
            <td class="note">脂肪燃焼の開始</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="total-timer">⏱ 目安 <strong>55分</strong>以内に完遂</div>
  </div>

  <!-- TUE -->
  <div class="day-card tue">
    <div class="day-header">
      <div class="day-label">火</div>
      <div class="day-info">
        <div class="day-name">TUESDAY · 04/28</div>
        <div class="day-theme">下半身 · 代謝爆発</div>
      </div>
    </div>
    <div class="exercises">
      <table>
        <thead><tr><th></th><th>種目</th><th>重量</th><th>回数×セット</th><th>備考</th></tr></thead>
        <tbody>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>スクワット</td>
            <td class="weight">80〜100kg</td>
            <td class="sets">8〜10回 × 3</td>
            <td class="note">最大筋肉を動かし代謝を最大化</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦵</span>レッグプレス</td>
            <td class="weight">120〜150kg</td>
            <td class="sets">12〜15回 × 3</td>
            <td class="note">脚を徹底的に追い込む</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦵</span>カーフレイズ</td>
            <td class="weight">80kg</td>
            <td class="sets">限界 × 3</td>
            <td class="note">妥協なき継続</td>
          </tr>
          <tr class="cardio-row">
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🔥</span>トレッドミル</td>
            <td class="weight">傾斜 10〜15%</td>
            <td class="sets">4.5km/h × 20分</td>
            <td class="note">代謝を高く保つ</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="total-timer">⏱ 目安 <strong>55分</strong>以内に完遂</div>
  </div>

  <!-- WED REST -->
  <div class="day-card wed rest">
    <div class="day-header">
      <div class="day-label">水</div>
      <div class="day-info">
        <div class="day-name">WEDNESDAY · 04/29</div>
        <div class="day-theme">完全休養</div>
      </div>
    </div>
    <div class="rest-body">
      <div class="rest-item" style="border-left-color: var(--green);">
        <div class="rest-icon">🥗</div>
        <div>
          <div class="rest-label">カロリー管理</div>
          <div class="rest-value">1,800 kcal を維持</div>
        </div>
      </div>
      <div class="rest-item" style="border-left-color: #5588e0;">
        <div class="rest-icon">🧠</div>
        <div>
          <div class="rest-label">意義</div>
          <div class="rest-value">木曜からの「造形」に向けて神経系を休ませる</div>
        </div>
      </div>
      <div class="rest-item" style="border-left-color: #9988ff;">
        <div class="rest-icon">💤</div>
        <div>
          <div class="rest-label">推奨</div>
          <div class="rest-value">睡眠・ストレッチ・栄養補給を優先</div>
        </div>
      </div>
    </div>
  </div>

  <!-- THU -->
  <div class="day-card thu">
    <div class="day-header">
      <div class="day-label">木</div>
      <div class="day-info">
        <div class="day-name">THURSDAY · 04/30</div>
        <div class="day-theme">上半身 · 彫刻（キレ重視）</div>
      </div>
    </div>
    <div class="exercises">
      <table>
        <thead><tr><th></th><th>種目</th><th>重量</th><th>回数×セット</th><th>備考</th></tr></thead>
        <tbody>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">💪</span>ベンチプレス</td>
            <td class="weight">70kg (中重量)</td>
            <td class="sets">10〜12回 × 3</td>
            <td class="note">頻度を保ち、胸のカットを出す</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦅</span>チンニング</td>
            <td class="weight">自重 (or補助)</td>
            <td class="sets">限界 × 3</td>
            <td class="note">逆三角形を強調する</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏅</span>サイドレイズ</td>
            <td class="weight">8〜12kg</td>
            <td class="sets">15〜20回 × 3</td>
            <td class="note">肩の立体感（メロン肩）を作る</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦵</span>カーフレイズ</td>
            <td class="weight">80kg</td>
            <td class="sets">限界 × 3</td>
            <td class="note">キレの源</td>
          </tr>
          <tr class="cardio-row">
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🔥</span>トレッドミル</td>
            <td class="weight">傾斜 10〜15%</td>
            <td class="sets">4.5km/h × 20分</td>
            <td class="note">常に脂肪を焼き続ける</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="total-timer">⏱ 目安 <strong>55分</strong>以内に完遂</div>
  </div>

  <!-- FRI -->
  <div class="day-card fri">
    <div class="day-header">
      <div class="day-label">金</div>
      <div class="day-info">
        <div class="day-name">FRIDAY · 05/01</div>
        <div class="day-theme">造形仕上げ · 厚み ＋ 腕</div>
      </div>
    </div>
    <div class="exercises">
      <table>
        <thead><tr><th></th><th>種目</th><th>重量</th><th>回数×セット</th><th>備考</th></tr></thead>
        <tbody>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>スクワット</td>
            <td class="weight">80kg</td>
            <td class="sets">10〜12回 × 3</td>
            <td class="note">週2回の刺激で代謝を落とさない</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🔩</span>ベントオーバーロー</td>
            <td class="weight">50〜60kg</td>
            <td class="sets">10〜12回 × 3</td>
            <td class="note">背中の厚みを構築する</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">💪</span>プレスダウン</td>
            <td class="weight">ケーブル</td>
            <td class="sets">12〜15回 × 3</td>
            <td class="note">腕の裏側のキレ</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">✦</span>ケーブルカール <span style="font-size:10px;color:var(--muted)">(任意)</span></td>
            <td class="weight">ケーブル</td>
            <td class="sets">12〜15回 × 2</td>
            <td class="note">二頭筋が欲しければ追加</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦵</span>カーフレイズ</td>
            <td class="weight">80kg</td>
            <td class="sets">限界 × 3</td>
            <td class="note">一週間の締め</td>
          </tr>
          <tr class="cardio-row">
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">💀</span>トレッドミル</td>
            <td class="weight">傾斜 15%</td>
            <td class="sets">5.0km/h × 30分</td>
            <td class="note">最後は最大負荷で脂肪を殺す</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="total-timer">⏱ 目安 <strong>60分</strong>以内に完遂</div>
  </div>

</div><!-- /week-grid w4 -->
</div><!-- /panel-w4 -->


<!-- ════════════════════════════
     週3日版
════════════════════════════ -->
<div class="tab-panel" id="panel-w3">
<div class="week-grid w3">

  <!-- MON – HIGH -->
  <div class="day-card mon">
    <div class="day-header">
      <div class="day-label">月</div>
      <div class="day-info">
        <div class="day-name">MONDAY · パワー日</div>
        <div class="day-theme">パワー · 高強度</div>
      </div>
      <span class="intensity high">HIGH</span>
    </div>
    <div class="exercises">
      <table>
        <thead><tr><th></th><th>種目</th><th>重量目安</th><th>回数×セット</th><th>備考</th></tr></thead>
        <tbody>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>スクワット</td>
            <td class="weight">100kg〜</td>
            <td class="sets">5〜8回 × 3</td>
            <td class="note">最初に全力を出し切る</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">💪</span>ベンチプレス</td>
            <td class="weight">80kg〜</td>
            <td class="sets">5〜8回 × 3</td>
            <td class="note">胸の厚みを死守</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>デッドリフト</td>
            <td class="weight">120kg〜</td>
            <td class="sets">3〜5回 × 2</td>
            <td class="note">最高重量に挑む</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦅</span>チンニング</td>
            <td class="weight">自重</td>
            <td class="sets">限界 × 3</td>
            <td class="note">広がりを作る</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦵</span>カーフレイズ</td>
            <td class="weight">80kg</td>
            <td class="sets">15〜20回 × 3</td>
            <td class="note">鉄の掟</td>
          </tr>
          <tr class="cardio-row">
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🔥</span>トレッドミル</td>
            <td class="weight">傾斜 15%</td>
            <td class="sets">4.5km/h × 20分</td>
            <td class="note">脂肪を焼く</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="total-timer">⏱ 目安 <strong>60分</strong>以内に完遂</div>
  </div>

  <!-- WED – LOW -->
  <div class="day-card wed">
    <div class="day-header">
      <div class="day-label">水</div>
      <div class="day-info">
        <div class="day-name">WEDNESDAY · スキル日</div>
        <div class="day-theme">スキル · 低強度</div>
      </div>
      <span class="intensity low">LOW</span>
    </div>
    <div class="exercises">
      <table>
        <thead><tr><th></th><th>種目</th><th>重量目安</th><th>回数×セット</th><th>備考</th></tr></thead>
        <tbody>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>スクワット</td>
            <td class="weight">60〜70kg</td>
            <td class="sets">12〜15回 × 2</td>
            <td class="note">フォーム重視</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">💪</span>ベンチプレス</td>
            <td class="weight">50〜60kg</td>
            <td class="sets">12〜15回 × 2</td>
            <td class="note">軌道を確認</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>デッドリフト</td>
            <td class="weight">70〜80kg</td>
            <td class="sets">10〜12回 × 1</td>
            <td class="note">血流を促す程度</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦅</span>チンニング</td>
            <td class="weight">自重</td>
            <td class="sets">限界の50% × 2</td>
            <td class="note">関節を休める</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦵</span>カーフレイズ</td>
            <td class="weight">80kg</td>
            <td class="sets">15〜20回 × 3</td>
            <td class="note">継続</td>
          </tr>
          <tr class="cardio-row">
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🚶</span>トレッドミル</td>
            <td class="weight">傾斜 10%</td>
            <td class="sets">4.0km/h × 20分</td>
            <td class="note">積極的休息</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="total-timer">⏱ 目安 <strong>50分</strong>以内に完遂</div>
  </div>

  <!-- FRI – MID -->
  <div class="day-card fri">
    <div class="day-header">
      <div class="day-label">金</div>
      <div class="day-info">
        <div class="day-name">FRIDAY · ビルド日</div>
        <div class="day-theme">ビルド · 中強度</div>
      </div>
      <span class="intensity mid">MID</span>
    </div>
    <div class="exercises">
      <table>
        <thead><tr><th></th><th>種目</th><th>重量目安</th><th>回数×セット</th><th>備考</th></tr></thead>
        <tbody>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>スクワット</td>
            <td class="weight">80kg</td>
            <td class="sets">10〜12回 × 3</td>
            <td class="note">パンプアップ</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">💪</span>ベンチプレス</td>
            <td class="weight">70kg</td>
            <td class="sets">10〜12回 × 3</td>
            <td class="note">収縮を意識</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🏋️</span>デッドリフト</td>
            <td class="weight">100kg</td>
            <td class="sets">8〜10回 × 2</td>
            <td class="note">中重量で背面を追い込む</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">✦</span>腕（三頭・二頭）<span style="font-size:10px;color:var(--muted)">任意</span></td>
            <td class="weight">任意</td>
            <td class="sets">12〜15回 × 各2</td>
            <td class="note">必要に応じて追加</td>
          </tr>
          <tr>
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">🦵</span>カーフレイズ</td>
            <td class="weight">80kg</td>
            <td class="sets">15〜20回 × 3</td>
            <td class="note">仕上げ</td>
          </tr>
          <tr class="cardio-row">
            <td class="check"><input type="checkbox"></td>
            <td class="exercise-name"><span class="icon">💀</span>トレッドミル</td>
            <td class="weight">傾斜 15%</td>
            <td class="sets">5.0km/h × 30分</td>
            <td class="note">最大燃焼</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="total-timer">⏱ 目安 <strong>60分</strong>以内に完遂</div>
  </div>

</div><!-- /week-grid w3 -->
</div><!-- /panel-w3 -->


<!-- LEGEND -->
<div class="legend">
  <strong>共通ルール：</strong>
  <span>⏱ 全日1時間以内に完遂</span>
  <span>🔁 インターバル 1〜2分</span>
  <span>☑ 完了したセットはチェック</span>
  <span style="color:var(--gold)">🔥 カーフレイズは毎日継続が絶対条件</span>
</div>

<script>
  function switchTab(id) {
    document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
    document.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
    document.getElementById('panel-' + id).classList.add('active');
    event.currentTarget.classList.add('active');
  }
</script>
</body>
</html>
