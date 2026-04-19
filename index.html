<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Supriya Kadam — Data Scientist</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Space+Mono:wght@400;700&family=Syne:wght@400;700;800&display=swap');

  :root {
    --bg: #06000f;
    --surface: #0f0020;
    --border: rgba(192,132,252,0.15);
    --accent: #c084fc;
    --accent2: #a855f7;
    --accent3: #7c3aed;
    --white: #f5f0ff;
    --muted: #9d8cbb;
    --glow: rgba(192,132,252,0.3);
  }

  * { margin:0; padding:0; box-sizing:border-box; }
  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--white);
    font-family: 'Space Grotesk', sans-serif;
    overflow-x: hidden;
  }

  /* ── CANVAS ── */
  #canvas-bg {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    z-index: 0;
    pointer-events: none;
  }

  /* ── NAV ── */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    padding: 1.2rem 3rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid var(--border);
    backdrop-filter: blur(20px);
    background: rgba(6,0,15,0.6);
  }
  .nav-logo {
    font-family: 'Space Mono', monospace;
    font-size: 0.85rem;
    color: var(--accent);
    letter-spacing: 3px;
    text-transform: uppercase;
  }
  .nav-links { display: flex; gap: 2rem; }
  .nav-links a {
    color: var(--muted);
    text-decoration: none;
    font-size: 0.85rem;
    letter-spacing: 1px;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--white); }

  /* ── SECTIONS ── */
  section {
    position: relative;
    z-index: 10;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .container { max-width: 1100px; margin: 0 auto; padding: 0 3rem; }

  /* ── HERO ── */
  #hero {
    align-items: flex-start;
    padding-top: 6rem;
  }
  .hero-tag {
    font-family: 'Space Mono', monospace;
    font-size: 0.7rem;
    color: var(--accent);
    letter-spacing: 4px;
    text-transform: uppercase;
    margin-bottom: 1.5rem;
    opacity: 0;
  }
  .hero-name {
    font-family: 'Syne', sans-serif;
    font-size: clamp(3.5rem, 9vw, 7rem);
    font-weight: 800;
    line-height: 0.95;
    color: var(--white);
    margin-bottom: 1.5rem;
    opacity: 0;
  }
  .hero-name em {
    font-style: normal;
    background: linear-gradient(135deg, var(--accent), #e879f9);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }
  .hero-desc {
    font-size: 1.1rem;
    color: var(--muted);
    max-width: 520px;
    line-height: 1.8;
    margin-bottom: 2.5rem;
    opacity: 0;
  }
  .hero-btns {
    display: flex;
    gap: 1rem;
    opacity: 0;
  }
  .btn-primary {
    background: var(--accent);
    color: #06000f;
    padding: 0.8rem 2rem;
    border-radius: 4px;
    font-weight: 600;
    font-size: 0.88rem;
    text-decoration: none;
    letter-spacing: 0.5px;
    transition: all 0.2s;
    border: none;
    cursor: pointer;
  }
  .btn-primary:hover { background: #d946ef; transform: translateY(-2px); }
  .btn-outline {
    border: 1px solid var(--border);
    color: var(--white);
    padding: 0.8rem 2rem;
    border-radius: 4px;
    font-size: 0.88rem;
    text-decoration: none;
    letter-spacing: 0.5px;
    transition: all 0.2s;
    backdrop-filter: blur(8px);
    background: rgba(192,132,252,0.05);
  }
  .btn-outline:hover { border-color: var(--accent); background: rgba(192,132,252,0.1); }

  .hero-stats {
    position: absolute;
    right: 3rem;
    bottom: 4rem;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    opacity: 0;
  }
  .stat-item { text-align: right; }
  .stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 2.2rem;
    font-weight: 800;
    color: var(--white);
    line-height: 1;
  }
  .stat-num span { color: var(--accent); }
  .stat-label {
    font-size: 0.7rem;
    color: var(--muted);
    letter-spacing: 2px;
    text-transform: uppercase;
  }

  /* ── AWARD BANNER ── */
  .award-strip {
    background: linear-gradient(135deg, rgba(192,132,252,0.08), rgba(124,58,237,0.05));
    border: 1px solid rgba(192,132,252,0.25);
    border-radius: 8px;
    padding: 1.2rem 1.8rem;
    display: flex;
    align-items: center;
    gap: 1.5rem;
    margin-bottom: 3rem;
    opacity: 0;
  }
  .award-flag { font-size: 2rem; }
  .award-body { flex: 1; }
  .award-title {
    font-family: 'Space Mono', monospace;
    font-size: 0.65rem;
    letter-spacing: 3px;
    color: var(--accent);
    text-transform: uppercase;
    margin-bottom: 4px;
  }
  .award-text { font-size: 0.95rem; color: var(--white); line-height: 1.5; }
  .award-text strong { color: var(--accent); }
  .award-pill {
    background: rgba(192,132,252,0.15);
    border: 1px solid rgba(192,132,252,0.4);
    color: var(--accent);
    font-family: 'Space Mono', monospace;
    font-size: 0.6rem;
    padding: 4px 10px;
    border-radius: 20px;
    letter-spacing: 1px;
    white-space: nowrap;
  }

  /* ── SECTION TITLES ── */
  .sec-label {
    font-family: 'Space Mono', monospace;
    font-size: 0.65rem;
    color: var(--accent);
    letter-spacing: 4px;
    text-transform: uppercase;
    margin-bottom: 0.5rem;
  }
  .sec-title {
    font-family: 'Syne', sans-serif;
    font-size: clamp(2rem, 4vw, 3rem);
    font-weight: 800;
    color: var(--white);
    margin-bottom: 3rem;
    line-height: 1.1;
  }

  /* ── HACKATHON TABLE ── */
  #hackathons { padding: 6rem 0; }
  .hof-grid { display: flex; flex-direction: column; gap: 1px; border: 1px solid var(--border); border-radius: 8px; overflow: hidden; }
  .hof-row {
    display: grid;
    grid-template-columns: 3rem 1fr 8rem 1fr;
    align-items: center;
    gap: 1.5rem;
    padding: 1.2rem 1.5rem;
    background: rgba(15,0,32,0.6);
    border-bottom: 1px solid var(--border);
    transition: background 0.2s;
    opacity: 0;
  }
  .hof-row:last-child { border: none; }
  .hof-row:hover { background: rgba(192,132,252,0.06); }
  .hof-medal { font-size: 1.4rem; text-align: center; }
  .hof-name { font-size: 0.95rem; font-weight: 600; color: var(--white); }
  .hof-org { font-size: 0.75rem; color: var(--muted); margin-top: 2px; }
  .hof-badge {
    font-family: 'Space Mono', monospace;
    font-size: 0.62rem;
    padding: 4px 10px;
    border-radius: 3px;
    text-align: center;
    letter-spacing: 1px;
  }
  .badge-win { background: rgba(192,132,252,0.15); border: 1px solid rgba(192,132,252,0.4); color: var(--accent); }
  .badge-run { background: rgba(124,58,237,0.12); border: 1px solid rgba(124,58,237,0.3); color: #a78bfa; }
  .badge-jdg { background: rgba(236,72,153,0.08); border: 1px solid rgba(236,72,153,0.2); color: #f9a8d4; }
  .hof-stack { font-size: 0.72rem; color: var(--muted); line-height: 1.6; }

  /* ── PROJECTS ── */
  #projects { padding: 6rem 0; }
  .proj-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1.5rem; }
  .proj-card {
    background: rgba(15,0,32,0.7);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 1.8rem;
    transition: all 0.3s;
    opacity: 0;
    position: relative;
    overflow: hidden;
  }
  .proj-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--accent), transparent);
    opacity: 0;
    transition: opacity 0.3s;
  }
  .proj-card:hover { border-color: rgba(192,132,252,0.35); transform: translateY(-4px); }
  .proj-card:hover::before { opacity: 1; }
  .proj-num {
    font-family: 'Space Mono', monospace;
    font-size: 0.6rem;
    color: rgba(192,132,252,0.4);
    letter-spacing: 2px;
    margin-bottom: 0.5rem;
  }
  .proj-name { font-size: 1.05rem; font-weight: 700; color: var(--white); margin-bottom: 0.7rem; }
  .proj-desc { font-size: 0.83rem; color: var(--muted); line-height: 1.8; margin-bottom: 1rem; }
  .proj-tags { display: flex; flex-wrap: wrap; gap: 5px; }
  .proj-tag {
    background: rgba(192,132,252,0.08);
    border: 1px solid rgba(192,132,252,0.2);
    color: var(--accent);
    font-family: 'Space Mono', monospace;
    font-size: 0.58rem;
    padding: 3px 8px;
    border-radius: 3px;
    letter-spacing: 0.5px;
  }

  /* ── STACK ── */
  #stack { padding: 6rem 0; }
  .stack-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 2rem; }
  .stack-col { opacity: 0; }
  .stack-cat {
    font-family: 'Space Mono', monospace;
    font-size: 0.62rem;
    color: var(--accent);
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 1rem;
    padding-bottom: 0.5rem;
    border-bottom: 1px solid var(--border);
  }
  .skill-item {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 0.5rem 0;
    border-bottom: 1px solid rgba(192,132,252,0.05);
  }
  .skill-name { font-size: 0.82rem; color: var(--white); flex: 1; }
  .skill-bar { width: 80px; height: 3px; background: rgba(192,132,252,0.1); border-radius: 2px; overflow: hidden; }
  .skill-fill { height: 100%; background: linear-gradient(90deg, var(--accent3), var(--accent)); border-radius: 2px; width: 0; transition: width 1.2s cubic-bezier(0.4,0,0.2,1); }

  /* ── FOOTER ── */
  footer {
    position: relative;
    z-index: 10;
    border-top: 1px solid var(--border);
    padding: 3rem;
    text-align: center;
  }
  .footer-name {
    font-family: 'Syne', sans-serif;
    font-size: 1.5rem;
    font-weight: 800;
    color: var(--white);
    margin-bottom: 0.5rem;
  }
  .footer-tagline { font-size: 0.8rem; color: var(--muted); margin-bottom: 1.5rem; letter-spacing: 1px; }
  .footer-links { display: flex; gap: 1rem; justify-content: center; }
  .footer-link {
    border: 1px solid var(--border);
    color: var(--muted);
    padding: 0.5rem 1.2rem;
    border-radius: 4px;
    font-size: 0.78rem;
    text-decoration: none;
    transition: all 0.2s;
    font-family: 'Space Mono', monospace;
  }
  .footer-link:hover { border-color: var(--accent); color: var(--accent); }

  /* ── SCROLL LINE ── */
  .scroll-line {
    position: fixed;
    top: 0; left: 0;
    width: 0%;
    height: 2px;
    background: linear-gradient(90deg, var(--accent3), var(--accent), #e879f9);
    z-index: 200;
    transition: width 0.1s linear;
  }

  /* 3D object canvas */
  #hero-3d {
    position: absolute;
    right: 3rem;
    top: 50%;
    transform: translateY(-50%);
    width: 320px;
    height: 320px;
    opacity: 0;
    pointer-events: none;
  }
</style>
</head>
<body>

<div class="scroll-line" id="scrollLine"></div>
<canvas id="canvas-bg"></canvas>

<nav>
  <div class="nav-logo">SK // 2026</div>
  <div class="nav-links">
    <a href="#hero">Home</a>
    <a href="#hackathons">Wins</a>
    <a href="#projects">Projects</a>
    <a href="#stack">Stack</a>
    <a href="mailto:skadam12@umd.edu">Contact</a>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="container" style="position:relative; width:100%; max-width:1100px; margin:0 auto; padding:0 3rem;">
    <div class="hero-tag">Data Scientist · ML Engineer · GenAI Builder</div>
    <div class="hero-name">Supriya<br/><em>Kadam.</em></div>
    <div class="hero-desc">
      MS Data Science @ UMD · 3× Hackathon Winner · Government of India Scholar ·
      Building multi-agent AI systems, RAG pipelines, and production ML at Connyct.
    </div>
    <div class="award-strip">
      <div class="award-flag">🏅</div>
      <div class="award-body">
        <div class="award-title">Government of India — National Scholarship</div>
        <div class="award-text">Awarded by the <strong>Education Minister of India</strong> · MS at University of Maryland fully sponsored by the Indian Government 🇮🇳</div>
      </div>
      <div class="award-pill">ICCR SCHOLAR</div>
    </div>
    <div class="hero-btns">
      <a href="#projects" class="btn-primary">View Projects</a>
      <a href="https://linkedin.com/in/supriya-kadam11" class="btn-outline" target="_blank">LinkedIn ↗</a>
    </div>
    <div class="hero-stats">
      <div class="stat-item">
        <div class="stat-num">3<span>×</span></div>
        <div class="stat-label">Hackathon Wins</div>
      </div>
      <div class="stat-item">
        <div class="stat-num">3<span>+</span></div>
        <div class="stat-label">Years Industry</div>
      </div>
      <div class="stat-item">
        <div class="stat-num">3.7</div>
        <div class="stat-label">MS GPA / 4.0</div>
      </div>
    </div>
    <canvas id="hero-3d"></canvas>
  </div>
</section>

<!-- HACKATHONS -->
<section id="hackathons">
  <div class="container">
    <div class="sec-label">// Track Record</div>
    <div class="sec-title">Hall of Fame</div>
    <div class="hof-grid">
      <div class="hof-row">
        <div class="hof-medal">🥇</div>
        <div><div class="hof-name">HOF Hacks — HOF Capital & Tech at NYU</div><div class="hof-org">Feb 2026</div></div>
        <div class="hof-badge badge-win">WINNER</div>
        <div class="hof-stack">Nemotron · Databricks · RAG · FastAPI · MediaPipe · Claude SDK</div>
      </div>
      <div class="hof-row">
        <div class="hof-medal">🥇</div>
        <div><div class="hof-name">Technica 2025 — T. Rowe Price Investor Challenge</div><div class="hof-org">Dec 2025</div></div>
        <div class="hof-badge badge-win">WINNER</div>
        <div class="hof-stack">LLM Fine-Tuning · NLP · RAG · Vector Embeddings · Semantic Search</div>
      </div>
      <div class="hof-row">
        <div class="hof-medal">🥇</div>
        <div><div class="hof-name">CAFB — AI for the Underserved</div><div class="hof-org">Apr 2025</div></div>
        <div class="hof-badge badge-win">WINNER</div>
        <div class="hof-stack">Kafka · AWS Lambda · DynamoDB · Twilio · TTS · Speech-to-Text</div>
      </div>
      <div class="hof-row">
        <div class="hof-medal">🥈</div>
        <div><div class="hof-name">Knight Hacks VIII — ServiceNow AI Challenge</div><div class="hof-org">Nov 2025</div></div>
        <div class="hof-badge badge-run">RUNNER-UP</div>
        <div class="hof-stack">Sentence Transformers · UMAP · HDBSCAN · Multi-Agent · MCP</div>
      </div>
      <div class="hof-row">
        <div class="hof-medal">⚖️</div>
        <div><div class="hof-name">MDC Data & AI Hackathon — University of Michigan</div><div class="hof-org">Mar 2026</div></div>
        <div class="hof-badge badge-jdg">JUDGE</div>
        <div class="hof-stack">—</div>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="container">
    <div class="sec-label">// Featured Work</div>
    <div class="sec-title">Projects</div>
    <div class="proj-grid">
      <div class="proj-card">
        <div class="proj-num">PROJ-001</div>
        <div class="proj-name">⚖️ Multi-Agent Legal Simulator</div>
        <div class="proj-desc">Fine-tuned NVIDIA Nemotron on legal corpora. RAG pipeline over Federal Rules of Evidence for real-time compliance detection. Orchestrated 4 agents via Claude SDK. Galileo.ai eval across facial, audio & transcript signals.</div>
        <div class="proj-tags">
          <span class="proj-tag">Nemotron</span><span class="proj-tag">RAG</span><span class="proj-tag">Claude SDK</span><span class="proj-tag">MediaPipe</span><span class="proj-tag">FastAPI</span><span class="proj-tag">Databricks</span>
        </div>
      </div>
      <div class="proj-card">
        <div class="proj-num">PROJ-002</div>
        <div class="proj-name">📈 Financial Education Platform</div>
        <div class="proj-desc">NLP sentiment pipeline on SEC EDGAR + Alpha Vantage market data. Feature engineering and ML models for personalized lesson sequencing. Validated across 3 retraining cycles in a compliance-aware multilingual beta.</div>
        <div class="proj-tags">
          <span class="proj-tag">scikit-learn</span><span class="proj-tag">NLP</span><span class="proj-tag">SEC EDGAR</span><span class="proj-tag">Alpha Vantage</span><span class="proj-tag">Recharts</span>
        </div>
      </div>
      <div class="proj-card">
        <div class="proj-num">PROJ-003</div>
        <div class="proj-name">🧠 Retina Connectomics Research</div>
        <div class="proj-desc">Preprocessing 10K+ neural annotation exports from connectomics datasets. PCA-based orientation relationships across 500+ neuron skeleton files to quantify inter-layer connectivity patterns at UMD.</div>
        <div class="proj-tags">
          <span class="proj-tag">Python</span><span class="proj-tag">scikit-image</span><span class="proj-tag">NumPy</span><span class="proj-tag">Matplotlib</span><span class="proj-tag">R</span>
        </div>
      </div>
      <div class="proj-card">
        <div class="proj-num">PROJ-004</div>
        <div class="proj-name">🔍 Enterprise Demand Intelligence</div>
        <div class="proj-desc">Multi-agent demand analysis using Sentence Transformers, UMAP, HDBSCAN and LLM-driven semantic routing. Continuous agent reasoning loops via Google ADK and Model Context Protocol.</div>
        <div class="proj-tags">
          <span class="proj-tag">Google ADK</span><span class="proj-tag">MCP</span><span class="proj-tag">UMAP</span><span class="proj-tag">HDBSCAN</span><span class="proj-tag">Sentence Transformers</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- STACK -->
<section id="stack">
  <div class="container">
    <div class="sec-label">// Capabilities</div>
    <div class="sec-title">Tech Stack</div>
    <div class="stack-grid">
      <div class="stack-col">
        <div class="stack-cat">Languages</div>
        <div class="skill-item"><span class="skill-name">Python</span><div class="skill-bar"><div class="skill-fill" data-w="95"></div></div></div>
        <div class="skill-item"><span class="skill-name">SQL</span><div class="skill-bar"><div class="skill-fill" data-w="90"></div></div></div>
        <div class="skill-item"><span class="skill-name">R</span><div class="skill-bar"><div class="skill-fill" data-w="80"></div></div></div>
        <div class="skill-item"><span class="skill-name">Scala</span><div class="skill-bar"><div class="skill-fill" data-w="65"></div></div></div>
        <div class="skill-item"><span class="skill-name">Bash</span><div class="skill-bar"><div class="skill-fill" data-w="70"></div></div></div>
        <div class="skill-item"><span class="skill-name">MATLAB</span><div class="skill-bar"><div class="skill-fill" data-w="60"></div></div></div>
      </div>
      <div class="stack-col">
        <div class="stack-cat">GenAI & ML</div>
        <div class="skill-item"><span class="skill-name">LLM Fine-Tuning</span><div class="skill-bar"><div class="skill-fill" data-w="90"></div></div></div>
        <div class="skill-item"><span class="skill-name">RAG Pipelines</span><div class="skill-bar"><div class="skill-fill" data-w="95"></div></div></div>
        <div class="skill-item"><span class="skill-name">Multi-Agent / MCP</span><div class="skill-bar"><div class="skill-fill" data-w="88"></div></div></div>
        <div class="skill-item"><span class="skill-name">PyTorch</span><div class="skill-bar"><div class="skill-fill" data-w="80"></div></div></div>
        <div class="skill-item"><span class="skill-name">XGBoost / SHAP</span><div class="skill-bar"><div class="skill-fill" data-w="85"></div></div></div>
        <div class="skill-item"><span class="skill-name">NLP / Transformers</span><div class="skill-bar"><div class="skill-fill" data-w="88"></div></div></div>
      </div>
      <div class="stack-col">
        <div class="stack-cat">Cloud & Data</div>
        <div class="skill-item"><span class="skill-name">AWS</span><div class="skill-bar"><div class="skill-fill" data-w="82"></div></div></div>
        <div class="skill-item"><span class="skill-name">GCP / Azure</span><div class="skill-bar"><div class="skill-fill" data-w="75"></div></div></div>
        <div class="skill-item"><span class="skill-name">Spark / PySpark</span><div class="skill-bar"><div class="skill-fill" data-w="80"></div></div></div>
        <div class="skill-item"><span class="skill-name">Kafka / Airflow</span><div class="skill-bar"><div class="skill-fill" data-w="78"></div></div></div>
        <div class="skill-item"><span class="skill-name">Docker / K8s</span><div class="skill-bar"><div class="skill-fill" data-w="72"></div></div></div>
        <div class="skill-item"><span class="skill-name">Power BI / Tableau</span><div class="skill-bar"><div class="skill-fill" data-w="88"></div></div></div>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="footer-name">Supriya Kadam</div>
  <div class="footer-tagline">She is not just in the room. She built the model that runs it.</div>
  <div class="footer-links">
    <a href="https://linkedin.com/in/supriya-kadam11" class="footer-link" target="_blank">LinkedIn ↗</a>
    <a href="https://github.com/skadam1199" class="footer-link" target="_blank">GitHub ↗</a>
    <a href="mailto:skadam12@umd.edu" class="footer-link">Email ↗</a>
  </div>
</footer>

<script>
// ── SCROLL PROGRESS LINE ──
window.addEventListener('scroll', () => {
  const pct = (window.scrollY / (document.body.scrollHeight - window.innerHeight)) * 100;
  document.getElementById('scrollLine').style.width = pct + '%';
});

// ── THREE.JS PARTICLE FIELD (background) ──
(function() {
  const canvas = document.getElementById('canvas-bg');
  const renderer = new THREE.WebGLRenderer({ canvas, alpha: true, antialias: true });
  renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
  renderer.setSize(window.innerWidth, window.innerHeight);

  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
  camera.position.z = 30;

  // Particles
  const N = 1800;
  const geo = new THREE.BufferGeometry();
  const pos = new Float32Array(N * 3);
  const col = new Float32Array(N * 3);
  for (let i = 0; i < N; i++) {
    pos[i*3]   = (Math.random() - 0.5) * 120;
    pos[i*3+1] = (Math.random() - 0.5) * 80;
    pos[i*3+2] = (Math.random() - 0.5) * 60;
    const t = Math.random();
    col[i*3]   = 0.47 + t * 0.2;
    col[i*3+1] = 0.2  + t * 0.1;
    col[i*3+2] = 0.85 + t * 0.1;
  }
  geo.setAttribute('position', new THREE.BufferAttribute(pos, 3));
  geo.setAttribute('color', new THREE.BufferAttribute(col, 3));
  const mat = new THREE.PointsMaterial({ size: 0.18, vertexColors: true, transparent: true, opacity: 0.55 });
  const points = new THREE.Points(geo, mat);
  scene.add(points);

  // Wireframe torus knot (floating geometric)
  const torusGeo = new THREE.TorusKnotGeometry(6, 1.4, 120, 16);
  const torusMat = new THREE.MeshBasicMaterial({ color: 0xc084fc, wireframe: true, transparent: true, opacity: 0.12 });
  const torus = new THREE.Mesh(torusGeo, torusMat);
  torus.position.set(18, 0, -10);
  scene.add(torus);

  let mx = 0, my = 0;
  document.addEventListener('mousemove', e => {
    mx = (e.clientX / window.innerWidth  - 0.5) * 2;
    my = (e.clientY / window.innerHeight - 0.5) * 2;
  });

  function animate() {
    requestAnimationFrame(animate);
    const t = Date.now() * 0.0003;
    points.rotation.y = t * 0.08 + mx * 0.03;
    points.rotation.x = t * 0.04 - my * 0.02;
    torus.rotation.x = t * 0.4;
    torus.rotation.y = t * 0.3;
    renderer.render(scene, camera);
  }
  animate();

  window.addEventListener('resize', () => {
    camera.aspect = window.innerWidth / window.innerHeight;
    camera.updateProjectionMatrix();
    renderer.setSize(window.innerWidth, window.innerHeight);
  });
})();

// ── THREE.JS HERO 3D SPHERE ──
(function() {
  const canvas = document.getElementById('hero-3d');
  if (!canvas) return;
  const renderer = new THREE.WebGLRenderer({ canvas, alpha: true, antialias: true });
  renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
  renderer.setSize(320, 320);

  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(50, 1, 0.1, 100);
  camera.position.z = 5;

  // Icosahedron wireframe
  const icoGeo = new THREE.IcosahedronGeometry(1.8, 3);
  const icoMat = new THREE.MeshBasicMaterial({ color: 0xa855f7, wireframe: true, transparent: true, opacity: 0.5 });
  const ico = new THREE.Mesh(icoGeo, icoMat);
  scene.add(ico);

  // Inner glowing sphere
  const sphereGeo = new THREE.SphereGeometry(1.2, 32, 32);
  const sphereMat = new THREE.MeshBasicMaterial({ color: 0x2a0040, transparent: true, opacity: 0.85 });
  const sphere = new THREE.Mesh(sphereGeo, sphereMat);
  scene.add(sphere);

  // Ring
  const ringGeo = new THREE.TorusGeometry(2.2, 0.02, 8, 80);
  const ringMat = new THREE.MeshBasicMaterial({ color: 0xc084fc, transparent: true, opacity: 0.35 });
  const ring = new THREE.Mesh(ringGeo, ringMat);
  ring.rotation.x = Math.PI / 3;
  scene.add(ring);

  // Orbiting dots
  const orbitGroup = new THREE.Group();
  for (let i = 0; i < 6; i++) {
    const dotGeo = new THREE.SphereGeometry(0.06, 8, 8);
    const dotMat = new THREE.MeshBasicMaterial({ color: 0xe879f9 });
    const dot = new THREE.Mesh(dotGeo, dotMat);
    const angle = (i / 6) * Math.PI * 2;
    dot.position.set(Math.cos(angle) * 2.2, Math.sin(angle) * 0.8, Math.sin(angle) * 1.6);
    orbitGroup.add(dot);
  }
  scene.add(orbitGroup);

  function animate() {
    requestAnimationFrame(animate);
    const t = Date.now() * 0.001;
    ico.rotation.y = t * 0.4;
    ico.rotation.x = t * 0.15;
    ring.rotation.z = t * 0.3;
    orbitGroup.rotation.y = t * 0.6;
    renderer.render(scene, camera);
  }
  animate();
})();

// ── GSAP ANIMATIONS ──
gsap.registerPlugin(ScrollTrigger);

// Hero entrance
gsap.timeline({ delay: 0.3 })
  .to('.hero-tag',   { opacity: 1, y: 0, duration: 0.7, ease: 'power3.out' }, 0)
  .from('.hero-tag', { y: 20 }, 0)
  .to('.hero-name',  { opacity: 1, y: 0, duration: 0.8, ease: 'power3.out' }, 0.15)
  .from('.hero-name', { y: 40 }, 0.15)
  .to('.hero-desc',  { opacity: 1, y: 0, duration: 0.7, ease: 'power3.out' }, 0.3)
  .from('.hero-desc', { y: 20 }, 0.3)
  .to('.award-strip',{ opacity: 1, y: 0, duration: 0.7, ease: 'power3.out' }, 0.45)
  .from('.award-strip', { y: 20 }, 0.45)
  .to('.hero-btns',  { opacity: 1, y: 0, duration: 0.6, ease: 'power3.out' }, 0.55)
  .from('.hero-btns', { y: 15 }, 0.55)
  .to('.hero-stats', { opacity: 1, duration: 0.8, ease: 'power3.out' }, 0.6)
  .to('#hero-3d',    { opacity: 1, duration: 1.2, ease: 'power3.out' }, 0.5);

// Hackathon rows
gsap.utils.toArray('.hof-row').forEach((row, i) => {
  gsap.to(row, {
    opacity: 1, x: 0, duration: 0.6, ease: 'power3.out',
    scrollTrigger: { trigger: row, start: 'top 85%' },
    delay: i * 0.08
  });
  gsap.from(row, {
    x: -30,
    scrollTrigger: { trigger: row, start: 'top 85%' },
    delay: i * 0.08,
    duration: 0.6
  });
});

// Project cards
gsap.utils.toArray('.proj-card').forEach((card, i) => {
  gsap.to(card, {
    opacity: 1, y: 0, duration: 0.7, ease: 'power3.out',
    scrollTrigger: { trigger: card, start: 'top 88%' },
    delay: i * 0.1
  });
  gsap.from(card, {
    y: 30,
    scrollTrigger: { trigger: card, start: 'top 88%' },
    delay: i * 0.1,
    duration: 0.7
  });
});

// Stack columns
gsap.utils.toArray('.stack-col').forEach((col, i) => {
  gsap.to(col, {
    opacity: 1, duration: 0.7,
    scrollTrigger: {
      trigger: col, start: 'top 85%',
      onEnter: () => {
        col.querySelectorAll('.skill-fill').forEach(bar => {
          bar.style.width = bar.dataset.w + '%';
        });
      }
    },
    delay: i * 0.15
  });
});
</script>
</body>
</html>
