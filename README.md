
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />

  <!-- SEO (não aparece na página) -->
  <title>Workshop Relacionamentos Conscientes</title>

  <style>
    :root{
      --masculino:#0b1d2a;   /* azul profundo */
      --feminino:#2a0f1f;    /* vinho/rosé profundo */
      --encontro:#d6b56c;    /* dourado */
      --texto:#ffffff;
      --muted:rgba(255,255,255,.75);
      --stroke:rgba(255,255,255,.15);
      --radius:22px;
      --max:1100px;
    }

    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial;
      color:var(--texto);
      background:
        linear-gradient(120deg,
          var(--masculino) 0%,
          var(--masculino) 35%,
          var(--feminino) 65%,
          var(--feminino) 100%);
    }

    .luz{
      position:fixed;
      inset:0;
      background:
        radial-gradient(circle at 50% 30%,
          rgba(214,181,108,.35),
          transparent 55%);
      pointer-events:none;
      z-index:0;
    }

    .wrap{
      max-width:var(--max);
      margin:0 auto;
      padding:0 20px;
      position:relative;
      z-index:1;
    }

    header{
      padding:90px 0 70px;
      text-align:center;
    }

    h1{
      font-size: clamp(52px, 7vw, 84px);
      line-height:1.05;
      margin:0;
      letter-spacing:-1px;
      font-weight:900;
    }

    .sub{
      margin-top:20px;
      font-size:22px;
      color:var(--encontro);
      font-weight:700;
      letter-spacing:.4px;
    }

    .frase{
      margin:40px auto 0;
      max-width:760px;
      font-size:20px;
      line-height:1.6;
      color:var(--muted);
    }

    section{
      padding:50px 0;
    }

    .card{
      background:rgba(255,255,255,.06);
      border:1px solid var(--stroke);
      border-radius:var(--radius);
      padding:36px;
    }

    h2{
      margin-top:0;
      font-size:30px;
      color:var(--encontro);
    }

    ul{
      padding-left:20px;
      line-height:1.6;
      color:var(--muted);
    }

    .info{
      display:grid;
      grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
      gap:20px;
      margin-top:30px;
    }

    .box{
      padding:22px;
      border-radius:18px;
      background:rgba(0,0,0,.25);
      border:1px solid var(--stroke);
    }

    .btn{
      display:inline-block;
      margin-top:40px;
      padding:18px 36px;
      border-radius:999px;
      background:linear-gradient(180deg,#f0d79a,#caa14d);
      color:#1a1a1a;
      font-weight:800;
      text-decoration:none;
      font-size:18px;
    }

    footer{
      padding:40px 0;
      text-align:center;
      font-size:14px;
      color:var(--muted);
    }
  </style>
</head>

<body>
  <div class="luz"></div>

  <header>
    <div class="wrap">
      <h1>RELACIONAMENTOS<br>CONSCIENTES</h1>
      <div class="sub">Do vínculo inconsciente ao encontro real</div>

      <div class="frase">
        Relacionamento não é sobre encontrar alguém.<br>
        É sobre o lugar interno a partir do qual eu me relaciono.
      </div>
    </div>
  </header>

  <section>
    <div class="wrap">
      <div class="card">
        <h2>Sobre o workshop</h2>
        <p class="frase">
          Este workshop de duas noites foi criado para quem percebe que muda a pessoa,
          mas a história do relacionamento se repete.
          <br><br>
          Aqui, o foco não é o outro.
          É o lugar emocional de onde você se relaciona.
        </p>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap">
      <div class="card">
        <h2>O que será trabalhado</h2>
        <ul>
          <li>Padrões inconscientes nos relacionamentos</li>
          <li>Carência, expectativa e projeção</li>
          <li>O lugar adulto no vínculo</li>
          <li>Limites e comunicação consciente</li>
          <li>Clareza para sustentar, ajustar ou encerrar relações</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap">
      <div class="card">
        <h2>Informações do evento</h2>

        <div class="info">
          <div class="box">
            📅 <strong>Datas</strong><br>
            19 e 20 de fevereiro de 2026
          </div>
          <div class="box">
            ⏰ <strong>Horário</strong><br>
            20h
          </div>
          <div class="box">
            📍 <strong>Formato</strong><br>
            Online
          </div>
        </div>

        <a class="btn"
           href="https://wa.me/5549998110445?text=Olá! Quero participar do Workshop Relacionamentos Conscientes.">
          Quero participar
        </a>
      </div>
    </div>
  </section>

  <footer>
    © 2026 • Workshop Relacionamentos Conscientes
  </footer>
</body>
</html>
