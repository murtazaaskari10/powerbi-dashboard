<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Murtaza Askari — Dashboard Portfolio</title>
  <meta name="description" content="Power BI & analytics dashboards by Murtaza Askari." />
  <meta property="og:title" content="Murtaza Askari — Dashboard Portfolio" />
  <meta property="og:description" content="Power BI & analytics dashboards by Murtaza Askari." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://avatars.githubusercontent.com/u/000?v=4" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0b0e14;
      --card: #121722;
      --text: #e8eefc;
      --muted: #9fb0d8;
      --brand: #ff9900;
      --accent: #d4af37;
      --ring: rgba(255,153,0,.35);
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0; font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      background: radial-gradient(1200px 600px at 20% -10%, rgba(255,153,0,.08), transparent 60%),
                  radial-gradient(1200px 600px at 120% 10%, rgba(212,175,55,.08), transparent 60%),
                  var(--bg);
      color: var(--text);
    }
    .container { max-width: 1100px; margin: 0 auto; padding: 24px; }
    header { display:flex; align-items:center; justify-content:space-between; gap:16px; }
    .brand { display:flex; align-items:center; gap:10px; text-decoration:none; color:var(--text); }
    .logo { width:42px; height:42px; border-radius:12px; background: linear-gradient(135deg, var(--brand), var(--accent)); box-shadow: 0 8px 24px rgba(255,153,0,.25); }
    .brand h1 { font-size: 18px; margin:0; font-weight:700; letter-spacing:.2px; }
    .nav a { color: var(--muted); text-decoration:none; margin-left:16px; font-weight:500; }
    .nav a:hover { color: var(--text); }
    .hero { margin-top: 48px; display:grid; grid-template-columns: 1.2fr 1fr; gap:28px; align-items:center; }
    .hero h2 { font-size: 40px; line-height: 1.1; margin: 0 0 12px; }
    .hero p { color: var(--muted); margin: 0 0 22px; font-size: 18px; }
    .cta { display:flex; gap:12px; flex-wrap:wrap; }
    .btn { display:inline-flex; align-items:center; gap:10px; padding:12px 16px; border-radius:12px; text-decoration:none; font-weight:600; border:1px solid transparent; }
    .btn-primary { background: linear-gradient(135deg, var(--brand), var(--accent)); color:#1b1203; box-shadow: 0 10px 24px var(--ring); }
    .btn-ghost { color: var(--text); border-color: rgba(255,255,255,.14); }
    .badge { display:inline-block; padding:6px 10px; border-radius:999px; background:rgba(212,175,55,.12); color:#f8e6a7; font-weight:600; font-size:12px; border:1px solid rgba(212,175,55,.28); }
    .card { background: linear-gradient(180deg, rgba(255,255,255,.02), transparent 40%), var(--card); border: 1px solid rgba(255,255,255,.08); border-radius: 16px; padding: 18px; position: relative; overflow:hidden; }
    .grid { display:grid; grid-template-columns: repeat(12, 1fr); gap: 18px; }
    .span-4 { grid-column: span 4; }
    .span-12 { grid-column: span 12; }
    .thumb { width:100%; aspect-ratio: 16/9; border-radius:12px; background:#0f1320; display:block; border:1px solid rgba(255,255,255,.08); }
    .meta { color: var(--muted); font-size: 14px; margin-top: 6px; }
    .title { font-size: 18px; font-weight:700; margin: 10px 0 6px; }
    .actions { display:flex; gap:10px; margin-top: 10px; flex-wrap:wrap; }
    .embed-wrap { border-radius: 16px; overflow: hidden; border:1px solid rgba(255,255,255,.1); }
    iframe { width:100%; height: 520px; border:0; background:#0f1320; }
    footer { margin: 48px 0 16px; color: var(--muted); font-size: 14px; text-align:center; }
    .small { font-size: 13px; color: var(--muted); }
    @media (max-width: 960px) {
      .hero { grid-template-columns: 1fr; }
      .span-4 { grid-column: span 12; }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <a class="brand" href="#">
        <div class="logo" aria-hidden="true"></div>
        <h1>Murtaza Askari</h1>
      </a>
      <nav class="nav">
        <a href="#projects">Projects</a>
        <a href="#live">Live Demo</a>
        <a href="https://github.com/your-username" target="_blank" rel="noopener">GitHub</a>
      </nav>
    </header>

    <section class="hero card">
      <div>
        <span class="badge">Power BI • Analytics • eCommerce</span>
        <h2>Dashboards that turn data into action.</h2>
        <p>Curated selection of my dashboards: Amazon KPIs, Marketing Attribution, and Ops Inventory. Each project includes a short case study, screenshots, and links to source files on GitHub.</p>
        <div class="cta">
          <a class="btn btn-primary" href="#live">View Live Demo</a>
          <a class="btn btn-ghost" href="https://github.com/your-username/dashboard-portfolio" target="_blank" rel="noopener">View on GitHub</a>
        </div>
      </div>
      <div class="card">
        <img class="thumb" src="https://images.unsplash.com/photo-1551281044-8fa16de3db50?q=80&w=1200&auto=format&fit=crop" alt="Dashboard preview" />
        <div class="meta small">Sample hero image — replace with your own screenshot (projects/01 cover.png)</div>
      </div>
    </section>

    <h3 id="projects" style="margin:32px 0 8px;">Projects</h3>
    <div class="grid">
      <article class="card span-4">
        <img class="thumb" src="https://images.unsplash.com/photo-1556767576-cfba2cdbba59?q=80&w=1200&auto=format&fit=crop" alt="Amazon KPI" />
        <div class="title">Amazon KPI Command Center</div>
        <div class="meta">Sales, Units, Buy Box%, CVR, TACoS, Margin. Drilldowns & diagnostics.</div>
        <div class="actions">
          <a class="btn btn-primary" href="#live">Live</a>
          <a class="btn btn-ghost" href="https://github.com/your-username/dashboard-portfolio/tree/main/projects/01-amazon-kpis" target="_blank" rel="noopener">Case Study</a>
        </div>
      </article>
    </div>

    <h3 id="live" style="margin:32px 0 8px;">Live Demo (Power BI)</h3>
    <p class="small">If you used <em>Publish to web</em>, paste your embed link below. Otherwise, point the button to your GitHub repo or PDF.
    <br/>⚠️ Public embeds are visible to anyone and may be indexed by search engines.</p>
    <div class="embed-wrap">
      <iframe title="Power BI Report" src="https://app.powerbi.com/view?r=eyJrIjoiZjliMGE0NWMtYjMzMi00OTNmLWIwNzYtNGQ3ZWQ2M2YyMWRkIiwidCI6ImZlZTNiOTE2LTAxYzEtNDk4Ny1hNjQ2LWUxOTM0MzJiOWVhYSIsImMiOjl9&pageName=91a4f559eaa1911813a8" allowfullscreen></iframe>
    </div>
    <div class="cta" style="margin-top:10px;">
      <a class="btn btn-ghost" href="https://github.com/your-username/dashboard-portfolio" target="_blank" rel="noopener">Open on GitHub</a>
      <a class="btn btn-primary" href="dashboard.pdf" target="_blank" rel="noopener">View PDF</a>
    </div>

    <footer>
      © <span id="y"></span> Murtaza Askari · <a href="https://www.linkedin.com/in/murtazaaskari98" target="_blank" rel="noopener" style="color:var(--text); text-decoration:none;">LinkedIn</a>
      <div class="small">Built with vanilla HTML/CSS. Hosted on GitHub Pages.</div>
    </footer>
  </div>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
