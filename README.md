
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background: #0d1117; color: #e6edf3; font-family: 'Courier New', monospace; }
  .container { max-width: 680px; margin: 0 auto; padding: 1.5rem 1rem; background: #0d1117; }
  .hero { text-align: center; padding: 2rem 1rem; border: 1px solid #30363d; border-radius: 8px; background: #0d1117; margin-bottom: 1.5rem; position: relative; overflow: hidden; }
  .hero::before { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 2px; background: linear-gradient(90deg, #00ff88, #0ea5e9, #a855f7); }
  .ascii { color: #00ff88; font-size: 9px; line-height: 1.2; white-space: pre; margin-bottom: 1rem; display: block; }
  .hero h1 { font-size: 1.4rem; color: #e6edf3; font-weight: 700; margin-bottom: 0.4rem; }
  .hero h1 span { color: #00ff88; }
  .typing { color: #7d8590; font-size: 0.85rem; border-right: 2px solid #00ff88; animation: blink 1s step-end infinite; display: inline-block; padding-right: 4px; }
  @keyframes blink { 0%, 100% { border-color: #00ff88; } 50% { border-color: transparent; } }
  .badges { display: flex; flex-wrap: wrap; gap: 6px; justify-content: center; margin-top: 1rem; }
  .badge { background: #161b22; border: 1px solid #30363d; border-radius: 4px; padding: 3px 10px; font-size: 11px; color: #8b949e; }
  .badge.green { border-color: #238636; color: #3fb950; }
  .badge.blue { border-color: #0ea5e9; color: #58a6ff; }
  .badge.purple { border-color: #7c3aed; color: #a78bfa; }
  .section { margin-bottom: 1.5rem; }
  .section-title { color: #00ff88; font-size: 0.75rem; font-weight: 700; text-transform: uppercase; letter-spacing: 2px; margin-bottom: 0.75rem; display: flex; align-items: center; gap: 8px; }
  .section-title::after { content: ''; flex: 1; height: 1px; background: #21262d; }
  .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .card { background: #161b22; border: 1px solid #21262d; border-radius: 6px; padding: 0.85rem; }
  .card:hover { border-color: #30363d; }
  .card-title { font-size: 0.8rem; color: #e6edf3; font-weight: 600; margin-bottom: 4px; }
  .card-sub { font-size: 0.7rem; color: #7d8590; }
  .card-dot { width: 8px; height: 8px; border-radius: 50%; background: #00ff88; display: inline-block; margin-right: 5px; }
  .card-dot.blue { background: #58a6ff; }
  .card-dot.yellow { background: #d29922; }
  .skills-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; }
  .skill-chip { background: #0d1117; border: 1px solid #21262d; border-radius: 4px; padding: 6px 10px; text-align: center; font-size: 11px; color: #8b949e; }
  .skill-chip:hover { border-color: #00ff88; color: #00ff88; }
  .stat-row { display: flex; gap: 8px; }
  .stat-card { flex: 1; background: #161b22; border: 1px solid #21262d; border-radius: 6px; padding: 0.75rem; text-align: center; }
  .stat-card .num { font-size: 1.4rem; font-weight: 700; color: #00ff88; display: block; }
  .stat-card .lbl { font-size: 10px; color: #7d8590; margin-top: 2px; }
  .project { background: #161b22; border: 1px solid #21262d; border-radius: 6px; padding: 0.85rem; margin-bottom: 8px; display: flex; justify-content: space-between; align-items: flex-start; }
  .project-name { color: #58a6ff; font-size: 0.82rem; font-weight: 600; }
  .project-desc { color: #7d8590; font-size: 0.7rem; margin-top: 3px; }
  .project-tag { background: #0d1117; border: 1px solid #30363d; border-radius: 10px; font-size: 10px; color: #8b949e; padding: 2px 8px; white-space: nowrap; }
  .terminal { background: #010409; border: 1px solid #21262d; border-radius: 6px; padding: 1rem; font-size: 11px; }
  .terminal .prompt { color: #00ff88; }
  .terminal .cmd { color: #e6edf3; }
  .terminal .out { color: #7d8590; margin-left: 1rem; }
  .footer { text-align: center; padding: 1rem; border-top: 1px solid #21262d; color: #7d8590; font-size: 10px; }
  .footer span { color: #00ff88; }
</style>

<div class="container">
  <div class="hero">
    <code class="ascii">
 ██████╗ ██╗     ██╗██╗   ██╗███████╗██████╗ 
██╔═══██╗██║     ██║██║   ██║██╔════╝██╔══██╗
██║   ██║██║     ██║██║   ██║█████╗  ██████╔╝
██║   ██║██║     ██║╚██╗ ██╔╝██╔══╝  ██╔══██╗
╚██████╔╝███████╗██║ ╚████╔╝ ███████╗██║  ██║
 ╚═════╝ ╚══════╝╚═╝  ╚═══╝  ╚══════╝╚═╝  ╚═╝</code>
    <h1>Hey, I'm <span>Oliver</span> 👋</h1>
    <p style="color: #7d8590; font-size: 0.82rem; margin: 0.5rem 0;">
      <span class="prompt">&gt; </span><span class="typing">Junior Python Developer — Madrid, Spain 🇪🇸</span>
    </p>
    <div class="badges">
      <span class="badge green">🟢 Open to Work</span>
      <span class="badge blue">Python</span>
      <span class="badge blue">REST APIs</span>
      <span class="badge purple">Automation</span>
      <span class="badge purple">Trading Bots</span>
    </div>
  </div>

  <div class="section">
    <div class="section-title">about.py</div>
    <div class="terminal">
      <div><span class="prompt">$ </span><span class="cmd">python3 oliver.py --info</span></div>
      <div class="out">📍 Location   → Madrid, Spain</div>
      <div class="out">💼 Role       → Junior Python Developer</div>
      <div class="out">🎯 Focus      → Automation · REST APIs · Backend</div>
      <div class="out">🤖 Currently  → Building trading bots for IQ Option</div>
      <div class="out">📬 Contact    → oliveljimenes@gmail.com</div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">tech_stack.json</div>
    <div class="skills-grid">
      <div class="skill-chip">🐍 Python</div>
      <div class="skill-chip">🔗 REST APIs</div>
      <div class="skill-chip">🐙 Git & GitHub</div>
      <div class="skill-chip">🐧 Linux</div>
      <div class="skill-chip">🤖 Automation</div>
      <div class="skill-chip">📡 Telegram API</div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">certifications[]</div>
    <div class="grid-2">
      <div class="card"><span class="card-dot"></span><span class="card-title">Python</span><div class="card-sub">Core & Advanced</div></div>
      <div class="card"><span class="card-dot blue"></span><span class="card-title">Git & GitHub</span><div class="card-sub">Version Control</div></div>
      <div class="card"><span class="card-dot yellow"></span><span class="card-title">Advanced Python</span><div class="card-sub">OOP · Async · APIs</div></div>
      <div class="card"><span class="card-dot"></span><span class="card-title">Linux & Terminal</span><div class="card-sub">Shell Scripting</div></div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">featured_projects/</div>
    <div class="project">
      <div>
        <div class="project-name">🤖 TeamBinari_Bot</div>
        <div class="project-desc">Trading signal bot with Telegram alerts — multi-asset monitoring via threading</div>
      </div>
      <span class="project-tag">Python</span>
    </div>
    <div class="project">
      <div>
        <div class="project-name">📈 Binary IQOption Automation</div>
        <div class="project-desc">Automated signal detection for IQ Option with breakout/resistance strategy</div>
      </div>
      <span class="project-tag">IQ Option API</span>
    </div>
  </div>

  <div class="footer">
    <p>Built with <span>{'<3'}</span> and Python · <span>@OLIVER26GOLDEN</span></p>
  </div>
</div>
