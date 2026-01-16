
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Relacionamentos Conscientes | Workshop</title>
  <meta name="description" content="Workshop de duas noites: Relacionamentos Conscientes — Do vínculo inconsciente ao encontro real. 19 e 20 de fevereiro de 2026 às 20h." />

  <!-- Open Graph -->
  <meta property="og:title" content="Relacionamentos Conscientes | Workshop" />
  <meta property="og:description" content="Do vínculo inconsciente ao encontro real. Relacionamento não é sobre encontrar alguém. É sobre o lugar interno a partir do qual eu me relaciono." />
  <meta property="og:type" content="website" />

  <style>
    :root{
      /* Paleta masculino + feminino (mais atrativa) */
      --masc: #0b2a5b;       /* azul safira */
      --fem:  #7a175f;       /* magenta profundo */
      --violet:#3a1b6f;      /* roxo de ligação */
      --gold: #d9b15f;
      --gold2:#f4dfad;

      --card: rgba(255,255,255,0.075);
      --card2: rgba(255,255,255,0.10);
      --stroke: rgba(255,255,255,0.14);

      --text: rgba(255,255,255,0.94);
      --muted: rgba(255,255,255,0.76);
      --muted2: rgba(255,255,255,0.60);

      --shadow: 0 18px 60px rgba(0,0,0,.45);
      --radius: 22px;
      --max: 1140px;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      color:var(--text);
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      /* FUNDO MAIS “VIVO” + PROFUNDO */
      background:
        radial-gradient(900px 650px at 18% 25%, rgba(11,42,91,0.95), transparent 62%),
        radial-gradient(900px 650px at 82% 30%, rgba(122,23,95,0.92), transparent 64%),
        radial-gradient(900px 650px at 50% 12%, rgba(58,27,111,0.65), transparent 60%),
        radial-gradient(700px 520px at 50% 0%, rgba(217,177,95,0.22), transparent 60%),
        linear-gradient(180deg, #050716 0%, #050414 55%, #040212 100%);
      overflow-x:hidden;
    }

    a{color:inherit}
    .wrap{max-width:var(--max); margin:0 auto; padding:0 18px}

    /* IMPORTANTE: garantir que não exista “título fantasma” acima */
    body > h1,
    body > header:not(.hero){
      display:none !important;
    }

    /* Topbar (sem qualquer título extra) */
    .topbar{
      position:sticky; top:0; z-index:20;
      backdrop-filter: blur(10px);
      background: rgba(5,6,18,.58);
      border-bottom: 1px solid var(--stroke);
    }
    .topbar .inner{
      display:flex; align-items:center; justify-content:space-between;
      gap:14px; padding:12px 0;
    }
    .brandline{
      display:flex; align-items:center; gap:10px;
      color: var(--muted2);
      font-weight:650;
      letter-spacing:.2px;
      user-select:none;
      white-space:nowrap;
    }
    .dot{
      width:10px; height:10px; border-radius:999px;
      background: radial-gradient(circle at 30% 30%, var(--gold2), var(--gold));
      box-shadow: 0 0 0 6px rgba(217,177,95,0.12);
      flex:0 0 auto;
    }

    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      padding:12px 16px;
      border-radius:999px;
      border:1px solid rgba(217,177,95,0.45);
      background: linear-gradient(180deg, rgba(217,177,95,0.24), rgba(217,177,95,0.10));
      color: var(--text);
      text-decoration:none;
      font-weight:850;
      letter-spacing:.2px;
      transition: transform .15s ease, background .15s ease, border-color .15s ease, box-shadow .15s ease;
      box-shadow: 0 10px 26px rgba(0,0,0,.30);
      cursor:pointer;
    }
    .btn:hover{
      transform: translateY(-1px);
      border-color: rgba(217,177,95,0.75);
      box-shadow: 0 14px 34px rgba(0,0,0,.34);
    }
    .btn.secondary{
      border-color: var(--stroke);
      background: rgba(255,255,255,0.06);
      font-weight:750;
      box-shadow:none;
    }
    .btn.secondary:hover{ transform: translateY(-1px); background: rgba(255,255,255,0.08); }

    .hero{ padding:54px 0 18px; }
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
      position:absolute; inset:-80px -90px auto auto;
      width:360px; height:360px;
      background: radial-gradient(circle at 30% 30%, rgba(244,223,173,0.28), transparent 62%);
      pointer-events:none;
      filter: blur(0.6px);
    }

    .sub{
      margin:0 0 14px;
      color: var(--gold2);
      font-weight:900;
      letter-spacing:.35px;
      text-transform:uppercase;
      font-size: 13px;
    }

    /* Título maior e com melhor respiro */
    h1{
      margin:0 0 12px;
      font-size: clamp(42px, 5.8vw, 72px);
      line-height: 1.03;
      letter-spacing: -1.05px;
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
      background: rgba(0,0,0,0.22);
      border: 1px solid rgba(217,177,95,0.22);
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
      background: linear-gradient(180deg, rgba(255,255,255,0.08), rgba(255,255,255,0.05));
    }
    .kicker{
      font-weight:950;
      letter-spacing:.25px;
      margin:0;
      color: var(--gold2);
      font-size: 16px;
    }

    .info{
      display:flex; align-items:baseline; gap:10px;
      padding:14px 14px;
      border-radius: 18px;
      border:1px
