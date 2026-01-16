
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Relacionamentos Conscientes | Workshop</title>

  <style>
    :root{
      --blue:#cfeeff;
      --purple:#e6ddff;
      --pink:#ffe3f1;
      --ink:#0b1020;

      --card: rgba(255,255,255,0.78);
      --stroke: rgba(11,16,32,0.12);

      --text: rgba(11,16,32,0.92);
      --muted: rgba(11,16,32,0.68);

      --accent:#8b5cf6;
      --shadow: 0 20px 50px rgba(11,16,32,.15);
      --radius: 22px;
      --max: 1140px;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color:var(--text);
      background:
        radial-gradient(1200px 700px at 15% 20%, var(--blue), transparent 60%),
        radial-gradient(1200px 700px at 85% 30%, var(--purple), transparent 60%),
        radial-gradient(1000px 600px at 50% 0%, var(--pink), transparent 65%),
        linear-gradient(180deg,#f7fbff 0%,#faf7ff 60%,#fff7fb 100%);
    }

    /* ====== KILL SWITCH GITHUB PAGES ====== */
    body > h1,
    body > header:not(.hero),
    .page-header, .site-header, #header, #header_wrap,
    #project_title, #project_tagline,
    .project-name, .project-tagline,
    .gh-header, .gh-head, .github-corner {
      display:none !important;
      height:0 !important;
      margin:0 !important;
      padding:0 !important;
    }

    a{color:inherit;text-decoration:none}
    .wrap{max-width:var(--max);margin:0 auto;padding:0 20px}

    /* TOPBAR */
    .topbar{
      position:sticky;top:0;z-index:10;
      background:rgba(255,255,255,.7);
      backdrop-filter:blur(10px);
      border-bottom:1px solid var(--stroke);
    }
    .topbar .inner{
      display:flex;justify-content:space-between;align-items:center;
      padding:14px 0;gap:14px;
    }
    .date{
      padding:10px 14px;
      border-radius:999px;
      background:white;
      border:1px solid var(--stroke);
      font-weight:700;
    }
    .actions{display:flex;gap:10px}
    .btn{
      padding:12px 18px;
      border-radius:999px;
      border:1px solid var(--stroke);
      background:white;
      font-weight:800;
      box-shadow:var(--shadow);
    }
    .btn.primary{
      background:linear-gradient(180deg,#e9e3ff,#ffffff);
      border-color:rgba(139,92,246,.35);
    }

    /* HERO */
    .hero{padding:70px 0 30px}
    .hero-card{
      background:var(--card);
      border:1px solid var(--stroke);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      padding:40px;
    }

    .subtitle{
      text-transform:uppercase;
      font-weight:900;
      letter-spacing:.3px;
      margin-bottom:14px;
      color:#555;
      font-size:13px;
    }

    h1{
      font-size:clamp(56px,6.5vw,96px);
      line-height:1;
      margin:0 0 16px;
      background:linear-gradient(90deg,#0b1020,#8b5cf6);
      -webkit-background-clip:text;
      background-clip:text;
      color:transparent;
    }

    .lead{
      font-size:18px;
      line-height:1.7;
      margin-bottom:22px;
      color:var(--muted);
    }

    .quote{
      background:white;
      border:1px solid rgba(139,92,246,.25);
      border-radius:16px;
      padding:18px;
      font-size:17px;
    }
    .quote b{color:var(--accent)}

    .cta-row{margin-top:26px;display:flex;gap:12px;flex-wrap:wrap}

    /* INFO */
    section{padding:40px 0}
    .card{
      background:var(--card);
      border:1px solid var(--stroke);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      padding:30px;
    }
    h2{margin-top:0}
    ul{padding-left:18px;line-height:1.7}

    footer{
      padding:30px 0;
      font-size:13px;
      color:#555;
      text-align:center;
    }

    @media(max-width:900px){
      .hero-card{padding:28px}
      h1{font-size:clamp(44px,10vw,64px)}
      .actions{display:none}
    }
  </style>
</head>

<body>

  <!-- TOPBAR -->
  <div class="topbar">
    <div class="wrap">
      <div class="inner">
        <div class="date">📅 19 e 20 de fevereiro • 20h</div>
        <div class="actions">
          <a class="btn" href="#conteudo">Ver conteúdo</a>
          <a class="btn primary" href="#inscricao">Quero participar</a>
        </div>
      </div>
    </div>
  </div>

  <!-- HERO -->
  <header class="hero">
    <div class="wrap">
      <div class="hero-card">

        <div class="subtitle">
          Workshop • 2 noites • fevereiro 2026
        </div>

        <h1>RELACIONAMENTOS<br>CONSCIENTES</h1>

        <p class="lead">
          <b>Do vínculo inconsciente ao encontro real</b><br><br>
          Você não se relaciona a partir do que deseja.<br>
          Você se relaciona a partir do lugar emocional que ocupa.
        </p>

        <div class="quote">
          Relacionamento não é sobre encontrar alguém.<br>
          É sobre o <b>lugar interno</b> a partir do qual eu me relaciono.
        </div>

        <div class="cta-row" id="inscricao">
          <a class="btn primary" href="https://wa.me/5549998110445" target="_blank">
            Quero participar do workshop
          </a>
          <a class="btn" href="#conteudo">É pra mim?</a>
        </div>

      </div>
    </div>
  </header>

  <!-- CONTEÚDO -->
  <section id="conteudo">
    <div class="wrap">
      <div class="card">
        <h2>Para quem é esse workshop</h2>
        <ul>
          <li>Para quem repete padrões nos relacionamentos</li>
          <li>Para quem se perde de si tentando dar certo com alguém</li>
          <li>Para quem quer se relacionar com mais clareza e maturidade</li>
          <li>Para quem está disposto(a) a assumir responsabilidade emocional</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap">
      <div class="card">
        <h2>O que será trabalhado</h2>
        <ul>
          <li>O vínculo inconsciente e sua origem</li>
          <li>O lugar emocional que você ocupa nas relações</li>
          <li>O posicionamento adulto no amor</li>
          <li>Clareza para sustentar, ajustar ou encerrar relações</li>
        </ul>
      </div>
    </div>
  </section>

  <footer>
    © <span id="year"></span> • Relacionamentos Conscientes
  </footer>

  <!-- JS FINAL: remove QUALQUER resíduo do GitHub -->
  <script>
    document.getElementById("year").textContent = new Date().getFullYear();

    (function killGithub(){
      const selectors = [
        '.page-header','header.page-header','.site-header',
        '#header','#header_wrap','#project_title','#project_tagline',
        '.project-name','.project-tagline','.github-corner'
      ];
      selectors.forEach(s=>{
        document.querySelectorAll(s).forEach(el=>el.remove());
      });
      if(document.body.firstElementChild?.tagName==='H1'){
        document.body.firstElementChild.remove();
      }
    })();
  </script>

</body>
</html>
