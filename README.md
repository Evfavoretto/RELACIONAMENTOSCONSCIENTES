
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="color-scheme" content="light only">
  <meta name="theme-color" content="#ffffff">
  <title>Relacionamentos Conscientes | Workshop (19 e 20/02/2026 às 20h)</title>
  <meta name="description" content="Workshop de duas noites: Relacionamentos Conscientes — Do vínculo inconsciente ao encontro real. 19 e 20 de fevereiro de 2026 às 20h.">

  <link rel="icon" href="https://via.placeholder.com/64.png" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;600;700;800;900&family=Fraunces:opsz,wght@9..144,600;9..144,700&display=swap" rel="stylesheet" />

  <style>
    :root{
      --blue:#cfeeff; --lilac:#e6ddff; --pink:#ffe3f1;
      --ink:#0b1020; --text:rgba(11,16,32,0.92);
      --muted:rgba(11,16,32,0.70); --muted2:rgba(11,16,32,0.56);
      --accent:#7c3aed; --accent2:#ec4899; --stroke:rgba(11,16,32,0.12);
      --card:rgba(255,255,255,0.78); --card2:rgba(255,255,255,0.90);
      --shadow:0 20px 55px rgba(11,16,32,.14);
      --radius:22px;
      --topbar-h: 70px;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:"Manrope",sans-serif;
      color:var(--text);
      background:
        radial-gradient(1200px 760px at 14% 22%, rgba(207,238,255,0.95), transparent 60%),
        radial-gradient(1200px 760px at 86% 30%, rgba(230,221,255,0.92), transparent 62%),
        radial-gradient(1000px 640px at 50% 0%, rgba(255,227,241,0.86), transparent 66%),
        linear-gradient(180deg, #f7fbff 0%, #faf7ff 60%, #fff7fb 100%);
      padding-top:calc(var(--topbar-h) + env(safe-area-inset-top,0px));
    }
    a{text-decoration:none;color:inherit}
    .wrap{max-width:1100px;margin:auto;padding:0 18px}
    .topbar{position:fixed;top:0;left:0;right:0;height:var(--topbar-h);background:rgba(255,255,255,.8);backdrop-filter:blur(10px);display:flex;align-items:center;z-index:99;border-bottom:1px solid var(--stroke);}
    .topbar .inner{display:flex;align-items:center;justify-content:space-between;width:100%;}
    .brand{display:flex;align-items:center;gap:10px}
    .mark{width:32px;height:32px;border-radius:12px;background:radial-gradient(circle at 30% 30%,#fff,rgba(124,58,237,0.95));}
    .brand strong{font-weight:900}
    .brand span{font-size:12px;color:var(--muted2)}

    /* HERO */
    .hero{padding:30px 0 20px}
    .grid{display:grid;grid-template-columns:1.15fr .85fr;gap:18px;align-items:stretch}
    .card{background:var(--card);border:1px solid var(--stroke);border-radius:var(--radius);padding:20px;box-shadow:var(--shadow)}
    .sub{font-size:12px;font-weight:800;color:var(--muted2);text-transform:uppercase;margin-bottom:8px}

    /* Título menor */
    .hero-title{
      font-family:"Fraunces",serif;
      font-size:clamp(26px,5vw,44px);
      line-height:1.04;
      letter-spacing:-0.4px;
      background:linear-gradient(90deg,rgba(11,16,32,0.92),rgba(124,58,237,0.92),rgba(236,72,153,0.80));
      -webkit-background-clip:text;
      color:transparent;
    }

    .card-title{
      font-family:"Fraunces",serif;
      font-size:clamp(24px,4.6vw,36px);
      line-height:1.06;
      letter-spacing:-0.35px;
      background:linear-gradient(90deg,rgba(11,16,32,0.70),rgba(124,58,237,0.78),rgba(236,72,153,0.70));
      -webkit-background-clip:text;
      color:transparent;
    }

    .lead{color:var(--muted);line-height:1.6;font-size:15px}
    .quote{background:rgba(255,255,255,.9);border:1px solid rgba(124,58,237,0.18);padding:14px;border-radius:16px;margin-top:10px}

    .bullets{list-style:none;padding:0;margin:12px 0 0;display:grid;gap:8px}
    .bullets li::before{content:"✦";color:rgba(124,58,237,0.95);margin-right:6px}
    .btn{display:inline-block;padding:10px 16px;border-radius:999px;background:rgba(255,255,255,0.88);font-weight:800;border:1px solid rgba(11,16,32,0.1)}
    .btn.primary{background:linear-gradient(180deg,rgba(230,221,255,0.95),rgba(255,255,255,0.92));border-color:rgba(124,58,237,0.25)}

    /* Side */
    .side{background:var(--card2)}
    .info{background:rgba(255,255,255,0.9);padding:10px;border-radius:12px;margin-top:8px;font-size:14px}
    .badge{background:rgba(230,221,255,0.55);padding:12px;border-radius:14px;margin-top:10px;text-align:center}
    .badge b{color:rgba(124,58,237,0.95)}

    /* PIX */
    .pix{background:rgba(255,255,255,0.9);padding:14px;border-radius:14px;margin-top:12px;border:1px solid rgba(124,58,237,0.16)}

    footer{padding:26px 0 40px;color:var(--muted2);font-size:13px;text-align:center;border-top:1px solid rgba(11,16,32,0.1)}

    /* Responsivo */
    @media(max-width:980px){.grid{grid-template-columns:1fr}}
    @media(max-width:430px){
      .hero-title{font-size:clamp(20px,7vw,28px);letter-spacing:-0.3px;}
      .card-title{font-size:clamp(18px,6.4vw,24px);letter-spacing:-0.25px;}
    }
  </style>
</head>
<body>

  <div class="topbar">
    <div class="wrap">
      <div class="inner">
        <div class="brand">
          <div class="mark"></div>
          <div>
            <strong>Relacionamentos Conscientes</strong>
            <span>Do vínculo inconsciente ao encontro real</span>
          </div>
        </div>
      </div>
    </div>
  </div>

  <header class="hero">
    <div class="wrap">
      <div class="grid">
        <div class="card">
          <p class="sub">Workshop — 2 noites • 19 e 20 de fevereiro de 2026 • 20h</p>
          <h1 class="hero-title">RELACIONAMENTOS CONSCIENTES</h1>
          <p class="lead"><b style="color:rgba(124,58,237,0.95);">Do vínculo inconsciente ao encontro real</b></p>
          <div class="quote">Relacionamento não é sobre encontrar alguém.<br>É sobre o <b>lugar interno</b> a partir do qual eu me relaciono.</div>
          <ul class="bullets">
            <li><b>Clareza emocional</b> para entender o padrão (sem se culpar).</li>
            <li><b>Reposicionamento adulto</b> para parar de implorar e começar a escolher.</li>
          </ul>
          <div style="margin-top:12px;">
            <a href="#pix" class="btn primary">Pagamento via PIX</a>
          </div>
        </div>

        <aside class="card side">
          <div class="info">📅 <b>19 e 20/02/2026</b></div>
          <div class="info">⏰ <b>20h</b></div>
          <div class="info">📍 <b>Online</b></div>
          <div class="badge"><b>De R$260 por R$44</b></div>
        </aside>
      </div>
    </div>
  </header>

  <section id="pix">
    <div class="wrap">
      <div class="card">
        <h2 class="card-title">Pagamento via PIX</h2>
        <p class="lead">Envie o comprovante no WhatsApp após realizar o PIX.</p>
        <div class="pix">
          <b>Chave PIX (CNPJ):</b><br>
          <code>48674960000163</code><br>
          <b>Favorecido:</b> EA Favoretto LTDA
        </div>
      </div>
    </div>
  </section>

  <footer>
    © <span id="year"></span> EA Favoretto LTDA — Todos os direitos reservados
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
