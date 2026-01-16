
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Relacionamentos Conscientes | Workshop</title>
  <meta name="description" content="Workshop de duas noites: Relacionamentos Conscientes — Do vínculo inconsciente ao encontro real. 19 e 20 de fevereiro de 2026 às 20h." />

  <meta property="og:title" content="Relacionamentos Conscientes | Workshop" />
  <meta property="og:description" content="Do vínculo inconsciente ao encontro real. Relacionamento não é sobre encontrar alguém. É sobre o lugar interno a partir do qual eu me relaciono." />
  <meta property="og:type" content="website" />

  <style>
    :root{
      /* Fundo (azul claro + roxo claro/rosa) */
      --sky1: #bfe7ff;   /* azul claro */
      --sky2: #d7ccff;   /* roxo claro */
      --rose: #ffd0ea;   /* rosa claro */
      --ink:  #0b1020;   /* texto escuro */

      --card: rgba(255,255,255,0.68);
      --card2: rgba(255,255,255,0.78);
      --stroke: rgba(11,16,32,0.10);

      --text: rgba(11,16,32,0.92);
      --muted: rgba(11,16,32,0.72);
      --muted2: rgba(11,16,32,0.58);

      --gold: #c89a2b;     /* dourado suave */
      --gold2:#8b5cf6;     /* roxo destaque (leve) */

      --shadow: 0 18px 50px rgba(11,16,32,.16);
      --radius: 22px;
      --max: 1140px;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      color:var(--text);
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";

      /* FUNDO CLARO, ATRATIVO E SUAVE */
      background:
        radial-gradient(1100px 760px at 15% 20%, rgba(191,231,255,0.95), transparent 62%),
        radial-gradient(1100px 760px at 85% 30%, rgba(215,204,255,0.92), transparent 64%),
        radial-gradient(900px 540px at 50% 0%, rgba(255,208,234,0.80), transparent 62%),
        linear-gradient(180deg, #f6fbff 0%, #faf7ff 55%, #fff7fb 100%);
      overflow-x:hidden;
    }

    a{color:inherit}
    .wrap{max-width:var(--max); margin:0 auto; padding:0 18px}

    /* DEFESA: se existir “título fantasma” acima, some */
    body > h1,
    body > header:not(.hero){
      display:none !important;
    }

    /* Topbar */
    .topbar{
      position:sticky; top:0; z-index:20;
      backdrop-filter: blur(10px);
      background: rgba(255,255,255,.60);
      border-bottom: 1px solid var(--stroke);
    }
    .topbar .inner{
      display:flex; align-items:center; justify-content:space-between;
      gap:14px; padding:12px 0;
    }
    .datepill{
      display:inline-flex; align-items:center; gap:10px;
      padding:10px 12px;
      border:1px solid var(--stroke);
      border-radius:999px;
      background: rgba(255,255,255,0.68);
      color: var(--muted);
      font-weight:800;
      letter-spacing:.2px;
      white-space:nowrap;
    }
    .dot{
      width:10px; height:10px; border-radius:999px;
      background: radial-gradient(circle at 30% 30%, #ffffff, rgba(139,92,246,0.9));
      box-shadow: 0 0 0 6px rgba(139,92,246,0.12);
      flex:0 0 auto;
    }

    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      padding:12px 16px;
      border-radius:999px;
      border:1px solid rgba(139,92,246,0.28);
      background: linear-gradient(180deg, rgba(139,92,246,0.18), rgba(255,255,255,0.75));
      color: var(--text);
      text-decoration:none;
      font-weight:900;
      letter-spacing:.2px;
      transition: transform .15s ease, border-color .15s ease, background .15s ease, box-shadow .15s ease;
      box-shadow: 0 10px 22px rgba(11,16,32,.14);
      cursor:pointer;
    }
    .btn:hover{ transform: translateY(-1px); border-color: rgba(139,92,246,0.48); }
    .btn.secondary{
      border-color: var(--stroke);
      background: rgba(255,255,255,0.66);
      font-weight:850;
      box-shadow:none;
    }
    .btn.secondary:hover{ transform: translateY(-1px); background: rgba(255,255,255,0.80); }

    .hero{ padding:56px 0 18px; }
    .grid{
      display:grid;
      grid-template-columns: 1.15fr .85fr;
      gap:18px;
      align-items:stretch;
    }

    .card{
      background: var(--card);
      border: 1px solid var(--stroke);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      overflow:hidden;
      position:relative;
    }
    .card.pad{ padding:26px; }

    /* brilho suave */
    .glow{
      position:absolute; inset:-120px -130px auto auto;
      width:440px; height:440px;
      background: radial-gradient(circle at 30% 30%, rgba(255,255,255,0.70), rgba(255,208,234,0.45), transparent 62%);
      pointer-events:none;
      filter: blur(0.6px);
    }

    .sub{
      margin:0 0 14px;
      color: rgba(11,16,32,0.68);
      font-weight:950;
      letter-spacing:.35px;
      text-transform:uppercase;
      font-size: 13px;
    }

    /* TÍTULO DO WORKSHOP BEM GRANDE */
    h1{
      margin:0 0 12px;
      font-size: clamp(52px, 6.2vw, 90px);
      line-height: 1.00;
      letter-spacing: -1.25px;
    }
    .title-accent{
      background: linear-gradient(90deg, rgba(11,16,32,0.92), rgba(139,92,246,0.92));
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
    }

    .lead{
      margin:0 0 14px;
      font-size: 16px;
      color: var(--muted);
      line-height: 1.75;
    }

    .quote{
      margin:18px 0 0;
      padding:16px 16px;
      border-radius: 18px;
      background: rgba(255,255,255,0.78);
      border: 1px solid rgba(139,92,246,0.18);
    }
    .quote b{ color: rgba(139,92,246,0.95); }

    .hero-actions{
      display:flex; gap:10px; flex-wrap:wrap;
      margin-top:16px;
    }
    .mini{
      display:flex; gap:10px; flex-wrap:wrap;
      margin-top:14px;
      color: var(--muted2);
      font-size: 13px;
    }
    .pill{
      padding:8px 10px;
      border:1px solid rgba(11,16,32,0.10);
      border-radius: 999px;
      background: rgba(255,255,255,0.72);
    }

    .side{
      padding:26px;
      display:flex;
      flex-direction:column;
      gap:14px;
      background: rgba(255,255,255,0.74);
    }
    .kicker{
      font-weight:950;
      letter-spacing:.25px;
      margin:0;
      color: rgba(139,92,246,0.95);
      font-size: 16px;
    }

    .info{
      display:flex; align-items:baseline; gap:10px;
      padding:14px 14px;
      border-radius: 18px;
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.78);
    }
    .info .big{ font-size: 15px; font-weight:900; color: var(--text); }
    .info .small{ font-size: 13px; color: var(--muted2); }

    section{ padding:18px 0; }
    .section-title{ margin:0 0 10px; font-size: 22px; letter-spacing:-0.2px; }
    .section-sub{ margin:0 0 18px; color: var(--muted); line-height: 1.75; }

    .cols{ display:grid; grid-template-columns: 1fr 1fr; gap:14px; }
    .block{
      border-radius: var(--radius);
      border:1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.72);
      padding:18px;
    }
    .block h3{ margin:0 0 10px; color: rgba(139,92,246,0.95); font-size: 17px; }

    .check{ margin:0; padding:0; list-style:none; display:grid; gap:8px; color: var(--muted); line-height:1.6; }
    .check li{ display:flex; gap:10px; align-items:flex-start; }
    .check li::before{ content:"✓"; color: rgba(139,92,246,0.95); font-weight:900; margin-top:1px; }

    .split{ display:grid; grid-template-columns: 1fr 1fr; gap:14px; align-items:stretch; }

    .cta{
      padding:28px;
      text-align:center;
      border-radius: calc(var(--radius) + 6px);
      background:
        radial-gradient(760px 360px at 50% 0%, rgba(255,208,234,0.65), transparent 65%),
        radial-gradient(900px 520px at 25% 90%, rgba(191,231,255,0.70), transparent 60%),
        radial-gradient(900px 520px at 80% 90%, rgba(215,204,255,0.70), transparent 60%),
        rgba(255,255,255,0.75);
      border:1px solid rgba(139,92,246,0.18);
      box-shadow: var(--shadow);
    }
    .cta h2{ margin:0 0 10px; font-size: 28px; letter-spacing:-0.25px; }
    .cta p{ margin:0 auto 14px; max-width: 760px; color: var(--muted); line-height:1.75; }

    .faq details{
      border-radius: 18px;
      border: 1px solid rgba(11,16,32,0.10);
      background: rgba(255,255,255,0.72);
      padding: 14px 14px;
    }
    .faq details + details{ margin-top:10px; }
    .faq summary{ cursor:pointer; font-weight:850; color: var(--text); }
    .faq .ans{ margin:10px 0 0; color: var(--muted); line-height:1.75; }

    footer{ padding:26px 0 40px; color: var(--muted2); font-size: 13px; }
    .footgrid{
      display:grid;
      grid-template-columns: 1fr auto;
      gap:12px;
      align-items:center;
      border-top: 1px solid rgba(11,16,32,0.10);
      padding-top: 18px;
    }

    @media (max-width: 920px){
      .grid{ grid-template-columns: 1fr; }
      .cols, .split{ grid-template-columns: 1fr; }
      .datepill{ display:none; }
      h1{ font-size: clamp(44px, 10vw, 64px); }
    }
  </style>
</head>

<body>

  <div class="topbar">
    <div class="wrap">
      <div class="inner">
        <div class="datepill" aria-label="Data do evento">
          <span class="dot" aria-hidden="true"></span>
          <span>19 e 20 de fevereiro • 20h</span>
        </div>
        <div style="display:flex; gap:10px; flex-wrap:wrap;">
          <a class="btn secondary" href="#conteudo">Ver conteúdo</a>
          <a class="btn" href="#inscricao">Quero participar</a>
        </div>
      </div>
    </div>
  </div>

  <header class="hero">
    <div class="wrap">
      <div class="grid">

        <div class="card pad">
          <div class="glow" aria-hidden="true"></div>

          <p class="sub">Workshop — 2 noites • 19 e 20 de fevereiro de 2026 • 20h</p>

          <h1 class="title-accent">RELACIONAMENTOS<br/>CONSCIENTES</h1>

          <p class="lead"><b style="color: rgba(139,92,246,0.95);">Do vínculo inconsciente ao encontro real</b></p>

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

          <div class="hero-actions">
            <a class="btn" href="#inscricao">Quero participar do workshop</a>
            <a class="btn secondary" href="#paraquem">É pra mim?</a>
          </div>

          <div class="mini">
            <span class="pill">Acolhimento • Consciência • Reposicionamento</span>
            <span class="pill">Sem exposição • Sem receita pronta</span>
          </div>
        </div>

        <aside class="card side" id="inscricao">
          <p class="kicker">Informações do evento</p>

          <div class="info">
            <div class="big">📅 Datas:</div>
            <div class="small"><b style="color: rgba(139,92,246,0.95);">19 e 20 de fevereiro de 2026</b></div>
          </div>

          <div class="info">
            <div class="big">⏰ Horário:</div>
            <div class="small"><b style="color: rgba(139,92,246,0.95);">20h</b></div>
          </div>

          <div class="info">
            <div class="big">⏳ Duração:</div>
            <div class="small"><b style="color: rgba(139,92,246,0.95);">3 a 4 horas por noite</b></div>
          </div>

          <div class="info">
            <div class="big">📍 Formato:</div>
            <div class="small"><b style="color: rgba(139,92,246,0.95);">[Online / Presencial]</b></div>
          </div>

          <p style="margin:6px 0 0; color:var(--muted); line-height:1.75;">
            Um workshop de duas noites para quem cansou de repetir padrões,
            se perder de si nos relacionamentos e deseja se relacionar a partir
            de um lugar mais consciente, adulto e verdadeiro.
          </p>

          <a class="btn"
             href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Quero%20participar%20do%20Workshop%20Relacionamentos%20Conscientes%20(19%20e%2020%2F02%2F2026%20%C3%A0s%2020h).%20Pode%20me%20enviar%20os%20detalhes%3F"
             target="_blank" rel="noopener">
            Receber detalhes no WhatsApp
          </a>

          <a class="btn secondary" href="#conteudo">Ver o que será trabalhado</a>
        </aside>

      </div>
    </div>
  </header>

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
          <p class="section-sub" style="margin-top:12px;" id="conteudo">
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

        <div class="cta" style="margin-top:14px;">
          <h2>Pronto(a) para sair da repetição?</h2>
          <p>
            Esse workshop não promete salvar relacionamentos.<br />
            Ele convida você a ocupar o seu lugar interno — e, a partir disso, viver um encontro mais real.
          </p>
          <div style="display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin-top:6px;">
            <a class="btn"
               href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Quero%20participar%20do%20Workshop%20Relacionamentos%20Conscientes%20(19%20e%2020%2F02%2F2026%20%C3%A0s%2020h).%20Pode%20me%20enviar%20os%20detalhes%3F"
               target="_blank" rel="noopener">
              Garantir minha participação
            </a>
            <a class="btn secondary" href="#inscricao">Ver informações</a>
          </div>
          <p style="margin:14px auto 0; max-width:760px; color:var(--muted2); font-size:13px; line-height:1.65;">
            Datas: <b style="color: rgba(139,92,246,0.95);">19 e 20/02/2026</b> • Horário: <b style="color: rgba(139,92,246,0.95);">20h</b>
          </p>
        </div>

      </div>
    </div>
  </section>

  <footer>
    <div class="wrap" style="padding-top:18px;">
      <div class="footgrid">
        <div>
          <div style="font-weight:900; color:var(--text);">Relacionamentos Conscientes</div>
          <div style="color:var(--muted2);">Do vínculo inconsciente ao encontro real</div>
          <div style="margin-top:6px; color:var(--muted2);">Contato:
            <a href="https://wa.me/5549998110445" target="_blank" rel="noopener">(49) 99811-0445</a>
          </div>
        </div>
        <div style="text-align:right;">
          <div>© <span id="year"></span> • Todos os direitos reservados</div>
          <div style="margin-top:6px;"><a href="#inscricao">Voltar ao topo</a></div>
        </div>
      </div>
    </div>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
