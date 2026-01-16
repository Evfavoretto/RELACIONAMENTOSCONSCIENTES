<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Relacionamentos Conscientes | Workshop</title>
  <meta name="description" content="Workshop de duas noites: Relacionamentos Conscientes — Do vínculo inconsciente ao encontro real. 19 e 20 de fevereiro de 2026 às 20h." />

  <meta property="og:title" content="Relacionamentos Conscientes | Workshop" />
  <meta property="og:description" content="Do vínculo inconsciente ao encontro real. Relacionamento não é sobre encontrar alguém. É sobre o lugar interno a partir do qual eu me relaciono." />
  <meta property="og:type" content="website" />

  <style>
    :root{
      /* FUNDO CLARO (azul + roxo + rosa) */
      --blue:   #cfeeff;
      --lilac:  #e6ddff;
      --pink:   #ffe3f1;

      /* Tipografia */
      --ink:    #0b1020;
      --text:   rgba(11,16,32,0.92);
      --muted:  rgba(11,16,32,0.70);
      --muted2: rgba(11,16,32,0.56);

      /* UI */
      --accent: #7c3aed; /* roxo */
      --accent2:#ec4899; /* rosa */
      --stroke: rgba(11,16,32,0.12);

      --card:   rgba(255,255,255,0.78);
      --card2:  rgba(255,255,255,0.86);

      --shadow: 0 20px 55px rgba(11,16,32,.14);
      --radius: 22px;
      --max: 1140px;
    }

    *{ box-sizing:border-box; }
    html,body{ height:100%; }
    body{
      margin:0;
      color:var(--text);
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;
      background:
        radial-gradient(1200px 760px at 14% 22%, rgba(207,238,255,0.95), transparent 60%),
        radial-gradient(1200px 760px at 86% 30%, rgba(230,221,255,0.92), transparent 62%),
        radial-gradient(1000px 640px at 50% 0%, rgba(255,227,241,0.86), transparent 66%),
        linear-gradient(180deg, #f7fbff 0%, #faf7ff 60%, #fff7fb 100%);
      overflow-x:hidden;
    }

    a{ color:inherit; text-decoration:none; }
    .wrap{ max-width:var(--max); margin:0 auto; padding:0 18px; }

    /* ============================================================
       KILL SWITCH — remove header/título do GitHub Pages / Jekyll
       (Cayman, Slate, Minimal, etc.)
       ============================================================ */
    body > h1,
    body > header:not(.hero),
    .page-header,
    .site-header,
    header.page-header,
    header.site-header,
    #header, #header_wrap, #header-wrap,
    #project_title, #project_tagline,
    .project-name, .project-tagline,
    #title, #subtitle,
    #forkme_banner, .ribbon,
    .github-corner,
    .gh-header, .gh-head {
      display:none !important;
      height:0 !important;
      margin:0 !important;
      padding:0 !important;
      border:0 !important;
    }
    main, .main-content, .container, .wrapper{
      padding-top:0 !important;
      margin-top:0 !important;
    }

    /* TOPBAR */
    .topbar{
      position:sticky; top:0; z-index:50;
      background: rgba(255,255,255,.68);
      backdrop-filter: blur(12px);
      border-bottom:1px solid var(--stroke);
    }
    .topbar .inner{
      display:flex; align-items:center; justify-content:space-between;
      gap:12px; padding:12px 0;
    }
    .datepill{
      display:inline-flex; align-items:center; gap:10px;
      padding:10px 12px;
      border-radius:999px;
      background: rgba(255,255,255,0.85);
      border:1px solid var(--stroke);
      color: var(--muted);
      font-weight:800;
      letter-spacing:.2px;
      white-space:nowrap;
    }
    .dot{
      width:10px; height:10px; border-radius:999px;
      background: radial-gradient(circle at 35% 35%, #fff, rgba(124,58,237,0.95));
      box-shadow: 0 0 0 6px rgba(124,58,237,0.12);
      flex:0 0 auto;
    }
    .actions{
      display:flex; gap:10px; flex-wrap:wrap;
    }

    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      padding:12px 16px;
      border-radius:999px;
      border:1px solid var(--stroke);
      background: rgba(255,255,255,0.86);
      color: var(--text);
      font-weight:900;
      letter-spacing:.2px;
      box-shadow: var(--shadow);
      transition: transform .15s ease, box-shadow .15s ease, border-color .15s ease;
    }
    .btn:hover{
      transform: translateY(-1px);
      border-color: rgba(124,58,237,0.25);
      box-shadow: 0 22px 60px rgba(11,16,32,.16);
    }
    .btn.primary{
      border-color: rgba(124,58,237,0.25);
      background: linear-gradient(180deg, rgba(230,221,255,0.95), rgba(255,255,255,0.92));
    }
    .btn.ghost{
      background: rgba(255,255,255,0.78);
      box-shadow:none;
    }

    /* HERO */
    .hero{ padding:54px 0 18px; }
    .grid{
      display:grid;
      grid-template-columns: 1.15fr .85fr;
      gap:18px;
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
    .card.pad{ padding:26px; }

    .glow{
      position:absolute; inset:-150px -160px auto auto;
      width:520px; height:520px;
      background: radial-gradient(circle at 35% 35%,
        rgba(255,255,255,0.75),
        rgba(255,227,241,0.55),
        rgba(230,221,255,0.48),
        transparent 64%);
      pointer-events:none;
      filter: blur(0.6px);
    }

    .sub{
      margin:0 0 14px;
      color: rgba(11,16,32,0.60);
      font-weight:950;
      text-transform:uppercase;
      letter-spacing:.35px;
      font-size:13px;
    }

    /* TÍTULO GIGANTE */
    h1{
      margin:0 0 14px;
      font-size: clamp(58px, 6.8vw, 96px);
      line-height: 0.98;
      letter-spacing: -1.35px;
      background: linear-gradient(90deg, rgba(11,16,32,0.92), rgba(124,58,237,0.92), rgba(236,72,153,0.80));
      -webkit-background-clip:text;
      background-clip:text;
      color: transparent;
    }

    .lead{
      margin:0 0 14px;
      font-size:16px;
      color: var(--muted);
      line-height:1.75;
    }

    .quote{
      margin:18px 0 0;
      padding:16px 16px;
      border-radius:18px;
      background: rgba(255,255,255,0.90);
      border:1px solid rgba(124,58,237,0.18);
    }
    .quote b{ color: rgba(124,58,237,0.95); }

    .mini{
      display:flex; gap:10px; flex-wrap:wrap;
      margin-top:14px;
      color: var(--muted2);
      font-size:13px;
    }
    .pill{
      padding:8px 10px;
      border:1px solid rgba(11,16,32,0.10);
      border-radius:999px;
      background: rgba(255,255,255,0.78);
    }

    /* SIDE CARD */
    .side{
      padding:26px;
      display:flex;
      flex-direction:column;
      gap:14px;
      background: var(--card2);
    }
    .kicker{
      margin:0;
      font-weight:950;
      letter-spacing:.2px;
      color: rgba(124,58,237,0.95);
      font-size:16px;
    }
    .info{
      display:flex; align-items:baseline; gap:10px;
      padding:14px;
      border-radius:18px;
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.92);
    }
    .info .big{ font-weight:900; }
    .info .small{ color: var(--muted2); font-size:13px; }

    /* SECTIONS */
    section{ padding:18px 0; }
    .section-title{
      margin:0 0 10px;
      font-size:22px;
      letter-spacing:-0.2px;
    }
    .section-sub{
      margin:0 0 18px;
      color: var(--muted);
      line-height:1.75;
    }

    .cols{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:14px;
    }
    .block{
      border-radius: var(--radius);
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.84);
      padding:18px;
    }
    .block h3{
      margin:0 0 10px;
      color: rgba(124,58,237,0.95);
      font-size:17px;
      letter-spacing:-0.1px;
    }
    .check{
      margin:0; padding:0; list-style:none;
      display:grid; gap:8px;
      color: var(--muted);
      line-height:1.6;
    }
    .check li{
      display:flex; gap:10px; align-items:flex-start;
    }
    .check li::before{
      content:"✓";
      color: rgba(124,58,237,0.95);
      font-weight:900;
      margin-top:1px;
    }

    .split{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:14px;
      align-items:stretch;
    }

    .cta{
      padding:28px;
      text-align:center;
      border-radius: calc(var(--radius) + 6px);
      background:
        radial-gradient(900px 520px at 18% 85%, rgba(207,238,255,0.80), transparent 60%),
        radial-gradient(900px 520px at 82% 85%, rgba(230,221,255,0.82), transparent 60%),
        radial-gradient(760px 360px at 50% 0%, rgba(255,227,241,0.82), transparent 65%),
        rgba(255,255,255,0.86);
      border:1px solid rgba(124,58,237,0.16);
      box-shadow: var(--shadow);
    }
    .cta h2{
      margin:0 0 10px;
      font-size:28px;
      letter-spacing:-0.25px;
    }
    .cta p{
      margin:0 auto 14px;
      max-width: 760px;
      color: var(--muted);
      line-height:1.75;
    }

    .faq details{
      border-radius:18px;
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.84);
      padding:14px;
    }
    .faq details + details{ margin-top:10px; }
    .faq summary{
      cursor:pointer;
      font-weight:900;
      color: var(--text);
    }
    .faq .ans{
      margin:10px 0 0;
      color: var(--muted);
      line-height:1.75;
    }

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

    @media (max-width: 920px){
      .grid{ grid-template-columns: 1fr; }
      .cols, .split{ grid-template-columns: 1fr; }
      .actions{ display:none; }
      h1{ font-size: clamp(44px, 10vw, 66px); }
    }
  </style>
</head>

<body>

  <!-- TOPBAR -->
  <div class="topbar">
    <div class="wrap">
      <div class="inner">
        <div class="datepill">
          <span class="dot" aria-hidden="true"></span>
          <span>19 e 20 de fevereiro • 20h</span>
        </div>
        <div class="actions">
          <a class="btn ghost" href="#conteudo">Ver conteúdo</a>
          <a class="btn primary" href="#inscricao">Quero participar</a>
        </div>
      </div>
    </div>
  </div>

  <!-- HERO -->
  <header class="hero">
    <div class="wrap">
      <div class="grid">

        <div class="card pad">
          <div class="glow" aria-hidden="true"></div>

          <p class="sub">Workshop — 2 noites • 19 e 20 de fevereiro de 2026 • 20h</p>

          <h1>RELACIONAMENTOS<br/>CONSCIENTES</h1>

          <p class="lead">
            <b style="color: rgba(124,58,237,0.95);">Do vínculo inconsciente ao encontro real</b>
          </p>

          <div class="quote">
            <div style="color:var(--muted); line-height:1.75;">
              Relacionamento não é sobre encontrar alguém.<br />
              É sobre o <b>lugar interno</b> a partir do qual eu me relaciono.
            </div>
          </div>

          <p class="lead" style="margin-top:14px;">
            Você muda a pessoa, mas a história se repete?<br />
            Talvez não seja falta de amor. Talvez seja falta de lugar.
          </p>

          <div style="display:flex; gap:10px; flex-wrap:wrap; margin-top:16px;" id="inscricao">
            <a class="btn primary" href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Quero%20participar%20do%20Workshop%20Relacionamentos%20Conscientes%20(19%20e%2020%2F02%2F2026%20%C3%A0s%2020h).%20Pode%20me%20enviar%20os%20detalhes%3F" target="_blank" rel="noopener">
              Quero participar do workshop
            </a>
            <a class="btn ghost" href="#paraquem">É pra mim?</a>
          </div>

          <div class="mini">
            <span class="pill">Acolhimento • Consciência • Reposicionamento</span>
            <span class="pill">Sem exposição • Sem receita pronta</span>
          </div>
        </div>

        <aside class="card side">
          <p class="kicker">Informações do evento</p>

          <div class="info">
            <div class="big">📅 Datas:</div>
            <div class="small"><b style="color: rgba(124,58,237,0.95);">19 e 20 de fevereiro de 2026</b></div>
          </div>

          <div class="info">
            <div class="big">⏰ Horário:</div>
            <div class="small"><b style="color: rgba(124,58,237,0.95);">20h</b></div>
          </div>

          <div class="info">
            <div class="big">⏳ Duração:</div>
            <div class="small"><b style="color: rgba(124,58,237,0.95);">3 a 4 horas por noite</b></div>
          </div>

          <div class="info">
            <div class="big">📍 Formato:</div>
            <div class="small"><b style="color: rgba(124,58,237,0.95);">[Online / Presencial]</b></div>
          </div>

          <p style="margin:6px 0 0; color:var(--muted); line-height:1.75;">
            Um workshop de duas noites para quem cansou de repetir padrões,
            se perder de si nos relacionamentos e deseja se relacionar a partir
            de um lugar mais consciente, adulto e verdadeiro.
          </p>

          <a class="btn primary"
             href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Quero%20participar%20do%20Workshop%20Relacionamentos%20Conscientes%20(19%20e%2020%2F02%2F2026%20%C3%A0s%2020h).%20Pode%20me%20enviar%20os%20detalhes%3F"
             target="_blank" rel="noopener">
            Receber detalhes no WhatsApp
          </a>

          <a class="btn ghost" href="#conteudo">Ver o que será trabalhado</a>

          <p style="margin:0; color:var(--muted2); font-size:13px; line-height:1.6;">
            *Se você tiver checkout, troque o link do botão principal para o pagamento e deixe o WhatsApp como opção.*
          </p>
        </aside>

      </div>
    </div>
  </header>

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

      </div>
    </div>
  </section>

  <!-- O QUE É + VIRADA -->
  <section id="conteudo">
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
            <div style="color:var(--muted); line-height:1.75;">
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
  <section>
    <div class="wrap">
      <div class="card pad">
        <h2 class="section-title">Quem conduz</h2>
        <p class="section-sub" style="margin-bottom:12px;">
          <b>Evandro Favoretto</b><br />
          Mentor em desenvolvimento emocional e relacional.
        </p>
        <p class="section-sub">
          Um trabalho voltado para reposicionamento interno e clareza emocional:
          organizar o lugar de onde você se relaciona para viver relações mais conscientes, leves e verdadeiras.
        </p>

        <div class="quote">
          <div style="color:var(--muted); line-height:1.75;">
            <b>Não é falta de amor.</b><br />
            Muitas vezes, é falta de lugar.
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA FINAL -->
  <section>
    <div class="wrap">
      <div class="cta">
        <h2>Pronto(a) para sair da repetição?</h2>
        <p>
          Esse workshop não promete salvar relacionamentos.<br />
          Ele convida você a ocupar o seu lugar interno — e, a partir disso, viver um encontro mais real.
        </p>

        <div style="display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin-top:6px;">
          <a class="btn primary"
             href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Quero%20participar%20do%20Workshop%20Relacionamentos%20Conscientes%20(19%20e%2020%2F02%2F2026%20%C3%A0s%2020h).%20Pode%20me%20enviar%20os%20detalhes%3F"
             target="_blank" rel="noopener">
            Garantir minha participação
          </a>
          <a class="btn ghost" href="#inscricao">Ver informações</a>
        </div>

        <p style="margin:14px auto 0; max-width:760px; color:var(--muted2); font-size:13px; line-height:1.65;">
          Datas: <b style="color: rgba(124,58,237,0.95);">19 e 20/02/2026</b> • Horário: <b style="color: rgba(124,58,237,0.95);">20h</b>
        </p>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="faq">
    <div class="wrap">
      <div class="card pad">
        <h2 class="section-title">Dúvidas comuns</h2>
        <p class="section-sub">Respostas simples para tirar dúvidas sem travar sua decisão.</p>

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

  <!-- FOOTER -->
  <footer>
    <div class="wrap">
      <div class="footgrid">
        <div>
          <div style="font-weight:950; color:var(--text);">Relacionamentos Conscientes</div>
          <div style="color:var(--muted2);">Do vínculo inconsciente ao encontro real</div>
          <div style="margin-top:6px;">Contato: <a href="https://wa.me/5549998110445" target="_blank" rel="noopener">(49) 99811-0445</a></div>
        </div>

        <div style="text-align:right;">
          <div>© <span id="year"></span> • Todos os direitos reservados</div>
          <div style="margin-top:6px;"><a href="#inscricao">Voltar ao topo</a></div>
        </div>
      </div>
    </div>
  </footer>

  <!-- JS: ano + remove resíduo do tema -->
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
      selectors.forEach(sel => {
        document.querySelectorAll(sel).forEach(el => el.remove());
      });

      // Se existir um H1 “solto” antes da sua topbar (como no print), remove.
      const first = document.body.firstElementChild;
      if (first && first.tagName === 'H1') first.remove();
      const stray = document.querySelector('body > h1');
      if (stray) stray.remove();
    })();
  </script>

</body>
</html>
