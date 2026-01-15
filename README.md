
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Workshop — Relacionamentos Conscientes</title>
  <meta name="description" content="Workshop de duas noites: Relacionamentos Conscientes — Do vínculo inconsciente ao encontro real." />

  <!-- Open Graph -->
  <meta property="og:title" content="Workshop — Relacionamentos Conscientes" />
  <meta property="og:description" content="Do vínculo inconsciente ao encontro real. Relacionamento não é sobre encontrar alguém. É sobre o lugar interno a partir do qual eu me relaciono." />
  <meta property="og:type" content="website" />

  <style>
    :root{
      --bg: #07160f;
      --card: rgba(255,255,255,0.06);
      --card2: rgba(255,255,255,0.08);
      --stroke: rgba(255,255,255,0.12);
      --text: rgba(255,255,255,0.92);
      --muted: rgba(255,255,255,0.72);
      --muted2: rgba(255,255,255,0.58);
      --gold: #d9b15f;
      --gold2:#f1d79a;
      --brand:#014D26; /* verde oficial */
      --shadow: 0 18px 60px rgba(0,0,0,.45);
      --radius: 22px;
      --max: 1100px;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      color:var(--text);
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      background:
        radial-gradient(900px 600px at 20% 10%, rgba(217,177,95,0.18), transparent 60%),
        radial-gradient(900px 600px at 80% 30%, rgba(1,77,38,0.35), transparent 55%),
        radial-gradient(1200px 800px at 50% 100%, rgba(255,255,255,0.06), transparent 60%),
        linear-gradient(180deg, #05120c 0%, #07160f 50%, #04110b 100%);
      overflow-x:hidden;
    }

    a{color:inherit}
    .wrap{max-width:var(--max); margin:0 auto; padding:0 18px}
    .topbar{
      position:sticky; top:0; z-index:20;
      backdrop-filter: blur(10px);
      background: rgba(5,18,12,.65);
      border-bottom: 1px solid var(--stroke);
    }
    .topbar .inner{
      display:flex; align-items:center; justify-content:space-between;
      gap:14px; padding:12px 0;
    }
    .badge{
      display:inline-flex; align-items:center; gap:10px;
      padding:10px 12px;
      border:1px solid var(--stroke);
      border-radius:999px;
      background: rgba(255,255,255,0.04);
    }
    .dot{
      width:10px; height:10px; border-radius:999px;
      background: radial-gradient(circle at 30% 30%, var(--gold2), var(--gold));
      box-shadow: 0 0 0 6px rgba(217,177,95,0.12);
    }
    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      padding:12px 16px;
      border-radius:999px;
      border:1px solid rgba(217,177,95,0.35);
      background: linear-gradient(180deg, rgba(217,177,95,0.22), rgba(217,177,95,0.10));
      color: var(--text);
      text-decoration:none;
      font-weight:700;
      letter-spacing:.2px;
      transition: transform .15s ease, background .15s ease, border-color .15s ease;
      box-shadow: 0 10px 24px rgba(0,0,0,.25);
      cursor:pointer;
    }
    .btn:hover{ transform: translateY(-1px); border-color: rgba(217,177,95,0.6); }
    .btn.secondary{
      border-color: var(--stroke);
      background: rgba(255,255,255,0.06);
      font-weight:650;
      box-shadow:none;
    }
    .btn.secondary:hover{ transform: translateY(-1px); background: rgba(255,255,255,0.08); }
    .hero{
      padding:48px 0 18px;
    }
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
    .card.pad{ padding:22px; }
    .glow{
      position:absolute; inset:-60px -80px auto auto;
      width:300px; height:300px;
      background: radial-gradient(circle at 30% 30%, rgba(241,215,154,0.25), transparent 60%);
      filter: blur(1px);
      pointer-events:none;
    }
    h1{
      margin:0 0 10px;
      font-size: clamp(30px, 4.2vw, 44px);
      line-height: 1.06;
      letter-spacing: -0.6px;
    }
    .sub{
      margin:0 0 16px;
      color: var(--gold2);
      font-weight:700;
      letter-spacing:.3px;
    }
    .lead{
      margin:0 0 14px;
      font-size: 16px;
      color: var(--muted);
      line-height: 1.55;
    }
    .quote{
      margin:18px 0 0;
      padding:16px 16px;
      border-radius: 18px;
      background: rgba(0,0,0,0.18);
      border: 1px solid rgba(217,177,95,0.18);
    }
    .quote b{ color: var(--gold2); }
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
      border:1px solid var(--stroke);
      border-radius: 999px;
      background: rgba(255,255,255,0.04);
    }

    .side{
      padding:22px;
      display:flex;
      flex-direction:column;
      gap:14px;
    }
    .kicker{
      font-weight:800;
      letter-spacing:.25px;
      margin:0;
      color: var(--gold2);
    }
    .list{
      margin:0; padding:0 0 0 18px;
      color: var(--muted);
      line-height: 1.55;
    }
    .price{
      display:flex; align-items:baseline; gap:10px;
      padding:14px 14px;
      border-radius: 18px;
      border:1px solid rgba(255,255,255,0.12);
      background: rgba(255,255,255,0.05);
    }
    .price .big{ font-size: 18px; font-weight:800; color: var(--text); }
    .price .small{ font-size: 13px; color: var(--muted2); }

    section{ padding:18px 0; }
    .section-title{
      margin:0 0 10px;
      font-size: 22px;
      letter-spacing:-0.2px;
    }
    .section-sub{
      margin:0 0 18px;
      color: var(--muted);
      line-height: 1.6;
    }

    .cols{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:14px;
    }
    .block{
      border-radius: var(--radius);
      border:1px solid var(--stroke);
      background: rgba(255,255,255,0.05);
      padding:18px;
    }
    .block h3{
      margin:0 0 10px;
      color: var(--gold2);
      font-size: 17px;
      letter-spacing:-0.1px;
    }
    .block p{
      margin:0 0 10px;
      color: var(--muted);
      line-height:1.6;
    }
    .check{
      margin:0; padding:0; list-style:none;
      display:grid; gap:8px;
      color: var(--muted);
      line-height:1.45;
    }
    .check li{
      display:flex; gap:10px; align-items:flex-start;
    }
    .check li::before{
      content:"✓";
      color: var(--gold2);
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
      padding:26px;
      text-align:center;
      border-radius: calc(var(--radius) + 6px);
      background:
        radial-gradient(600px 300px at 50% 0%, rgba(217,177,95,0.25), transparent 65%),
        linear-gradient(180deg, rgba(255,255,255,0.08), rgba(255,255,255,0.04));
      border:1px solid rgba(217,177,95,0.22);
      box-shadow: var(--shadow);
    }
    .cta h2{
      margin:0 0 8px;
      font-size: 26px;
      letter-spacing:-0.25px;
    }
    .cta p{
      margin:0 auto 14px;
      max-width: 760px;
      color: var(--muted);
      line-height:1.6;
    }

    .faq details{
      border-radius: 18px;
      border: 1px solid var(--stroke);
      background: rgba(255,255,255,0.05);
      padding: 14px 14px;
    }
    .faq details + details{ margin-top:10px; }
    .faq summary{
      cursor:pointer;
      font-weight:750;
      color: var(--text);
    }
    .faq .ans{
      margin:10px 0 0;
      color: var(--muted);
      line-height:1.6;
    }

    footer{
      padding:26px 0 40px;
      color: var(--muted2);
      font-size: 13px;
    }
    .footgrid{
      display:grid;
      grid-template-columns: 1fr auto;
      gap:12px;
      align-items:center;
      border-top: 1px solid var(--stroke);
      padding-top: 18px;
    }

    /* responsive */
    @media (max-width: 920px){
      .grid{ grid-template-columns: 1fr; }
      .cols, .split{ grid-template-columns: 1fr; }
    }
  </style>
</head>

<body>

  <!-- TOPBAR -->
  <div class="topbar">
    <div class="wrap">
      <div class="inner">
        <div class="badge" aria-label="Identificação do evento">
          <span class="dot" aria-hidden="true"></span>
          <strong>Workshop • Relacionamentos Conscientes</strong>
        </div>
        <div style="display:flex; gap:10px; flex-wrap:wrap;">
          <a class="btn secondary" href="#conteudo">Ver conteúdo</a>
          <!-- TROQUE O LINK DO BOTÃO AQUI (WhatsApp / Checkout / Formulário) -->
          <a class="btn" href="#inscricao">Quero participar</a>
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

          <p class="sub">WORKSHOP — 2 NOITES</p>
          <h1>RELACIONAMENTOS CONSCIENTES</h1>
          <p class="lead"><b>Do vínculo inconsciente ao encontro real</b></p>

          <div class="quote">
            <div style="color:var(--muted); line-height:1.6;">
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

          <!-- EDITE ABAIXO COM DATAS / HORÁRIOS / FORMATO -->
          <div class="price">
            <div class="big">📅 Datas: <span style="color:var(--gold2);">[coloque aqui]</span></div>
          </div>
          <div class="price">
            <div class="big">⏰ Horário: <span style="color:var(--gold2);">[coloque aqui]</span></div>
          </div>
          <div class="price">
            <div class="big">📍 Formato: <span style="color:var(--gold2);">[Online / Presencial]</span></div>
          </div>
          <div class="price">
            <div class="big">⏳ Duração: <span style="color:var(--gold2);">3 a 4 horas por noite</span></div>
            <div class="small">2 noites • Conteúdo + vivências</div>
          </div>

          <p style="margin:6px 0 0; color:var(--muted); line-height:1.6;">
            Este workshop é um portal de consciência para você reorganizar o seu lugar interno e,
            a partir disso, viver relações mais maduras, leves e verdadeiras.
          </p>

          <!-- TROQUE O LINK DO BOTÃO PRINCIPAL AQUI -->
          <a class="btn" href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Quero%20participar%20do%20Workshop%20Relacionamentos%20Conscientes.%20Pode%20me%20enviar%20os%20detalhes%3F" target="_blank" rel="noopener">
            Falar no WhatsApp e receber detalhes
          </a>

          <a class="btn secondary" href="#conteudo">Ver o que será trabalhado</a>

          <p style="margin:0; color:var(--muted2); font-size:13px; line-height:1.5;">
            *Dica:* deixe esse botão levar para o seu checkout ou formulário. WhatsApp funciona muito bem para fechar.
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
          Você ama, tenta, conversa, se adapta… e mesmo assim algo sempre dói?
          <br />Talvez você não esteja vivendo um problema de “relacionamento”.
          <br />Talvez esteja vivendo um problema de <b>lugar emocional</b>.
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

  <!-- O QUE É -->
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

        <div class="card pad" id="conteudo">
          <h2 class="section-title">A virada central</h2>
          <p class="section-sub" style="margin-bottom:10px;">
            A maioria das pessoas entra em relacionamentos a partir de lugares inconscientes:
            carência, medo de abandono, necessidade de aprovação ou tentativa de preencher vazios emocionais.
          </p>
          <div class="quote" style="margin:0;">
            <div style="color:var(--muted); line-height:1.6;">
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

  <!-- 2 NOITES -->
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
            <p><b>Objetivo:</b> entender por que dói e por que se repete.</p>
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
            <p><b>Objetivo:</b> saber o que fazer a partir de agora.</p>
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
          Seu trabalho é ajudar pessoas a se reposicionarem internamente, organizando o lugar emocional
          que sustenta decisões, vínculos e escolhas — para viver relações mais conscientes, leves e verdadeiras.
        </p>

        <div class="quote">
          <div style="color:var(--muted); line-height:1.6;">
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
          <a class="btn" href="https://wa.me/5549998110445?text=Ol%C3%A1!%20Quero%20participar%20do%20Workshop%20Relacionamentos%20Conscientes.%20Pode%20me%20enviar%20os%20detalhes%3F" target="_blank" rel="noopener">
            Garantir minha participação
          </a>
          <a class="btn secondary" href="#conteudo">Ver conteúdo completo</a>
        </div>

        <p style="margin:14px auto 0; max-width:760px; color:var(--muted2); font-size:13px; line-height:1.55;">
          *Troque o link do botão para seu checkout, formulário ou página de pagamento, se preferir.*
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
          <div style="font-weight:750; color:var(--text);">Workshop — Relacionamentos Conscientes</div>
          <div>Do vínculo inconsciente ao encontro real</div>
          <div style="margin-top:6px;">Contato: <a href="https://wa.me/5549998110445" target="_blank" rel="noopener">(49) 99811-0445</a></div>
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
