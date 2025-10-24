<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Name — CS Capstone E‑Portfolio</title>
  <meta name="description" content="Computer Science capstone e‑portfolio with welcome, professional self‑assessment, artifact, narratives, and code review video." />
  <meta name="color-scheme" content="light" />
  <style>
    :root{
      --bg:#ffffff;          /* bright background */
      --text:#1f2937;        /* slate-800 */
      --muted:#4b5563;       /* slate-600 */
      --border:#e5e7eb;      /* slate-200 */
      --card:#f9fafb;        /* slate-50 */
      --accent:#2563eb;      /* blue-600 */
      --accent-ink:#ffffff;  
      --maxw:900px;          /* simpler, narrower */
      --radius:14px;
    }
    html,body{height:100%}
    body{margin:0;background:var(--bg);color:var(--text);font:16px/1.7 system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,"Apple Color Emoji","Segoe UI Emoji"}
    .container{max-width:var(--maxw);margin:0 auto;padding:0 1rem}

    /* Header */
    header{position:sticky;top:0;background:#fffffff2;backdrop-filter:saturate(120%) blur(6px);border-bottom:1px solid var(--border);z-index:10}
    .nav{display:flex;align-items:center;justify-content:space-between;padding:.9rem 0}
    .brand{font-weight:800;letter-spacing:.2px}
    nav ul{display:flex;gap:1rem;list-style:none;margin:0;padding:0}
    nav a{color:var(--muted);text-decoration:none;font-weight:600}
    nav a:hover,nav a:focus{color:var(--accent)}

    /* Sections */
    section{padding:2.25rem 0;border-top:1px solid var(--border)}
    section:first-of-type{border-top:none}
    h1{font-size:clamp(1.8rem,2.5vw+1rem,2.6rem);line-height:1.2;margin:.5rem 0}
    h2{font-size:clamp(1.3rem,1.2vw+1rem,1.8rem);margin:.2rem 0 1rem}
    .lead{color:var(--muted);max-width:70ch}

    /* Cards */
    .grid{display:grid;grid-template-columns:1fr;gap:1rem}
    .card{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:1rem}
    .card h3{margin-top:.2rem}

    /* Buttons & links */
    .btn{display:inline-block;background:var(--accent);color:var(--accent-ink);text-decoration:none;border-radius:999px;padding:.55rem .9rem;font-weight:700;border:1px solid color-mix(in lab, var(--accent) 85%, black 0%)}
    .btn.ghost{background:transparent;color:var(--accent);border-color:var(--accent)}

    /* Footer */
    footer{border-top:1px solid var(--border);padding:1.5rem 0;color:var(--muted)}

    /* Accessibility */
    .skip-link{position:absolute;left:-9999px;top:auto;width:1px;height:1px;overflow:hidden}
    .skip-link:focus{position:static;width:auto;height:auto;padding:.5rem .75rem;background:var(--accent);color:var(--accent-ink);border-radius:8px}
    :focus-visible{outline:3px solid rgba(37,99,235,.35);outline-offset:2px}

    /* Simple video placeholder */
    .video{aspect-ratio:16/9;background:#eef2ff;border:2px dashed #c7d2fe;border-radius:12px;display:flex;align-items:center;justify-content:center;color:#4338ca}
  </style>
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>
  <header role="banner">
    <div class="container nav">
      <div class="brand">Your Name</div>
      <nav aria-label="Primary">
        <ul>
          <li><a href="#welcome">Welcome</a></li>
          <li><a href="#self">Self‑Assessment</a></li>
          <li><a href="#artifact">Artifact</a></li>
          <li><a href="#narratives">Narratives</a></li>
          <li><a href="#code-review">Code Review</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main" class="container" role="main">
    <!-- Welcome -->
    <section id="welcome" aria-labelledby="welcome-title">
      <h1 id="welcome-title">Welcome</h1>
      <p class="lead">Write a short welcome message here. State your degree program, your focus areas, and your goal for this e‑portfolio. Keep it clear and friendly.</p>
    </section>

    <!-- Professional Self‑Assessment / Education Review -->
    <section id="self" aria-labelledby="self-title">
      <h2 id="self-title">Professional Self‑Assessment</h2>
      <div class="card">
        <p>Summarize your growth across the program. Reflect on design habits, testing practices, collaboration, and ethics. Mention how coursework shaped your approach to problem solving and planning. Include 2–3 concrete examples with outcomes.</p>
      </div>
    </section>

    <!-- Artifact: Original vs Enhanced -->
    <section id="artifact" aria-labelledby="artifact-title">
      <h2 id="artifact-title">Capstone Artifact</h2>
      <p class="lead">This single artifact maps to three categories: Software Engineering & Design, Algorithms & Data Structures, and Databases.</p>
      <div class="grid">
        <article class="card" aria-labelledby="orig-title">
          <h3 id="orig-title">Original Artifact</h3>
          <p>Briefly describe the project at the time you first submitted it: goals, context, and limitations.</p>
          <p><strong>Link:</strong> <a href="#" aria-label="Original artifact link">Add repo/file link</a></p>
          <p><strong>Key Snapshot:</strong> commit/tag/branch reference.</p>
        </article>
        <article class="card" aria-labelledby="enh-title">
          <h3 id="enh-title">Enhanced Artifact</h3>
          <p>Describe the improvements you made for the capstone: design changes, code quality, tests, performance, or data model updates.</p>
          <p><strong>Link:</strong> <a href="#" aria-label="Enhanced artifact link">Add repo/file link</a></p>
          <p><strong>Evidence:</strong> link to diff, PR, or release notes.</p>
        </article>
      </div>
    </section>

    <!-- Narratives for each category (same artifact) -->
    <section id="narratives" aria-labelledby="nar-title">
      <h2 id="nar-title">Narratives</h2>

      <article class="card" aria-labelledby="nar-se-title">
        <h3 id="nar-se-title">Category One — Software Engineering & Design</h3>
        <p>Explain how the enhancement improved architecture, readability, and maintainability. Point to patterns, refactoring, and tests that prove quality.</p>
      </article>

      <article class="card" aria-labelledby="nar-algo-title">
        <h3 id="nar-algo-title">Category Two — Algorithms & Data Structures</h3>
        <p>Explain how you optimized an algorithm, chose a better data structure, or reduced time/space complexity. Provide metrics or benchmarks if available.</p>
      </article>

      <article class="card" aria-labelledby="nar-db-title">
        <h3 id="nar-db-title">Category Three — Databases</h3>
        <p>Explain schema or query changes, indexing, or transaction safety. Show how these changes improved correctness or performance.</p>
      </article>
    </section>

    <!-- Code Review Video placeholder -->
    <section id="code-review" aria-labelledby="cr-title">
      <h2 id="cr-title">Code Review Video</h2>
      <div class="card">
        <p>When your video is ready, paste the link below. You can also embed it.</p>
        <p><strong>Link:</strong> <a href="#">Add your video URL</a></p>
        <div class="video" role="img" aria-label="Video placeholder">Video placeholder (16:9)</div>
        <!-- To embed later (example):
        <div class="video"><iframe title="Code review video" src="https://www.youtube.com/embed/VIDEO_ID" width="100%" height="100%" frameborder="0" allowfullscreen></iframe></div>
        -->
      </div>
    </section>
  </main>

  <footer class="container" role="contentinfo">
    <small>© <span id="year"></span> Your Name. Last updated <time id="lastUpdated" datetime=""></time>.</small>
  </footer>

  <script>
    // Current year & last modified
    document.getElementById('year').textContent = new Date().getFullYear();
    const lm = new Date(document.lastModified);
    const last = document.getElementById('lastUpdated');
    last.textContent = lm.toLocaleDateString(undefined,{year:'numeric',month:'short',day:'numeric'});
    last.setAttribute('datetime', lm.toISOString());
  </script>
</body>
</html>
