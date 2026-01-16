
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>Relacionamentos Conscientes | Workshop (19 e 20/02/2026 às 20h)</title>
  <meta name="description" content="Workshop de duas noites: Relacionamentos Conscientes — Do vínculo inconsciente ao encontro real. 19 e 20 de fevereiro de 2026 às 20h." />

  <!-- Canonical (troque pela URL final) -->
  <link rel="canonical" href="https://seu-dominio.com/relacionamentos-conscientes" />

  <!-- Open Graph -->
  <meta property="og:title" content="Relacionamentos Conscientes | Workshop" />
  <meta property="og:description" content="Do vínculo inconsciente ao encontro real. Relacionamento não é sobre encontrar alguém. É sobre o lugar interno a partir do qual eu me relaciono." />
  <meta property="og:type" content="website" />
  <meta property="og:locale" content="pt_BR" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Relacionamentos+Conscientes" />
  <meta property="og:url" content="https://seu-dominio.com/relacionamentos-conscientes" />

  <!-- Twitter Card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Relacionamentos Conscientes | Workshop" />
  <meta name="twitter:description" content="Do vínculo inconsciente ao encontro real. 19 e 20/02/2026 às 20h." />
  <meta name="twitter:image" content="https://via.placeholder.com/1200x630.png?text=Relacionamentos+Conscientes" />

  <link rel="icon" href="https://via.placeholder.com/64.png" />

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;600;700;800&family=Fraunces:opsz,wght@9..144,600;9..144,700&display=swap" rel="stylesheet" />

  <style>
    :root{
      --blue:#cfeeff;
      --lilac:#e6ddff;
      --pink:#ffe3f1;

      --ink:#0b1020;
      --text:rgba(11,16,32,0.92);
      --muted:rgba(11,16,32,0.70);
      --muted2:rgba(11,16,32,0.56);

      --accent:#7c3aed;
      --accent2:#ec4899;
      --stroke:rgba(11,16,32,0.12);

      --card:rgba(255,255,255,0.78);
      --card2:rgba(255,255,255,0.90);

      --shadow:0 20px 55px rgba(11,16,32,.14);
      --shadow2:0 12px 30px rgba(11,16,32,.10);
      --radius:22px;
      --max:1140px;

      --focus:0 0 0 4px rgba(124,58,237,0.25);
      --topbar-h:68px;

      /* Tipos base (desktop) */
      --h1: clamp(44px, 5.4vw, 84px);
      --lead: 15.5px;
      --p: 15px;
      --sub: 12px;
      --sec-title: 22px;
    }

    *{ box-sizing:border-box; }
    html,body{ height:100%; }
    body{
      margin:0;
      color:var(--text);
      font-family:"Manrope", ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;
      background:
        radial-gradient(1200px 760px at 14% 22%, rgba(207,238,255,0.95), transparent 60%),
        radial-gradient(1200px 760px at 86% 30%, rgba(230,221,255,0.92), transparent 62%),
        radial-gradient(1000px 640px at 50% 0%, rgba(255,227,241,0.86), transparent 66%),
        linear-gradient(180deg, #f7fbff 0%, #faf7ff 60%, #fff7fb 100%);
      overflow-x:hidden;
      padding-top: var(--topbar-h);
    }

    a{ color:inherit; text-decoration:none; }
    img{ max-width:100%; display:block; }
    .wrap{ max-width:var(--max); margin:0 auto; padding:0 18px; }

    /* Acessibilidade */
    .skip-link{ position:absolute; left:-999px; top:auto; width:1px; height:1px; overflow:hidden; }
    .skip-link:focus{
      left:18px; top:14px; width:auto; height:auto;
      padding:10px 12px; border-radius:12px;
      background:#fff; border:1px solid var(--stroke);
      box-shadow: var(--shadow2);
      outline:none;
      z-index:9999;
    }
    :focus-visible{ outline:none; box-shadow: var(--focus); border-radius:14px; }

    /* GitHub Pages tema */
    body > h1,
    body > header:not(.hero),
    .page-header,.site-header,header.page-header,header.site-header,
    #header,#header_wrap,#header-wrap,
    #project_title,#project_tagline,
    .project-name,.project-tagline,
    #title,#subtitle,
    #forkme_banner,.ribbon,
    .github-corner,.gh-header,.gh-head{
      display:none !important;
      height:0 !important;
      margin:0 !important;
      padding:0 !important;
      border:0 !important;
    }

    /* TOPBAR fixa */
    .topbar{
      position:fixed; left:0; right:0; top:0;
      height:var(--topbar-h);
      z-index:80;
      background: rgba(255,255,255,.78);
      backdrop-filter: blur(12px);
      border-bottom:1px solid var(--stroke);
      display:flex; align-items:center;
    }
    .topbar .inner{
      display:flex; align-items:center; justify-content:space-between;
      gap:12px; padding:10px 0;
    }
    .brand{ display:flex; align-items:center; gap:10px; min-width:220px; }
    .mark{
      width:34px; height:34px; border-radius:14px;
      background: radial-gradient(circle at 30% 30%, #fff, rgba(124,58,237,0.95));
      box-shadow: 0 0 0 6px rgba(124,58,237,0.10);
      flex:0 0 auto;
    }
    .brand strong{ font-weight:900; letter-spacing:-0.3px; line-height:1.05; }
    .brand span{ display:block; font-size:12px; color:var(--muted2); margin-top:2px; font-weight:700; }

    .datepill{
      display:inline-flex; align-items:center; gap:10px;
      padding:9px 11px; border-radius:999px;
      background: rgba(255,255,255,0.85);
      border:1px solid var(--stroke);
      color: var(--muted);
      font-weight:800;
      white-space:nowrap;
      font-size:13px;
    }
    .dot{
      width:10px; height:10px; border-radius:999px;
      background: radial-gradient(circle at 35% 35%, #fff, rgba(236,72,153,0.95));
      box-shadow: 0 0 0 6px rgba(236,72,153,0.12);
      flex:0 0 auto;
    }
    nav{ display:flex; gap:12px; align-items:center; justify-content:center; flex:1; }
    nav a{
      padding:9px 10px; border-radius:999px;
      font-weight:800; color:var(--muted);
      border:1px solid transparent;
      transition: background .15s ease, border-color .15s ease, transform .15s ease;
      white-space:nowrap;
      font-size:13px;
    }
    nav a:hover{
      background: rgba(255,255,255,.75);
      border-color: rgba(124,58,237,0.16);
      transform: translateY(-1px);
      color: var(--text);
    }
    .actions{ display:flex; gap:10px; flex-wrap:wrap; justify-content:flex-end; min-width:240px; }

    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      padding:12px 16px; border-radius:999px;
      border:1px solid var(--stroke);
      background: rgba(255,255,255,0.88);
      color: var(--text);
      font-weight:900;
      box-shadow: var(--shadow2);
      transition: transform .15s ease, box-shadow .15s ease, border-color .15s ease, filter .15s ease;
      font-size:13.5px;
    }
    .btn:hover{
      transform: translateY(-1px);
      border-color: rgba(124,58,237,0.25);
      box-shadow: 0 22px 60px rgba(11,16,32,.16);
      filter: brightness(1.02);
    }
    .btn.primary{
      border-color: rgba(124,58,237,0.25);
      background: linear-gradient(180deg, rgba(230,221,255,0.95), rgba(255,255,255,0.92));
    }
    .btn.ghost{ background: rgba(255,255,255,0.78); box-shadow:none; }

    /* HERO */
    .hero{ padding:18px 0 12px; }
    .grid{
      display:grid;
      grid-template-columns: 1.15fr .85fr;
      gap:16px;
      align-items:stretch;
    }
    .card{
      background: var(--card);
      border:1px solid var(--stroke);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      position:relative;
      overflow:hidden;
    }
    .card.pad{ padding:18px; }

    .glow{
      position:absolute; inset:-150px -160px auto auto;
      width:520px; height:520px;
      background: radial-gradient(circle at 35% 35%,
        rgba(255,255,255,0.75),
        rgba(255,227,241,0.55),
        rgba(230,221,255,0.48),
        transparent 64%);
      pointer-events:none;
    }

    .sub{
      margin:0 0 10px;
      color: rgba(11,16,32,0.60);
      font-weight:950;
      text-transform:uppercase;
      letter-spacing:.35px;
      font-size: var(--sub);
    }

    /* H1 CONTROLADO (sem estourar) */
    h1{
      margin:0 0 8px;
      font-family:"Fraunces", ui-serif, Georgia, serif;
      font-size: var(--h1);
      line-height: 1.02;
      letter-spacing: -0.9px;
      background: linear-gradient(90deg, rgba(11,16,32,0.92), rgba(124,58,237,0.92), rgba(236,72,153,0.80));
      -webkit-background-clip:text;
      background-clip:text;
      color: transparent;
    }
    h1 span{ display:inline-block; }

    .lead{
      margin:0 0 12px;
      font-size: var(--lead);
      color: var(--muted);
      line-height:1.65;
    }

    .bullets{
      display:grid; gap:10px;
      margin:12px 0 0;
      padding:0;
      list-style:none;
      color:var(--muted);
      font-size: var(--p);
    }
    .bullets li{
      display:flex; gap:10px; align-items:flex-start;
      background: rgba(255,255,255,0.78);
      border: 1px solid rgba(11,16,32,0.08);
      border-radius: 16px;
      padding:10px 12px;
    }
    .bullets li::before{
      content:"✦";
      color: rgba(124,58,237,0.95);
      font-weight:900;
      margin-top:1px;
    }

    .quote{
      margin:12px 0 0;
      padding:12px 12px;
      border-radius:18px;
      background: rgba(255,255,255,0.92);
      border:1px solid rgba(124,58,237,0.18);
      font-size: var(--p);
    }
    .quote b{ color: rgba(124,58,237,0.95); }

    .mini{
      display:flex; gap:10px; flex-wrap:wrap;
      margin-top:12px;
      color: var(--muted2);
      font-size:12.5px;
    }
    .pill{
      padding:7px 10px;
      border:1px solid rgba(11,16,32,0.10);
      border-radius:999px;
      background: rgba(255,255,255,0.78);
      font-weight:800;
    }

    /* SIDE CARD */
    .side{
      padding:18px;
      display:flex;
      flex-direction:column;
      gap:12px;
      background: var(--card2);
    }
    .kicker{
      margin:0;
      font-weight:950;
      letter-spacing:.2px;
      color: rgba(124,58,237,0.95);
      font-size:15px;
    }
    .info{
      display:flex; align-items:flex-start; gap:10px;
      padding:12px;
      border-radius:18px;
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.92);
    }
    .info .big{ font-weight:900; min-width: 92px; font-size:13px; }
    .info .small{ color: var(--muted2); font-size:13px; line-height:1.45; }

    .badge{
      display:flex; align-items:center; justify-content:space-between; gap:10px;
      padding:14px 14px;
      border-radius:18px;
      border:1px solid rgba(124,58,237,0.16);
      background: rgba(230,221,255,0.55);
    }
    .badge strong{ font-weight:950; }
    .badge span{ color:var(--muted); font-weight:800; font-size:13px; }
    .badge s{ color: rgba(11,16,32,0.45); }

    /* SECTIONS */
    section{ padding:16px 0; }
    .section-title{
      margin:0 0 10px;
      font-size: var(--sec-title);
      letter-spacing:-0.2px;
    }
    .section-sub{
      margin:0 0 16px;
      color: var(--muted);
      line-height:1.68;
      font-size: var(--p);
    }

    .cols{ display:grid; grid-template-columns: 1fr 1fr; gap:14px; }
    .block{
      border-radius: var(--radius);
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.86);
      padding:16px;
      box-shadow: 0 10px 26px rgba(11,16,32,.06);
    }
    .block h3{
      margin:0 0 10px;
      color: rgba(124,58,237,0.95);
      font-size:16px;
    }

    .check{
      margin:0; padding:0; list-style:none;
      display:grid; gap:8px;
      color: var(--muted);
      line-height:1.6;
      font-size: var(--p);
    }
    .check li{ display:flex; gap:10px; align-items:flex-start; }
    .check li::before{ content:"✓"; color: rgba(124,58,237,0.95); font-weight:900; margin-top:1px; }

    .split{ display:grid; grid-template-columns: 1fr 1fr; gap:14px; align-items:stretch; }

    .stats{
      display:grid; gap:12px;
      grid-template-columns: repeat(3, 1fr);
      margin-top: 12px;
    }
    .stat{
      border-radius: 18px;
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.90);
      padding:14px;
      text-align:left;
    }
    .stat .num{ font-size:18px; font-weight:950; color: rgba(124,58,237,0.95); }
    .stat .lbl{ margin-top:4px; color: var(--muted2); font-size:12.5px; font-weight:800; line-height:1.35; }

    /* Depoimentos sem foto */
    .testimonials{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:14px;
      margin-top: 10px;
    }
    .t{
      border-radius: var(--radius);
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.86);
      padding:14px;
      box-shadow: 0 10px 26px rgba(11,16,32,.06);
    }
    .t p{ margin:0; color: var(--muted); line-height:1.6; font-size: var(--p); }
    .t .who{ margin-top:10px; color: var(--muted2); font-size:12.5px; font-weight:950; }

    /* PIX */
    .pix{
      margin: 14px auto 0;
      max-width: 920px;
      text-align:left;
      border-radius: 18px;
      border: 1px solid rgba(124,58,237,0.16);
      background: rgba(255,255,255,0.90);
      padding: 16px;
      box-shadow: 0 10px 26px rgba(11,16,32,.06);
    }
    .pix .row{
      display:flex; gap:12px; flex-wrap:wrap;
      align-items:center; justify-content:space-between;
    }
    .pix code{
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
      font-size: 13px;
      padding: 8px 10px;
      border-radius: 12px;
      background: rgba(230,221,255,0.55);
      border: 1px solid rgba(124,58,237,0.16);
      user-select: all;
    }
    .pix small{ color: var(--muted2); font-weight:800; font-size:12px; }
    .copybtn{
      padding:10px 12px;
      border-radius: 14px;
      border: 1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.90);
      font-weight: 950;
      cursor: pointer;
      box-shadow: var(--shadow2);
      font-size:13px;
    }
    .copybtn:hover{ transform: translateY(-1px); }
    .toast{
      margin-top: 10px;
      color: rgba(124,58,237,0.95);
      font-weight: 950;
      display:none;
      font-size: 13px;
    }

    /* Foto menor */
    .photo-wrap{
      max-width: 340px;
      margin: 0 auto;
      padding: 12px;
      text-align:center;
    }
    .photo-wrap img{
      width: 100%;
      height: 300px;
      object-fit: cover;
      border-radius:18px;
      border:1px solid rgba(11,16,32,0.10);
      box-shadow: var(--shadow2);
    }

    /* FAQ */
    .faq details{
      border-radius:18px;
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.86);
      padding:14px;
    }
    .faq details + details{ margin-top:10px; }
    .faq summary{
      cursor:pointer;
      font-weight:950;
      color: var(--text);
      list-style:none;
      font-size: 14px;
    }
    .faq summary::-webkit-details-marker{ display:none; }
    .faq summary::after{
      content:"+";
      float:right;
      font-weight:950;
      color: rgba(124,58,237,0.95);
    }
    .faq details[open] summary::after{ content:"–"; }
    .faq .ans{ margin:10px 0 0; color: var(--muted); line-height:1.65; font-size: var(--p); }

    /* Footer */
    footer{
      padding:26px 0 40px;
      color: var(--muted2);
      font-size:13px;
    }
    .footgrid{
      display:grid;
      grid-template-columns: 1fr auto;
      gap:12px;
      align-items:center;
      border-top: 1px solid rgba(11,16,32,0.10);
      padding-top:18px;
    }

    /* WhatsApp floating */
    .whats-float{
      position: fixed;
      right: 16px;
      bottom: 16px;
      width: 54px;
      height: 54px;
      border-radius: 18px;
      background: #25D366;
      display:flex; align-items:center; justify-content:center;
      box-shadow: 0 18px 40px rgba(11,16,32,.22);
      z-index: 60;
      border: 1px solid rgba(255,255,255,0.25);
      transition: transform .15s ease, filter .15s ease;
    }
    .whats-float svg{ width: 28px; height: 28px; fill: #fff; }
    .whats-float:hover{ filter: brightness(1.03); transform: translateY(-1px); }

    /* RESPONSIVO (MOBILE MENOR DE VERDADE) */
    @media (max-width: 980px){
      nav{ display:none; }
      .brand{ min-width: unset; }
    }
    @media (max-width: 920px){
      :root{
        --topbar-h: 60px;

        /* >>> aqui está o ajuste principal do “texto grande” <<< */
        --h1: clamp(28px, 8.3vw, 40px);
        --lead: 13.8px;
        --p: 13.5px;
        --sub: 11px;
        --sec-title: 19px;
      }

      body{ padding-top: var(--topbar-h); }

      .grid{ grid-template-columns: 1fr; }
      .cols, .split{ grid-template-columns: 1fr; }
      .actions{ display:none; }
      .datepill{ display:none; }

      .hero{ padding:12px 0 10px; }
      .card.pad{ padding:14px; }

      .bullets li{ padding:10px 10px; }
      .quote{ padding:10px 10px; }

      .stats{ grid-template-columns: 1fr; }
      .testimonials{ grid-template-columns: 1fr; }

      .photo-wrap{ max-width: 240px; padding: 8px; }
      .photo-wrap img{ height: 200px; }
    }

    @media (max-width: 380px){
      :root{
        --h1: 26px;
        --lead: 13.2px;
        --p: 13.2px;
      }
      .btn{ padding:11px 14px; }
    }
  </style>
</head>

<body>
  <a class="skip-link" href="#conteudo">Pular para o conteúdo</a>

  <!-- TOPBAR -->
  <div class="topbar" role="banner">
    <div class="wrap">
      <div class="inner">
        <a class="brand" href="#topo" aria-label="Ir ao topo">
          <span class="mark" aria-hidden="true"></span>
          <div>
            <strong>Relacionamentos Conscientes</strong>
            <span>Do vínculo inconsciente ao encontro real</span>
          </div>
        </a>

        <div class="datepill" aria-label="Data e horário do workshop">
          <span class="dot" aria-hidden="true"></span>
          <span>19 e 20 de fevereiro • 20h</span>
        </div>

        <nav aria-label="Navegação">
          <a href="#paraquem">É pra mim?</a>
          <a href="#conteudo">Conteúdo</a>
          <a href="#quem">Quem conduz</a>
          <a href="#faq">Dúvidas</a>
        </nav>

        <div class="actions">
          <a class="btn ghost" href="#conteudo">Ver conteúdo</a>
          <a class="btn primary" href="#pix">Pagamento (PIX)</a>
        </div>
      </div>
    </div>
  </div>

  <!-- HERO -->
  <header class="hero" id="topo">
    <div class="wrap">
      <div class="grid">

        <div class="card pad">
          <div class="glow" aria-hidden="true"></div>

          <p class="sub">Workshop — 2 noites • 19 e 20 de fevereiro de 2026 • 20h</p>

          <h1><span>RELACIONAMENTOS</span><br><span>CONSCIENTES</span></h1>

          <p class="lead">
            <b style="color: rgba(124,58,237,0.95);">Do vínculo inconsciente ao encontro real</b>
          </p>

          <div class="quote">
            <div style="color:var(--muted); line-height:1.65;">
              Relacionamento não é sobre encontrar alguém.<br />
              É sobre o <b>lugar interno</b> a partir do qual eu me relaciono.
            </div>
          </div>

          <ul class="bullets" aria-label="O que você vai encontrar">
            <li><b>Clareza emocional</b> para entender o padrão (sem se culpar).</li>
            <li><b>Reposicionamento adulto</b> para parar de implorar e começar a escolher.</li>
            <li><b>Próximos passos</b> simples e práticos para aplicar no dia a dia.</li>
          </ul>

          <p class="lead" style="margin-top:12px;">
            Você muda a pessoa, mas a história se repete?<br />
            Talvez não seja falta de amor. Talvez seja falta de lugar.
          </p>

          <!-- PIX (botão 1/2) -->
          <div style="display:flex; gap:10px; flex-wrap:wrap; margin-top:12px;">
            <a class="btn primary" href="#pix">Pagamento via PIX</a>
            <a class="btn ghost" href="#paraquem">É pra mim?</a>
          </div>

          <div class="mini" aria-label="Pilares do workshop">
            <span class="pill">Acolhimento • Consciência • Reposicionamento</span>
            <span class="pill">Sem exposição • Sem receita pronta</span>
          </div>
        </div>

        <aside class="card side" aria-label="Informações do evento">
          <p class="kicker">Informações do evento</p>

          <div class="info">
            <div class="big">📅 Datas</div>
            <div class="small"><b style="color: rgba(124,58,237,0.95);">19 e 20/02/2026</b></div>
          </div>

          <div class="info">
            <div class="big">⏰ Horário</div>
            <div class="small"><b style="color: rgba(124,58,237,0.95);">20h</b></div>
          </div>

          <div class="info">
            <div class="big">⏳ Duração</div>
            <div class="small"><b style="color: rgba(124,58,237,0.95);">2h por noite</b></div>
          </div>

          <div class="info">
            <div class="big">📍 Formato</div>
            <div class="small"><b style="color: rgba(124,58,237,0.95);">Online</b></div>
          </div>

          <div class="badge" aria-label="Vagas e investimento">
            <div>
              <strong>Vagas limitadas</strong><br />
              <span>
                <s>De R$ 260,00</s><br />
                <b style="color: rgba(124,58,237,0.95); font-size:18px;">Por R$ 44,00</b>
              </span>
            </div>
            <span>⭐</span>
          </div>

          <p style="margin:6px 0 0; color:var(--muted); line-height:1.65; font-size: var(--p);">
            Um workshop de duas noites para quem cansou de repetir padrões,
            se perder de si e deseja se relacionar a partir de um lugar mais
            consciente, adulto e verdadeiro.
          </p>

          <!-- PIX (botão 2/2) -->
          <a class="btn primary" href="#pix">Pagamento via PIX</a>

          <p style="margin:0; color:var(--muted2); font-size:12.5px; line-height:1.55;">
            Após pagar no PIX, envie o comprovante no WhatsApp para confirmar sua vaga.
          </p>

          <a class="btn ghost"
             href="https://wa.me/5549998110445?text=Ol%C3%A1!%20J%C3%A1%20fiz%20o%20PIX%20do%20Workshop%20Relacionamentos%20Conscientes%20e%20vou%20enviar%20o%20comprovante.%20Pode%20confirmar%20minha%20vaga%3F"
             target="_blank" rel="noopener">
            Enviar comprovante no WhatsApp
          </a>
        </aside>

      </div>
    </div>
  </header>

  <main id="conteudo">
    <!-- IDENTIFICAÇÃO -->
    <section>
      <div class="wrap">
        <div class="card pad">
          <h2 class="section-title">Se isso é você, essa página é um espelho</h2>
          <p class="section-sub">
            Você ama, tenta, conversa, se adapta… e mesmo assim algo sempre dói?<br />
            Talvez você não esteja vivendo um problema de “relacionamento”.<br />
            Talvez esteja vivendo um problema de <b>lugar emocional</b>.
          </p>

          <div class="cols" id="paraquem">
            <div class="block">
              <h3>✅ Este workshop é para você se…</h3>
              <ul class="check">
                <li>sente que repete padrões mesmo mudando de pessoa</li>
                <li>se perde de si tentando dar certo com alguém</li>
                <li>vive gatilhos, reatividade ou silêncios que afastam</li>
                <li>quer clareza emocional para se posicionar melhor</li>
                <li>está pronto(a) para se olhar com honestidade</li>
              </ul>
            </div>

            <div class="block">
              <h3>❌ Não é para você se…</h3>
              <ul class="check">
                <li>procura receita pronta ou “frase mágica”</li>
                <li>quer mudar o outro sem mudar a si</li>
                <li>espera uma promessa de “salvar” relacionamento</li>
                <li>não está disposto(a) a assumir responsabilidade emocional</li>
                <li>quer apenas confirmar que “o outro é o problema”</li>
              </ul>
            </div>
          </div>

          <div class="stats" aria-label="Resultados esperados">
            <div class="stat">
              <div class="num">+ clareza</div>
              <div class="lbl">entender o padrão sem autoengano</div>
            </div>
            <div class="stat">
              <div class="num">+ presença</div>
              <div class="lbl">sair do automático e voltar para si</div>
            </div>
            <div class="stat">
              <div class="num">+ direção</div>
              <div class="lbl">ajustar, sustentar ou encerrar com respeito</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- O QUE É + VIRADA -->
    <section>
      <div class="wrap">
        <div class="split">
          <div class="card pad">
            <h2 class="section-title">O que é o Workshop Relacionamentos Conscientes?</h2>
            <p class="section-sub" style="margin-bottom:10px;">
              Um workshop de duas noites para reorganizar o seu lugar interno — e, a partir disso,
              transformar a forma como você se relaciona.
            </p>
            <ul class="check">
              <li>Não é terapia em grupo.</li>
              <li>Não é exposição de histórias.</li>
              <li>Não é um curso “racional” de comunicação.</li>
            </ul>
            <p class="section-sub" style="margin-top:12px;">
              É um espaço de <b>consciência</b>, <b>acolhimento</b> e <b>reposicionamento interno</b>:
              para sair do vínculo inconsciente (padrão) e caminhar para o encontro real (presença).
            </p>
          </div>

          <div class="card pad">
            <h2 class="section-title">A virada central</h2>
            <p class="section-sub" style="margin-bottom:10px;">
              A maioria das pessoas entra em relacionamentos a partir de lugares inconscientes:
              carência, medo de abandono, necessidade de aprovação ou tentativa de preencher vazios emocionais.
            </p>
            <div class="quote" style="margin:0;">
              <div style="color:var(--muted); line-height:1.65;">
                <b>Adulto não ama implorando.</b><br />
                Adulto ama escolhendo.
              </div>
            </div>
            <p class="section-sub" style="margin-top:12px;">
              Quando o lugar interno muda, a relação responde.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- DUAS NOITES -->
    <section>
      <div class="wrap">
        <div class="card pad">
          <h2 class="section-title">O que será trabalhado em cada noite</h2>
          <p class="section-sub">
            A estrutura foi desenhada para levar você de uma clareza profunda (noite 1)
            para um reposicionamento prático (noite 2).
          </p>

          <div class="cols">
            <div class="block">
              <h3>🌙 Noite 1 — O vínculo inconsciente</h3>
              <p class="section-sub" style="margin:0 0 10px;">
                <b>Objetivo:</b> entender por que dói e por que se repete.
              </p>
              <ul class="check">
                <li>Padrões repetitivos nos relacionamentos</li>
                <li>De onde vem o seu jeito de amar</li>
                <li>Carência, expectativa e projeção</li>
                <li>O outro como espelho emocional</li>
                <li>Como você se perde de si</li>
              </ul>
            </div>

            <div class="block">
              <h3>🌙 Noite 2 — O encontro real</h3>
              <p class="section-sub" style="margin:0 0 10px;">
                <b>Objetivo:</b> saber o que fazer a partir de agora.
              </p>
              <ul class="check">
                <li>O lugar adulto no relacionamento</li>
                <li>Comunicação consciente (sem ataque e sem defesa)</li>
                <li>Limites e responsabilidade emocional</li>
                <li>Clareza: sustentar, ajustar ou encerrar</li>
                <li>Próximo passo consciente (plano simples)</li>
              </ul>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- QUEM CONDUZ -->
    <section id="quem">
      <div class="wrap">
        <div class="card pad">
          <h2 class="section-title">Quem conduz</h2>

          <div class="split" style="align-items:center;">
            <div class="block" style="margin:0;">
              <p class="section-sub" style="margin:0 0 12px;">
                <b>Evandro Favoretto</b><br />
                Mentor em desenvolvimento emocional e relacional.
              </p>
              <p class="section-sub" style="margin:0;">
                Um trabalho voltado para reposicionamento interno e clareza emocional:
                organizar o lugar de onde você se relaciona para viver relações mais conscientes, leves e verdadeiras.
              </p>

              <div class="quote">
                <div style="color:var(--muted); line-height:1.65;">
                  <b>Não é falta de amor.</b><br />
                  Muitas vezes, é falta de lugar.
                </div>
              </div>
            </div>

            <div class="block photo-wrap">
              <img src="mentor.jpeg" alt="Foto do mentor Evandro Favoretto" loading="lazy" />
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- PAGAMENTO PIX (seção única) -->
    <section id="pix">
      <div class="wrap">
        <div class="card pad">
          <h2 class="section-title">Pagamento via PIX</h2>
          <p class="section-sub">
            Para garantir sua vaga, faça o PIX e depois envie o comprovante no WhatsApp.
          </p>

          <div class="pix" aria-label="Dados do PIX">
            <div class="row">
              <div>
                <small>Chave PIX (CNPJ)</small><br />
                <code id="pixKey">48674960000163</code>
              </div>
              <button class="copybtn" type="button" id="copyPix">Copiar chave</button>
            </div>

            <div style="margin-top:10px;">
              <small>Favorecido</small><br />
              <b>EA Favoretto LTDA</b>
            </div>

            <div class="toast" id="toast" role="status" aria-live="polite">Chave PIX copiada ✅</div>

            <div style="display:flex; gap:10px; flex-wrap:wrap; margin-top:14px;">
              <a class="btn primary"
                 href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Fiz%20o%20PIX%20do%20Workshop%20Relacionamentos%20Conscientes%20(CNPJ%2048674960000163%20-%20EA%20Favoretto%20LTDA)%20e%20vou%20enviar%20o%20comprovante.%20Pode%20confirmar%20minha%20vaga%3F"
                 target="_blank" rel="noopener">
                Enviar comprovante no WhatsApp
              </a>
              <a class="btn ghost" href="#conteudo">Voltar ao conteúdo</a>
            </div>

            <p style="margin:12px 0 0; color:var(--muted2); font-size:12.5px; line-height:1.55;">
              Dica: ao enviar o comprovante, informe seu <b>nome completo</b>.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- DEPOIMENTOS (sem foto) -->
    <section>
      <div class="wrap">
        <div class="card pad">
          <h2 class="section-title">O que as pessoas costumam sentir depois</h2>
          <p class="section-sub">Substitua por depoimentos reais quando quiser.</p>

          <div class="testimonials" aria-label="Depoimentos">
            <div class="t">
              <p>“Eu parei de tentar convencer e comecei a me posicionar. Foi leve e direto.”</p>
              <div class="who">Mariana S.</div>
            </div>
            <div class="t">
              <p>“Saí com clareza do que é meu e do que é do outro. Isso muda tudo.”</p>
              <div class="who">Carlos R.</div>
            </div>
          </div>

          <div style="display:flex; justify-content:center; gap:10px; margin-top:14px; flex-wrap:wrap;">
            <a class="btn ghost" href="#pix">Ir para a seção PIX</a>
            <a class="btn ghost" href="https://wa.me/5549998110445" target="_blank" rel="noopener">Tirar dúvida no WhatsApp</a>
          </div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section class="faq" id="faq">
      <div class="wrap">
        <div class="card pad">
          <h2 class="section-title">Dúvidas comuns</h2>
          <p class="section-sub">Respostas simples para tirar dúvidas sem travar sua decisão.</p>

          <details>
            <summary>Como confirmo minha vaga?</summary>
            <p class="ans">
              Faça o PIX para o CNPJ <b>48674960000163</b> (EA Favoretto LTDA) e envie o comprovante no WhatsApp.
            </p>
          </details>

          <details>
            <summary>Preciso estar em um relacionamento para participar?</summary>
            <p class="ans">
              Não. Esse workshop é sobre o seu lugar interno. Serve para quem está em relacionamento,
              para quem terminou, para quem está começando ou para quem quer se preparar melhor.
            </p>
          </details>

          <details>
            <summary>Isso é terapia em grupo?</summary>
            <p class="ans">
              Não. É um workshop de consciência e reposicionamento interno. Você participa com presença,
              exercícios e reflexões, sem necessidade de exposição pessoal.
            </p>
          </details>

          <details>
            <summary>Vai ter exercícios?</summary>
            <p class="ans">
              Sim. Exercícios guiados (simples e profundos) para trazer clareza emocional e próximos passos.
            </p>
          </details>

          <details>
            <summary>Esse workshop “salva” relacionamentos?</summary>
            <p class="ans">
              Ele não promete isso. Ele te ajuda a organizar o seu lugar interno — e quando isso muda, a relação responde.
              Às vezes para reconstruir, às vezes para ajustar, e às vezes para encerrar com respeito e consciência.
            </p>
          </details>
        </div>
      </div>
    </section>
  </main>

  <!-- WhatsApp floating -->
  <a class="whats-float"
     href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Quero%20tirar%20uma%20d%C3%BAvida%20sobre%20o%20Workshop%20Relacionamentos%20Conscientes."
     target="_blank" rel="noopener"
     aria-label="Falar no WhatsApp">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/>
    </svg>
  </a>

  <!-- FOOTER -->
  <footer>
    <div class="wrap">
      <div class="footgrid">
        <div>
          <div style="font-weight:950; color:var(--text);">Relacionamentos Conscientes</div>
          <div style="color:var(--muted2);">Do vínculo inconsciente ao encontro real</div>
          <div style="margin-top:6px;">
            Contato: <a href="https://wa.me/5549998110445" target="_blank" rel="noopener">(49) 99811-0445</a>
          </div>
        </div>

        <div style="text-align:right;">
          <div>© <span id="year"></span> • Todos os direitos reservados EA Favoretto LTDA</div>
          <div style="margin-top:6px;"><a href="#topo">Voltar ao topo</a></div>
        </div>
      </div>
    </div>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();

    (function killGithubTheme(){
      const selectors = [
        '.page-header','header.page-header','.site-header','header.site-header',
        '#header','#header_wrap','#header-wrap',
        '#project_title','#project_tagline',
        '.project-name','.project-tagline',
        '#title','#subtitle',
        '#forkme_banner','.ribbon',
        '.github-corner','.gh-header','.gh-head'
      ];
      selectors.forEach(sel => document.querySelectorAll(sel).forEach(el => el.remove()));
      const first = document.body.firstElementChild;
      if (first && first.tagName === 'H1') first.remove();
      const stray = document.querySelector('body > h1');
      if (stray) stray.remove();
    })();

    // Copiar PIX
    (function(){
      const btn = document.getElementById('copyPix');
      const key = document.getElementById('pixKey');
      const toast = document.getElementById('toast');

      if (!btn || !key || !toast) return;

      btn.addEventListener('click', async () => {
        try{
          await navigator.clipboard.writeText(key.textContent.trim());
          toast.textContent = 'Chave PIX copiada ✅';
          toast.style.display = 'block';
          setTimeout(() => toast.style.display = 'none', 2000);
        }catch(e){
          const range = document.createRange();
          range.selectNodeContents(key);
          const sel = window.getSelection();
          sel.removeAllRanges();
          sel.addRange(range);
          toast.textContent = 'Selecionei a chave — copie agora ✅';
          toast.style.display = 'block';
          setTimeout(() => toast.style.display = 'none', 2500);
        }
      });
    })();
  </script>
</body>
</html>
