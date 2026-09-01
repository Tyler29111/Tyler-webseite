<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tyler Tweaks — Maximiere die Leistung deines PCs</title>
<meta name="description" content="Professionelle PC-Optimierung und das Tyler Tweaks Tool für maximale Gaming-Performance.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #06070a;
    --bg-alt: #0a0c11;
    --surface: #12151b;
    --surface-2: #171b23;
    --border: rgba(255,255,255,0.09);
    --border-strong: rgba(255,255,255,0.16);
    --neon: #35e2ff;
    --neon-dim: #35e2ff66;
    --neon-2: #5b7bff;
    --text: #eef1f6;
    --text-muted: #98a1b3;
    --text-dim: #5c6577;
    --danger: #ff5b5b;
    --radius-sharp: 3px;
    --radius-pill: 999px;
    --maxw: 1180px;
  }

  *{ box-sizing: border-box; }
  html{ scroll-behavior: smooth; }
  @media (prefers-reduced-motion: reduce){
    html{ scroll-behavior: auto; }
    *{ animation-duration: 0.001ms !important; animation-iteration-count: 1 !important; transition-duration: 0.001ms !important; scroll-behavior: auto !important; }
  }

  body{
    margin:0;
    background: var(--bg);
    color: var(--text);
    font-family: 'Inter', sans-serif;
    -webkit-font-smoothing: antialiased;
    overflow-x: hidden;
  }

  h1,h2,h3,h4{
    font-family: 'Space Grotesk', sans-serif;
    margin: 0;
    letter-spacing: -0.01em;
  }

  a{ color: inherit; text-decoration: none; }
  ul{ list-style: none; margin:0; padding:0; }
  img{ max-width: 100%; display:block; }

  .wrap{
    max-width: var(--maxw);
    margin: 0 auto;
    padding: 0 28px;
  }

  section{ position: relative; padding: 120px 0; }
  @media (max-width: 760px){ section{ padding: 84px 0; } }

  .eyebrow-line{
    display:flex;
    align-items:center;
    gap: 12px;
    margin-bottom: 18px;
  }
  .eyebrow-line span{
    font-size: 13px;
    color: var(--text-dim);
    font-family: 'JetBrains Mono', monospace;
  }
  .eyebrow-line .dash{
    width: 28px; height: 1px;
    background: var(--neon);
    box-shadow: 0 0 8px var(--neon);
  }

  .section-title{
    font-size: clamp(28px, 3.4vw, 42px);
    line-height: 1.15;
    font-weight: 600;
    max-width: 640px;
  }
  .section-lede{
    color: var(--text-muted);
    font-size: 17px;
    line-height: 1.65;
    max-width: 560px;
    margin-top: 16px;
  }

  /* ---------- reveal ---------- */
  .rv{ opacity: 0; transform: translateY(22px); transition: opacity .7s cubic-bezier(.2,.7,.2,1), transform .7s cubic-bezier(.2,.7,.2,1); }
  .rv.rv-left{ transform: translateX(-24px); }
  .rv.rv-right{ transform: translateX(24px); }
  .rv.is-visible{ opacity: 1; transform: none; }

  /* ---------- nav ---------- */
  header.nav{
    position: fixed; top:0; left:0; right:0; z-index: 500;
    background: rgba(6,7,10,0.72);
    backdrop-filter: blur(14px);
    border-bottom: 1px solid transparent;
    transition: border-color .3s ease, background .3s ease;
  }
  header.nav.scrolled{ border-bottom-color: var(--border); background: rgba(6,7,10,0.92); }
  .nav-inner{
    max-width: var(--maxw); margin: 0 auto; padding: 0 28px;
    height: 76px; display:flex; align-items:center; justify-content:space-between;
  }
  .logo{
    font-family: 'Space Grotesk', sans-serif; font-weight: 700; font-size: 19px;
    display:flex; align-items:center; gap:10px; letter-spacing: 0.01em;
  }
  .logo .dot{
    width: 8px; height: 8px; border-radius: 50%;
    background: var(--neon); box-shadow: 0 0 10px 2px var(--neon);
    flex-shrink:0;
  }
  nav.links{ display:flex; align-items:center; gap: 34px; }
  nav.links a{
    font-size: 14.5px; color: var(--text-muted); font-weight: 500;
    position: relative; padding: 4px 0; transition: color .2s ease;
  }
  nav.links a::after{
    content:''; position:absolute; left:0; bottom:-2px; width:0; height:1px;
    background: var(--neon); transition: width .25s ease; box-shadow: 0 0 6px var(--neon);
  }
  nav.links a:hover{ color: var(--text); }
  nav.links a:hover::after{ width: 100%; }

  .btn{
    display: inline-flex; align-items:center; justify-content:center; gap:8px;
    padding: 13px 26px; border-radius: var(--radius-pill);
    font-weight: 600; font-size: 14.5px; cursor:pointer;
    border: 1px solid transparent; transition: transform .18s ease, box-shadow .25s ease, background .25s ease, border-color .25s ease;
    white-space: nowrap;
  }
  .btn:active{ transform: scale(0.97); }
  .btn-primary{
    background: linear-gradient(135deg, var(--neon), var(--neon-2));
    color: #04060a;
    box-shadow: 0 0 0 rgba(53,226,255,0);
  }
  .btn-primary:hover{ box-shadow: 0 6px 30px -6px var(--neon-dim), 0 0 20px -4px var(--neon); transform: translateY(-1px); }
  .btn-ghost{
    background: transparent; color: var(--text); border-color: var(--border-strong);
  }
  .btn-ghost:hover{ border-color: var(--neon); color: var(--neon); box-shadow: 0 0 18px -6px var(--neon); }
  .btn-sm{ padding: 10px 20px; font-size: 13.5px; }
  .btn-full{ width: 100%; }

  .nav-cta{ display:flex; align-items:center; gap: 14px; }
  .burger{ display:none; flex-direction:column; gap:5px; cursor:pointer; background:none; border:none; padding:6px; }
  .burger span{ width:22px; height:2px; background: var(--text); transition: all .25s ease; }

  @media (max-width: 900px){
    nav.links{ display:none; }
    .nav-cta .btn-ghost{ display:none; }
    .burger{ display:flex; }
  }

  .mobile-menu{
    position: fixed; inset: 76px 0 0 0; z-index: 480;
    background: rgba(6,7,10,0.98);
    display:flex; flex-direction:column; padding: 32px 28px;
    gap: 4px;
    transform: translateY(-8px); opacity:0; pointer-events:none;
    transition: transform .3s ease, opacity .3s ease;
  }
  .mobile-menu.open{ transform: translateY(0); opacity:1; pointer-events:all; }
  .mobile-menu a{
    padding: 16px 4px; font-size: 19px; font-weight: 500; color: var(--text);
    border-bottom: 1px solid var(--border);
  }
  .mobile-menu .btn{ margin-top: 20px; }

  /* ---------- bracket frame (signature HUD element) ---------- */
  .bracket{
    position: relative;
    border: 1px solid var(--border);
    border-radius: var(--radius-sharp);
    background: var(--surface);
  }
  .bracket::before, .bracket::after,
  .bracket .bk-tl, .bracket .bk-br{ content:''; }
  .bracket::before{
    position:absolute; top:-1px; left:-1px; width:16px; height:16px;
    border-top: 2px solid var(--neon); border-left: 2px solid var(--neon);
    opacity: 0; transition: opacity .3s ease;
  }
  .bracket::after{
    position:absolute; bottom:-1px; right:-1px; width:16px; height:16px;
    border-bottom: 2px solid var(--neon); border-right: 2px solid var(--neon);
    opacity: 0; transition: opacity .3s ease;
  }
  .bracket:hover::before, .bracket:hover::after{ opacity: 1; }
  .bracket.always-on::before, .bracket.always-on::after{ opacity: 1; }

  /* ---------- hero ---------- */
  .hero{
    padding-top: 190px; padding-bottom: 120px;
    min-height: 92vh; display:flex; align-items:center;
    position: relative; overflow: hidden;
  }
  .hero-bg{
    position:absolute; inset:0; z-index:0;
    background-image:
      linear-gradient(rgba(53,226,255,0.055) 1px, transparent 1px),
      linear-gradient(90deg, rgba(53,226,255,0.055) 1px, transparent 1px);
    background-size: 46px 46px;
    mask-image: radial-gradient(ellipse 70% 60% at 30% 30%, black 20%, transparent 75%);
  }
  .hero-glow{
    position:absolute; z-index:0; width: 620px; height: 620px; border-radius:50%;
    background: radial-gradient(circle, rgba(53,226,255,0.16), transparent 65%);
    top: -180px; right: -160px; pointer-events:none;
    filter: blur(10px);
  }
  .hero-grid{
    display:grid; grid-template-columns: 1.15fr 0.85fr; gap: 60px; align-items:center;
    position: relative; z-index: 2;
  }
  @media (max-width: 980px){ .hero-grid{ grid-template-columns: 1fr; } }

  .hero-tag{
    display:inline-flex; align-items:center; gap:10px;
    font-family:'JetBrains Mono', monospace; font-size: 12.5px; color: var(--neon);
    border: 1px solid var(--neon-dim); padding: 7px 14px; border-radius: var(--radius-pill);
    margin-bottom: 26px; background: rgba(53,226,255,0.06);
  }
  .hero-tag .blip{ width:6px; height:6px; border-radius:50%; background: var(--neon); box-shadow:0 0 8px var(--neon); animation: blip 1.6s ease-in-out infinite; }
  @keyframes blip{ 0%,100%{ opacity:1; } 50%{ opacity:.25; } }

  .hero h1{
    font-size: clamp(38px, 5.6vw, 66px);
    line-height: 1.06;
    font-weight: 700;
    max-width: 15ch;
  }
  .hero h1 .accent{
    background: linear-gradient(135deg, var(--neon), var(--neon-2));
    -webkit-background-clip: text; background-clip:text; color: transparent;
  }
  .hero p.sub{
    margin-top: 26px; font-size: 18px; color: var(--text-muted); line-height: 1.65; max-width: 46ch;
  }
  .hero-actions{ display:flex; gap: 16px; margin-top: 40px; flex-wrap: wrap; }

  .hero-stats{ display:flex; gap: 36px; margin-top: 56px; flex-wrap: wrap; }
  .hero-stat b{ display:block; font-family:'Space Grotesk',sans-serif; font-size: 26px; color: var(--text); }
  .hero-stat span{ font-size: 13px; color: var(--text-dim); }

  /* hero HUD panel */
  .hud-panel{ padding: 26px; }
  .hud-row{ display:flex; justify-content:space-between; align-items:center; margin-bottom: 22px; }
  .hud-row .hud-label{ font-family:'JetBrains Mono',monospace; font-size: 11.5px; color: var(--text-dim); }
  .hud-row .hud-status{ font-family:'JetBrains Mono',monospace; font-size: 11.5px; color: var(--neon); display:flex; align-items:center; gap:6px; }
  .hud-status .dot{ width:6px;height:6px;border-radius:50%; background: var(--neon); box-shadow:0 0 6px var(--neon); }

  .meter-block{ margin-bottom: 20px; }
  .meter-top{ display:flex; justify-content:space-between; font-size: 13px; color: var(--text-muted); margin-bottom: 8px; }
  .meter-top b{ color: var(--text); font-family:'Space Grotesk',sans-serif; font-size:15px; }
  .meter-track{ height: 6px; background: var(--surface-2); border-radius: 4px; overflow:hidden; }
  .meter-fill{ height:100%; border-radius:4px; background: linear-gradient(90deg, var(--neon-2), var(--neon)); width:0%; transition: width 1.4s cubic-bezier(.2,.8,.2,1); box-shadow: 0 0 10px var(--neon-dim); }

  .fps-counter{
    display:flex; align-items:baseline; gap:10px; justify-content:center;
    padding: 24px 0 8px; border-top: 1px solid var(--border); margin-top: 8px;
  }
  .fps-counter .num{ font-family:'Space Grotesk',sans-serif; font-size: 52px; font-weight:700; color: var(--neon); text-shadow: 0 0 24px var(--neon-dim); }
  .fps-counter .lbl{ font-size: 13px; color: var(--text-dim); font-family:'JetBrains Mono',monospace; }

  /* ---------- about ---------- */
  .about-grid{ display:grid; grid-template-columns: 1fr 1fr; gap: 70px; align-items:start; }
  @media (max-width: 860px){ .about-grid{ grid-template-columns: 1fr; gap: 40px; } }
  .about-body p{ color: var(--text-muted); font-size: 16.5px; line-height: 1.75; margin: 0 0 18px; }
  .about-body p:last-child{ margin-bottom:0; }
  .about-points{ display:flex; flex-direction:column; gap: 22px; }
  .about-point{ display:flex; gap:16px; align-items:flex-start; padding: 20px; }
  .about-point .num{ font-family:'JetBrains Mono',monospace; color: var(--neon); font-size: 13px; padding-top:2px; }
  .about-point h4{ font-size: 16px; margin-bottom: 6px; }
  .about-point p{ color: var(--text-muted); font-size: 14.5px; line-height:1.6; margin:0; }

  /* ---------- pricing ---------- */
  .pricing-grid{ display:grid; grid-template-columns: repeat(3, 1fr); gap: 26px; margin-top: 56px; }
  @media (max-width: 980px){ .pricing-grid{ grid-template-columns: 1fr; max-width: 460px; margin-left:auto; margin-right:auto; } }

  .price-card{
    padding: 34px 28px; display:flex; flex-direction:column;
    transition: transform .3s ease, border-color .3s ease;
  }
  .price-card:hover{ transform: translateY(-6px); border-color: var(--border-strong); }
  .price-card.featured{
    border-color: var(--neon-dim);
    background: linear-gradient(180deg, rgba(53,226,255,0.07), var(--surface) 40%);
    position: relative;
  }
  .price-card.featured:hover{ transform: translateY(-10px); }
  .badge-pop{
    position:absolute; top:-13px; left: 28px;
    background: linear-gradient(135deg, var(--neon), var(--neon-2));
    color:#04060a; font-size:11.5px; font-weight:700; letter-spacing:0.02em;
    padding: 6px 14px; border-radius: var(--radius-pill);
    box-shadow: 0 4px 18px -4px var(--neon-dim);
  }
  .price-name{ font-size: 20px; font-weight:600; margin-bottom: 10px; }
  .price-desc{ color: var(--text-muted); font-size: 14px; line-height:1.6; margin-bottom: 22px; min-height: 42px; }
  .price-value{ display:flex; align-items:baseline; gap:8px; margin-bottom: 26px; }
  .price-value .amount{ font-family:'Space Grotesk',sans-serif; font-size: 38px; font-weight:700; }
  .price-value .period{ color: var(--text-dim); font-size: 13px; }
  .price-value.tbd .amount{ font-size: 22px; color: var(--text-muted); }
  .price-list{ display:flex; flex-direction:column; gap:12px; margin-bottom: 28px; flex-grow:1; }
  .price-list li{ display:flex; gap:10px; align-items:flex-start; font-size: 14.5px; color: var(--text); }
  .price-list li svg{ flex-shrink:0; margin-top:3px; color: var(--neon); }

  /* ---------- steps ---------- */
  .steps-rail{ position:relative; margin-top: 60px; }
  .steps-grid{ display:grid; grid-template-columns: repeat(4,1fr); gap: 24px; position:relative; }
  @media (max-width: 900px){ .steps-grid{ grid-template-columns: 1fr 1fr; } }
  @media (max-width: 560px){ .steps-grid{ grid-template-columns: 1fr; } }
  .step-card{ padding: 28px 22px; position:relative; }
  .step-num{
    font-family:'Space Grotesk',sans-serif; font-size: 34px; font-weight:700;
    color: transparent; -webkit-text-stroke: 1.4px var(--neon-dim);
    margin-bottom: 16px; display:block;
  }
  .step-card h4{ font-size: 16.5px; margin-bottom: 8px; }
  .step-card p{ color: var(--text-muted); font-size: 14px; line-height:1.6; margin:0; }
  .step-arrow{
    position:absolute; top: 50%; right:-24px; transform: translateY(-50%);
    color: var(--text-dim); font-size: 18px; z-index:2;
  }
  @media (max-width: 900px){ .step-arrow{ display:none; } }

  /* ---------- why cards ---------- */
  .why-grid{ display:grid; grid-template-columns: repeat(3, 1fr); gap: 22px; margin-top: 56px; }
  @media (max-width: 900px){ .why-grid{ grid-template-columns: 1fr 1fr; } }
  @media (max-width: 600px){ .why-grid{ grid-template-columns: 1fr; } }
  .why-card{ padding: 30px 26px; transition: transform .3s ease, border-color .3s ease; }
  .why-card:hover{ transform: translateY(-5px); border-color: var(--border-strong); }
  .why-icon{
    width: 44px; height:44px; border-radius: var(--radius-sharp);
    display:flex; align-items:center; justify-content:center;
    background: rgba(53,226,255,0.08); color: var(--neon); margin-bottom: 20px;
    border: 1px solid var(--neon-dim);
  }
  .why-card h4{ font-size: 17px; margin-bottom:10px; }
  .why-card p{ color: var(--text-muted); font-size: 14.5px; line-height:1.6; margin:0; }

  /* ---------- FAQ ---------- */
  .faq-list{ max-width: 780px; margin: 50px auto 0; display:flex; flex-direction:column; gap: 12px; }
  .faq-item{ border: 1px solid var(--border); border-radius: var(--radius-sharp); background: var(--surface); overflow:hidden; }
  .faq-q{
    width:100%; text-align:left; background:none; border:none; color: var(--text);
    padding: 20px 22px; font-family:'Space Grotesk',sans-serif; font-size: 16px; font-weight:500;
    cursor:pointer; display:flex; justify-content:space-between; align-items:center; gap: 16px;
  }
  .faq-q .plus{ flex-shrink:0; width:20px; height:20px; position:relative; }
  .faq-q .plus::before, .faq-q .plus::after{
    content:''; position:absolute; background: var(--neon); border-radius:2px;
    transition: transform .3s ease;
  }
  .faq-q .plus::before{ width:14px; height:2px; top:9px; left:3px; }
  .faq-q .plus::after{ width:2px; height:14px; left:9px; top:3px; }
  .faq-item.open .plus::after{ transform: rotate(90deg) translate(0,0); opacity:0; }
  .faq-a{ max-height:0; overflow:hidden; transition: max-height .35s ease; }
  .faq-a-inner{ padding: 0 22px 20px; color: var(--text-muted); font-size: 14.5px; line-height:1.7; }

  /* ---------- contact ---------- */
  .contact-grid{ display:grid; grid-template-columns: 1.1fr 0.9fr; gap: 50px; align-items:stretch; margin-top: 50px; }
  @media (max-width: 900px){ .contact-grid{ grid-template-columns: 1fr; } }
  .contact-main{ padding: 44px; display:flex; flex-direction:column; justify-content:center; text-align:left; position:relative; overflow:hidden; }
  .contact-main::before{
    content:''; position:absolute; top:-50%; right:-20%; width:340px; height:340px; border-radius:50%;
    background: radial-gradient(circle, rgba(53,226,255,0.13), transparent 65%); pointer-events:none;
  }
  .contact-main h3{ font-size: 26px; margin-bottom: 12px; position:relative; }
  .contact-main p{ color: var(--text-muted); font-size:15px; line-height:1.7; max-width: 44ch; margin-bottom: 28px; position:relative; }
  .contact-side{ display:flex; flex-direction:column; gap: 18px; }
  .contact-tile{ padding: 22px; display:flex; gap:16px; align-items:center; }
  .contact-tile .ic{ width:42px; height:42px; border-radius: var(--radius-sharp); background: var(--surface-2); display:flex; align-items:center; justify-content:center; color: var(--neon); flex-shrink:0; border:1px solid var(--border); }
  .contact-tile h5{ font-size: 14.5px; margin: 0 0 4px; font-family:'Space Grotesk',sans-serif; }
  .contact-tile span{ font-size: 13.5px; color: var(--text-dim); }

  /* ---------- footer ---------- */
  footer{ border-top: 1px solid var(--border); padding: 64px 0 30px; background: var(--bg-alt); }
  .footer-grid{ display:grid; grid-template-columns: 1.4fr 1fr 1fr 1fr; gap: 40px; margin-bottom: 50px; }
  @media (max-width: 760px){ .footer-grid{ grid-template-columns: 1fr 1fr; } }
  .footer-brand p{ color: var(--text-dim); font-size: 14px; line-height:1.6; margin-top: 14px; max-width: 32ch; }
  .footer-col h5{ font-size: 13px; color: var(--text-dim); font-family:'JetBrains Mono',monospace; margin-bottom: 18px; font-weight:500; }
  .footer-col ul{ display:flex; flex-direction:column; gap: 12px; }
  .footer-col a{ font-size: 14.5px; color: var(--text-muted); transition: color .2s ease; }
  .footer-col a:hover{ color: var(--neon); }
  .footer-bottom{ border-top: 1px solid var(--border); padding-top: 26px; display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap; gap: 14px; }
  .footer-bottom span{ font-size: 13px; color: var(--text-dim); }
  .footer-bottom .flinks{ display:flex; gap: 24px; }
  .footer-bottom .flinks a{ font-size: 13px; color: var(--text-dim); }
  .footer-bottom .flinks a:hover{ color: var(--neon); }

  ::selection{ background: var(--neon); color: #04060a; }
</style>
</head>
<body>

<header class="nav" id="siteNav">
  <div class="nav-inner">
    <a href="#top" class="logo"><span class="dot"></span>TYLER TWEAKS</a>
    <nav class="links">
      <a href="#about">Über uns</a>
      <a href="#angebote">Angebote</a>
      <a href="#ablauf">Ablauf</a>
      <a href="#vorteile">Vorteile</a>
      <a href="#faq">FAQ</a>
      <a href="#kontakt">Kontakt</a>
    </nav>
    <div class="nav-cta">
      <a href="#kontakt" class="btn btn-ghost btn-sm">Kontakt</a>
      <a href="#" class="btn btn-primary btn-sm">Discord beitreten</a>
      <button class="burger" id="burgerBtn" aria-label="Menü öffnen">
        <span></span><span></span><span></span>
      </button>
    </div>
  </div>
</header>

<div class="mobile-menu" id="mobileMenu">
  <a href="#about">Über uns</a>
  <a href="#angebote">Angebote</a>
  <a href="#ablauf">Ablauf</a>
  <a href="#vorteile">Vorteile</a>
  <a href="#faq">FAQ</a>
  <a href="#kontakt">Kontakt</a>
  <a href="#" class="btn btn-primary btn-full">Discord beitreten</a>
</div>

<main id="top">

  <!-- HERO -->
  <section class="hero">
    <div class="hero-bg"></div>
    <div class="hero-glow"></div>
    <div class="wrap hero-grid">
      <div>
        <div class="hero-tag"><span class="blip"></span>Live · PC-Optimierung &amp; Performance-Tool</div>
        <h1>Maximiere die <span class="accent">Leistung</span> deines PCs.</h1>
        <p class="sub">Professionelle PC-Optimierung und das Tyler Tweaks Tool für maximale Gaming-Performance.</p>
        <div class="hero-actions">
          <a href="#" class="btn btn-primary">Discord beitreten</a>
          <a href="#angebote" class="btn btn-ghost">Unsere Angebote</a>
        </div>
        <div class="hero-stats">
          <div class="hero-stat"><b>500+</b><span>optimierte Systeme</span></div>
          <div class="hero-stat"><b>+38%</b><span>durchschn. FPS-Zuwachs</span></div>
          <div class="hero-stat"><b>24/7</b><span>Support auf Discord</span></div>
        </div>
      </div>

      <div class="bracket always-on hud-panel">
        <div class="hud-row">
          <span class="hud-label">SYSTEM_STATUS</span>
          <span class="hud-status"><span class="dot"></span>OPTIMIERT</span>
        </div>

        <div class="meter-block">
          <div class="meter-top"><span>CPU-Auslastung reduziert</span><b>42%</b></div>
          <div class="meter-track"><div class="meter-fill" data-fill="42"></div></div>
        </div>
        <div class="meter-block">
          <div class="meter-top"><span>Input-Lag verringert</span><b>65%</b></div>
          <div class="meter-track"><div class="meter-fill" data-fill="65"></div></div>
        </div>
        <div class="meter-block">
          <div class="meter-top"><span>Frametime-Stabilität</span><b>91%</b></div>
          <div class="meter-track"><div class="meter-fill" data-fill="91"></div></div>
        </div>

        <div class="fps-counter">
          <span class="num" id="fpsNum">0</span>
          <span class="lbl">FPS<br>nach Optimierung</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <div class="wrap about-grid">
      <div class="rv rv-left">
        <div class="eyebrow-line"><div class="dash"></div><span>ÜBER TYLER TWEAKS</span></div>
        <h2 class="section-title">Performance ist kein Zufall — sie wird konfiguriert.</h2>
        <div class="about-body" style="margin-top:26px;">
          <p>Ich optimiere Gaming-PCs auf Windows-Ebene: Systemeinstellungen, Hintergrundprozesse, Netzwerk- und Energieeinstellungen werden gezielt angepasst, damit deine Hardware ihr tatsächliches Potenzial abruft — mehr FPS, stabilere Frametimes und spürbar weniger Input-Lag.</p>
          <p>Aus hunderten Optimierungen ist das Tyler Tweaks Tool entstanden: eine eigene Software, die die wichtigsten Anpassungen automatisiert und dauerhaft auf deinem System verfügbar macht — auch nach einer Neuinstallation von Windows.</p>
        </div>
      </div>
      <div class="rv rv-right about-points">
        <div class="bracket about-point">
          <span class="num">01</span>
          <div><h4>Manuelle Optimierung</h4><p>Jedes System wird individuell analysiert und angepasst, nicht nach Schema F.</p></div>
        </div>
        <div class="bracket about-point">
          <span class="num">02</span>
          <div><h4>Eigenes Tweak-Tool</h4><p>Selbst entwickelte Software für dauerhafte Performance-Anpassungen per Klick.</p></div>
        </div>
        <div class="bracket about-point">
          <span class="num">03</span>
          <div><h4>Direkter Kontakt</h4><p>Kein Ticket-System eines Konzerns — persönlicher Support auf Discord.</p></div>
        </div>
      </div>
    </div>
  </section>

  <!-- ANGEBOTE -->
  <section id="angebote">
    <div class="wrap">
      <div class="rv" style="text-align:center; margin:0 auto;">
        <div class="eyebrow-line" style="justify-content:center;"><div class="dash"></div><span>UNSERE ANGEBOTE</span><div class="dash"></div></div>
        <h2 class="section-title" style="margin:0 auto; text-align:center;">Wähle das Paket, das zu deinem Setup passt.</h2>
      </div>

      <div class="pricing-grid">
        <div class="price-card bracket rv">
          <div class="price-name">Premium PC-Optimierung</div>
          <div class="price-desc">Vollständige manuelle Optimierung deines Systems für maximale Gaming-Performance.</div>
          <div class="price-value"><span class="amount">30€</span><span class="period">einmalig</span></div>
          <ul class="price-list">
            <li>✓ Individuelle Systemanalyse</li>
            <li>✓ Optimierung von Windows, Netzwerk &amp; Energieplan</li>
            <li>✓ Reduzierung von Hintergrundprozessen</li>
            <li>✓ Durchführung per Fernwartung</li>
            <li>✓ Persönlicher Support auf Discord</li>
          </ul>
          <a href="#kontakt" class="btn btn-ghost btn-full">Jetzt anfragen</a>
        </div>

        <div class="price-card bracket always-on featured rv">
          <span class="badge-pop">Beliebteste Wahl</span>
          <div class="price-name">Ultimate Bundle</div>
          <div class="price-desc">Premium PC-Optimierung plus das Tyler Tweaks Tool, vollständig für dich eingerichtet.</div>
          <div class="price-value"><span class="amount">70€</span><span class="period">einmalig</span></div>
          <ul class="price-list">
            <li>✓ Alles aus der Premium PC-Optimierung</li>
            <li>✓ Tyler Tweaks Tool inklusive</li>
            <li>✓ Tool wird für dich eingerichtet</li>
            <li>✓ Lifetime Updates für das Tool</li>
            <li>✓ Priorisierter Support</li>
          </ul>
          <a href="#kontakt" class="btn btn-primary btn-full">Jetzt anfragen</a>
        </div>

        <div class="price-card bracket rv">
          <div class="price-name">Tyler Tweaks Tool</div>
          <div class="price-desc">Die eigenständige Software für dauerhafte Performance-Optimierung — auf Lebenszeit.</div>
          <div class="price-value tbd"><span class="amount">Preis wird noch ergänzt</span></div>
          <ul class="price-list">
            <li>✓ Einmaliger Kauf, lebenslange Nutzung</li>
            <li>✓ Lifetime Updates</li>
            <li>✓ Automatisierte Systemanpassungen</li>
            <li>✓ Einfache Bedienung ohne Vorkenntnisse</li>
            <li>✓ Support bei Fragen zur Installation</li>
          </ul>
          <a href="#kontakt" class="btn btn-ghost btn-full">Auf Discord fragen</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ABLAUF -->
  <section id="ablauf">
    <div class="wrap">
      <div class="rv" style="text-align:center; margin:0 auto;">
        <div class="eyebrow-line" style="justify-content:center;"><div class="dash"></div><span>SO FUNKTIONIERT ES</span><div class="dash"></div></div>
        <h2 class="section-title" style="margin:0 auto; text-align:center;">In vier Schritten zu mehr Performance.</h2>
      </div>

      <div class="steps-rail">
        <div class="steps-grid">
          <div class="step-card bracket rv">
            <span class="step-num">01</span>
            <h4>Discord Server beitreten</h4>
            <p>Werde Teil der Community und erhalte Zugriff auf alle Angebote und den Support.</p>
            <span class="step-arrow">→</span>
          </div>
          <div class="step-card bracket rv">
            <span class="step-num">02</span>
            <h4>Ticket eröffnen</h4>
            <p>Öffne ein Ticket im Server, um deine Anfrage direkt und persönlich zu besprechen.</p>
            <span class="step-arrow">→</span>
          </div>
          <div class="step-card bracket rv">
            <span class="step-num">03</span>
            <h4>Paket auswählen</h4>
            <p>Wähle das passende Angebot für dein System und deine Anforderungen aus.</p>
            <span class="step-arrow">→</span>
          </div>
          <div class="step-card bracket rv">
            <span class="step-num">04</span>
            <h4>Service oder Tool erhalten</h4>
            <p>Nach der Bezahlung wird die Optimierung durchgeführt oder das Tool bereitgestellt.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- WARUM -->
  <section id="vorteile">
    <div class="wrap">
      <div class="rv" style="text-align:center; margin:0 auto;">
        <div class="eyebrow-line" style="justify-content:center;"><div class="dash"></div><span>WARUM TYLER TWEAKS?</span><div class="dash"></div></div>
        <h2 class="section-title" style="margin:0 auto; text-align:center;">Spürbare Vorteile, keine leeren Versprechen.</h2>
      </div>

      <div class="why-grid">
        <div class="why-card bracket rv">
          <div class="why-icon">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M13 2 3 14h7l-1 8 10-12h-7l1-8z"/></svg>
          </div>
          <h4>Mehr FPS</h4>
          <p>Spürbar höhere Bildraten durch gezielte System- und Grafikoptimierung.</p>
        </div>
        <div class="why-card bracket rv">
          <div class="why-icon">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3.5 2"/></svg>
          </div>
          <h4>Schnellere Performance</h4>
          <p>Reduzierte Systemlast und optimierte Prozesse für ein insgesamt flüssigeres System.</p>
        </div>
        <div class="why-card bracket rv">
          <div class="why-icon">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 12h4l3 8 4-16 3 8h4"/></svg>
          </div>
          <h4>Weniger Input-Lag</h4>
          <p>Direktere Reaktion zwischen Eingabe und Bildschirm für präzises Gameplay.</p>
        </div>
        <div class="why-card bracket rv">
          <div class="why-icon">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.4-4 8-9 8-1.2 0-2.3-.2-3.4-.6L3 21l1.6-4.5C3.6 15.2 3 13.7 3 12c0-4.4 4-8 9-8s9 3.6 9 8z"/></svg>
          </div>
          <h4>Persönlicher Support</h4>
          <p>Direkte Kommunikation auf Discord statt anonymer Ticket-Warteschlangen.</p>
        </div>
        <div class="why-card bracket rv">
          <div class="why-icon">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 12a9 9 0 1 1-3-6.7"/><path d="M21 3v6h-6"/></svg>
          </div>
          <h4>Lifetime Updates</h4>
          <p>Das Tyler Tweaks Tool wird laufend weiterentwickelt — Updates sind inklusive.</p>
        </div>
        <div class="why-card bracket rv">
          <div class="why-icon">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2 4 6v6c0 5 3.4 8.7 8 10 4.6-1.3 8-5 8-10V6z"/></svg>
          </div>
          <h4>Sichere Optimierung</h4>
          <p>Alle Anpassungen basieren auf getesteten, unschädlichen Systemeinstellungen.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq">
    <div class="wrap">
      <div class="rv" style="text-align:center; margin:0 auto;">
        <div class="eyebrow-line" style="justify-content:center;"><div class="dash"></div><span>HÄUFIGE FRAGEN</span><div class="dash"></div></div>
        <h2 class="section-title" style="margin:0 auto; text-align:center;">Fragen und Antworten.</h2>
      </div>

      <div class="faq-list" id="faqList">
        <div class="faq-item">
          <button class="faq-q">Was ist Tyler Tweaks?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Tyler Tweaks ist ein Service zur professionellen Optimierung von Gaming-PCs sowie der Entwickler eines eigenen Tweak-Tools, das Systemanpassungen automatisiert.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Für wen ist der Service geeignet?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Für alle PC-Gamer, die mehr FPS, stabilere Frametimes und weniger Input-Lag möchten — unabhängig von der aktuellen Hardware.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Was macht das Tyler Tweaks Tool genau?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Es automatisiert die wichtigsten Systemanpassungen, die sonst manuell vorgenommen werden — darunter Energie-, Netzwerk- und Hintergrundprozess-Optimierungen.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Ist die Optimierung sicher für mein System?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Ja. Es werden ausschließlich getestete, unschädliche Einstellungen verwendet. Es findet kein Eingriff statt, der dein System gefährdet.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Wie lange dauert eine PC-Optimierung?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Je nach System dauert die Durchführung per Fernwartung in der Regel zwischen 30 und 60 Minuten.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Brauche ich Vorkenntnisse, um das Tool zu nutzen?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Nein. Das Tool ist auf einfache Bedienung ausgelegt und wird bei Bedarf gemeinsam eingerichtet.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Welche Zahlungsmethoden werden akzeptiert?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Die verfügbaren Zahlungsmethoden werden dir im eröffneten Ticket auf Discord genannt.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Bekomme ich Updates für das Tool?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Ja, das Tyler Tweaks Tool erhält Lifetime Updates ohne zusätzliche Kosten.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Was ist im Ultimate Bundle enthalten?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Das Ultimate Bundle enthält die vollständige Premium PC-Optimierung sowie das Tyler Tweaks Tool, das direkt für dich eingerichtet wird.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Wie starte ich den Bestellprozess?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Trete dem Discord Server bei, eröffne ein Ticket und wähle dort das passende Paket aus.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Gibt es eine Garantie oder Rückerstattung?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Die genauen Konditionen werden individuell im Ticket besprochen, bevor die Zahlung erfolgt.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q">Funktioniert Tyler Tweaks mit jedem Windows-System?<span class="plus"></span></button>
          <div class="faq-a"><div class="faq-a-inner">Die Optimierung und das Tool sind für aktuelle Windows-Versionen ausgelegt. Details werden im Ticket geklärt.</div></div>
        </div>
      </div>
    </div>
  </section>

  <!-- KONTAKT -->
  <section id="kontakt">
    <div class="wrap">
      <div class="rv" style="text-align:center; margin:0 auto;">
        <div class="eyebrow-line" style="justify-content:center;"><div class="dash"></div><span>KONTAKT</span><div class="dash"></div></div>
        <h2 class="section-title" style="margin:0 auto; text-align:center;">Bereit für mehr Performance?</h2>
      </div>

      <div class="contact-grid">
        <div class="contact-main bracket always-on rv rv-left">
          <h3>Alles läuft über Discord.</h3>
          <p>Tritt dem Server bei, eröffne ein Ticket und wir besprechen direkt, welches Paket zu deinem System passt.</p>
          <a href="#" class="btn btn-primary" style="align-self:flex-start; position:relative;">Discord beitreten</a>
        </div>
        <div class="contact-side rv rv-right">
          <div class="contact-tile bracket">
            <div class="ic">
              <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16v16H4z" opacity="0"/><path d="M22 6 12 13 2 6"/><rect x="2" y="4" width="20" height="16" rx="2"/></svg>
            </div>
            <div><h5>E-Mail</h5><span>kontakt@tylertweaks.de (Platzhalter)</span></div>
          </div>
          <div class="contact-tile bracket">
            <div class="ic">
              <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="4" y="2" width="16" height="20" rx="2"/><path d="M12 18h.01"/></svg>
            </div>
            <div><h5>Instagram / TikTok</h5><span>@tylertweaks (Platzhalter)</span></div>
          </div>
          <div class="contact-tile bracket">
            <div class="ic">
              <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 12a3 3 0 1 0 6 0 3 3 0 0 0-6 0z"/><path d="M4 9c0-3.9 3.6-7 8-7s8 3.1 8 7-3.6 12-8 12-8-8.1-8-12z" opacity="0"/><circle cx="9" cy="12" r="2.4"/><circle cx="15" cy="7" r="2.4"/><circle cx="15" cy="17" r="2.4"/><path d="M11 10.7 13 8M13 16l-2-1.3"/></svg>
            </div>
            <div><h5>Discord Server</h5><span>discord.gg/tylertweaks (Platzhalter)</span></div>
          </div>
        </div>
      </div>
    </div>
  </section>

</main>

<footer>
  <div class="wrap">
    <div class="footer-grid">
      <div class="footer-brand">
        <a href="#top" class="logo"><span class="dot"></span>TYLER TWEAKS</a>
        <p>Professionelle PC-Optimierung und das Tyler Tweaks Tool für maximale Gaming-Performance.</p>
      </div>
      <div class="footer-col">
        <h5>NAVIGATION</h5>
        <ul>
          <li><a href="#about">Über uns</a></li>
          <li><a href="#angebote">Angebote</a></li>
          <li><a href="#ablauf">Ablauf</a></li>
          <li><a href="#vorteile">Vorteile</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h5>SUPPORT</h5>
        <ul>
          <li><a href="#faq">FAQ</a></li>
          <li><a href="#kontakt">Kontakt</a></li>
          <li><a href="#">Discord Server</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h5>RECHTLICHES</h5>
        <ul>
          <li><a href="#">Impressum</a></li>
          <li><a href="#">Datenschutz</a></li>
          <li><a href="#">AGB</a></li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© 2026 Tyler Tweaks. Alle Rechte vorbehalten.</span>
      <div class="flinks">
        <a href="#">Impressum</a>
        <a href="#">Datenschutz</a>
        <a href="#top">Nach oben ↑</a>
      </div>
    </div>
  </div>
</footer>

<script>
  // Nav scroll state
  const navEl = document.getElementById('siteNav');
  window.addEventListener('scroll', () => {
    navEl.classList.toggle('scrolled', window.scrollY > 10);
  }, { passive: true });

  // Mobile menu
  const burger = document.getElementById('burgerBtn');
  const mobileMenu = document.getElementById('mobileMenu');
  burger.addEventListener('click', () => {
    mobileMenu.classList.toggle('open');
  });
  mobileMenu.querySelectorAll('a').forEach(a => {
    a.addEventListener('click', () => mobileMenu.classList.remove('open'));
  });

  // Scroll reveal
  const revealEls = document.querySelectorAll('.rv');
  if ('IntersectionObserver' in window) {
    const io = new IntersectionObserver((entries) => {
      entries.forEach((entry, i) => {
        if (entry.isIntersecting) {
          setTimeout(() => entry.target.classList.add('is-visible'), Math.min(i * 60, 240));
          io.unobserve(entry.target);
        }
      });
    }, { threshold: 0.15 });
    revealEls.forEach(el => io.observe(el));
  } else {
    revealEls.forEach(el => el.classList.add('is-visible'));
  }

  // Hero meters + FPS counter — plays once when hero is visible
  const heroPanel = document.querySelector('.hud-panel');
  let heroPlayed = false;
  function playHero(){
    if (heroPlayed) return;
    heroPlayed = true;
    document.querySelectorAll('.meter-fill').forEach(f => {
      requestAnimationFrame(() => { f.style.width = f.dataset.fill + '%'; });
    });
    const fpsNum = document.getElementById('fpsNum');
    const target = 240;
    const duration = 1400;
    const start = performance.now();
    function tick(now){
      const p = Math.min((now - start) / duration, 1);
      const eased = 1 - Math.pow(1 - p, 3);
      fpsNum.textContent = Math.round(eased * target);
      if (p < 1) requestAnimationFrame(tick);
    }
    requestAnimationFrame(tick);
  }
  if (heroPanel) {
    const heroIo = new IntersectionObserver((entries) => {
      entries.forEach(entry => { if (entry.isIntersecting) { playHero(); heroIo.disconnect(); } });
    }, { threshold: 0.3 });
    heroIo.observe(heroPanel);
  }

  // FAQ accordion
  document.querySelectorAll('.faq-item').forEach(item => {
    const q = item.querySelector('.faq-q');
    const a = item.querySelector('.faq-a');
    q.addEventListener('click', () => {
      const isOpen = item.classList.contains('open');
      document.querySelectorAll('.faq-item.open').forEach(other => {
        if (other !== item) {
          other.classList.remove('open');
          other.querySelector('.faq-a').style.maxHeight = null;
        }
      });
      if (isOpen) {
        item.classList.remove('open');
        a.style.maxHeight = null;
      } else {
        item.classList.add('open');
        a.style.maxHeight = a.scrollHeight + 'px';
      }
    });
  });

  // Hero glow follows cursor (desktop only)
  const glow = document.querySelector('.hero-glow');
  const heroSection = document.querySelector('.hero');
  if (glow && heroSection && window.matchMedia('(hover: hover)').matches) {
    heroSection.addEventListener('mousemove', (e) => {
      const rect = heroSection.getBoundingClientRect();
      const x = e.clientX - rect.left;
      const y = e.clientY - rect.top;
      glow.style.transform = `translate(${x - rect.width * 0.75}px, ${y - rect.height * 0.35}px)`;
    });
  }
</script>

</body>
</html>
