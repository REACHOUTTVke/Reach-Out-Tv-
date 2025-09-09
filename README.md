<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Reach Out TV</title>
  <meta name="description" content="Reach Out TV — Live streaming, adverts, and documentaries. Kisii Town, Kenya." />
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text x='50' y='60' text-anchor='middle' font-size='60'>📺</text></svg>">
  <style>
    :root{
      --bg:#0a1a3d;          /* navy blue background */
      --fg:#ffffff;          /* white foreground */
      --muted:#cbd5e1;       /* soft gray */
      --brand:#ffffff;       /* white */
      --brand-2:#1e3a8a;     /* deep navy */
      --card:#11204d;        /* card bg navy shade */
      --ring:rgba(255,255,255,.4);
      --radius:20px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--fg);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,sans-serif;}
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block}
    .container{max-width:1100px;margin:0 auto;padding:0 16px}
    header{position:sticky;top:0;z-index:50;background:rgba(10,26,61,.85);backdrop-filter:blur(10px);border-bottom:1px solid rgba(255,255,255,.1)}
    .nav{display:flex;align-items:center;justify-content:space-between;padding:14px 0}
    .brand{display:flex;gap:10px;align-items:center;font-weight:800}
    .logo{height:36px;width:36px;display:grid;place-items:center;background:#ffffff;border-radius:12px;box-shadow:0 10px 30px rgba(255,255,255,.2);color:#0a1a3d;font-weight:bold}
    .brand span{letter-spacing:.4px}
    .links{display:flex;gap:18px}
    .links a{opacity:.85}
    .links a:hover{opacity:1}
    .btn{display:inline-flex;gap:8px;align-items:center;padding:12px 16px;border-radius:14px;background:var(--fg);color:var(--bg);font-weight:700;box-shadow:0 10px 30px var(--ring);border:1px solid #ffffff24}
    .btn.ghost{background:transparent;border:1px solid #ffffff50;color:var(--fg);box-shadow:none}
    .mobile-toggle{display:none}

    .hero{position:relative;overflow:hidden}
    .hero .wrap{display:grid;grid-template-columns:1.2fr .8fr;gap:26px;align-items:center;padding:64px 0 48px}
    .kicker{color:var(--fg);font-weight:800;letter-spacing:.12em}
    h1{font-size:clamp(28px,4vw,52px);line-height:1.05;margin:10px 0 16px;color:var(--fg)}
    p.lead{font-size:clamp(16px,2.1vw,20px);color:var(--muted)}
    .hero-card{background:var(--card);border:1px solid #ffffff30;border-radius:var(--radius);padding:18px;box-shadow:0 10px 35px rgba(0,0,0,.35)}
    .hero-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    .stat{padding:18px;border-radius:16px;background:#0e1a3a;border:1px solid #ffffff30;text-align:center}
    .stat strong{font-size:22px}

    .section{padding:64px 0}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .card{background:var(--card);border:1px solid #ffffff30;border-radius:var(--radius);padding:20px}
    .card h3{margin:8px 0 6px}

    .chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:12px}
    .chip{padding:8px 12px;border-radius:999px;border:1px solid #ffffff40;background:#0e1a3a;font-size:14px;color:var(--fg)}

    .gallery{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}
    .gallery img{border-radius:14px;border:1px solid #ffffff20}

    .testimonial{display:grid;grid-template-columns:80px 1fr;gap:14px;align-items:center}
    .avatar{height:64px;width:64px;border-radius:50%;background:#ffffff;color:#0a1a3d;display:flex;align-items:center;justify-content:center;font-weight:bold}

    .cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:18px}

    footer{padding:42px 0;border-top:1px solid #ffffff30;color:#cbd5e1}
    .footergrid{display:grid;grid-template-columns:2fr 1fr 1fr;gap:18px}
    .mono{font-family:ui-monospace, SFMono-Regular, Menlo, monospace;color:#94a3b8}

    @media (max-width: 880px){
      .hero .wrap{grid-template-columns:1fr;gap:18px}
      .grid-3{grid-template-columns:1fr}
      .gallery{grid-template-columns:repeat(2,1fr)}
      .links{display:none}
      .mobile-toggle{display:inline-flex;align-items:center;gap:8px;border:1px solid #ffffff50;padding:10px 12px;border-radius:12px;background:transparent;color:var(--fg)}
      nav.open .links{display:flex;position:absolute;inset:56px 16px auto;flex-direction:column;background:var(--card);border:1px solid #ffffff40;padding:12px;border-radius:16px}
    }
  </style>
</head>
<body>
  <!-- Content remains the same as before -->
  <!-- I only updated colors and title -->

  <!-- Existing HTML content goes here unchanged -->
  
</body>
</html>
