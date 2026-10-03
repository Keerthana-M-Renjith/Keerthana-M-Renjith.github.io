<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Keerthana M Renjith · Verified Academic Documents</title>
<meta name="description" content="Undergraduate experimental physics enthusiast. Verified academic documents for applications and evaluation.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300..600;1,9..144,300..500&family=Inter:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0a0912;
    --bg2:#100e1c;
    --ink:#efecfa;
    --muted:#9b97b8;
    --line:rgba(255,255,255,.09);
    --glass:rgba(255,255,255,.04);
    --glass-hi:rgba(255,255,255,.08);
    --violet:#a78bfa;
    --pink:#f0abfc;
    --cyan:#67e8f9;
    --grad:linear-gradient(120deg,var(--violet),var(--pink) 50%,var(--cyan));
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{
    font-family:'Inter',system-ui,sans-serif;
    background:var(--bg);
    color:var(--ink);
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
    overflow-x:hidden;
  }

  /* ambient glow */
  .aurora{position:fixed;inset:0;z-index:-2;pointer-events:none;overflow:hidden}
  .aurora span{position:absolute;border-radius:50%;filter:blur(110px);opacity:.38}
  .aurora span:nth-child(1){width:520px;height:520px;background:#7c3aed;top:-160px;left:-120px;animation:drift 22s ease-in-out infinite alternate}
  .aurora span:nth-child(2){width:460px;height:460px;background:#db2777;top:30%;right:-160px;opacity:.22;animation:drift 28s ease-in-out infinite alternate-reverse}
  .aurora span:nth-child(3){width:520px;height:520px;background:#0891b2;bottom:-220px;left:25%;opacity:.2;animation:drift 32s ease-in-out infinite alternate}
  @keyframes drift{to{transform:translate(70px,50px) scale(1.12)}}
  .grain{position:fixed;inset:0;z-index:-1;pointer-events:none;opacity:.05;
    background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='160' height='160'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.9' numOctaves='2'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E")}

  .wrap{max-width:1040px;margin:0 auto;padding:0 24px}

  /* ---------- hero ---------- */
  header{position:relative;padding:112px 0 40px;text-align:center}
  .eyebrow{
    display:inline-flex;align-items:center;gap:10px;
    font-family:'JetBrains Mono',monospace;font-size:.74rem;letter-spacing:.18em;text-transform:uppercase;
    color:var(--muted);padding:8px 16px;border:1px solid var(--line);border-radius:999px;background:var(--glass);
    backdrop-filter:blur(8px);
  }
  .eyebrow i{width:7px;height:7px;border-radius:50%;background:var(--cyan);box-shadow:0 0 12px var(--cyan);animation:pulse 2.4s infinite}
  @keyframes pulse{50%{opacity:.35}}
  h1{
    font-family:'Fraunces',serif;font-weight:400;
    font-size:clamp(2.8rem,8.4vw,6rem);line-height:1.02;letter-spacing:-.025em;
    margin:30px 0 22px;
  }
  h1 em{
    font-style:italic;font-weight:300;
    background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent;
  }
  .lead{max-width:560px;margin:0 auto;color:var(--muted);font-size:1.08rem;font-weight:300}
  .chips{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-top:30px}
  .chip{font-size:.8rem;color:var(--ink);padding:7px 14px;border-radius:999px;background:var(--glass);border:1px solid var(--line)}
  .chip b{font-weight:500;color:var(--pink)}

  /* spectrum */
  .spectrum{position:relative;height:150px;margin:44px auto 0;max-width:900px;
    -webkit-mask-image:linear-gradient(90deg,transparent,#000 14%,#000 86%,transparent);
            mask-image:linear-gradient(90deg,transparent,#000 14%,#000 86%,transparent)}
  .spectrum canvas{width:100%;height:100%;display:block}
  .axis{display:flex;justify-content:space-between;max-width:900px;margin:6px auto 0;padding:0 8%;
    font-family:'JetBrains Mono',monospace;font-size:.66rem;color:#6d6989;letter-spacing:.08em}

  /* ---------- sections ---------- */
  main{padding:56px 0 40px}
  section{margin-top:64px}
  .sec-head{display:flex;align-items:baseline;gap:16px;margin-bottom:24px}
  .sec-num{font-family:'JetBrains Mono',monospace;font-size:.78rem;color:var(--violet)}
  .sec-head h2{font-family:'Fraunces',serif;font-weight:400;font-size:1.85rem;letter-spacing:-.01em}
  .sec-head::after{content:"";flex:1;height:1px;background:linear-gradient(90deg,var(--line),transparent)}

  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(290px,1fr));gap:18px}

  .card{
    position:relative;display:flex;flex-direction:column;justify-content:space-between;gap:26px;
    padding:26px;border-radius:22px;text-decoration:none;color:inherit;
    background:var(--glass);border:1px solid var(--line);
    backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);
    overflow:hidden;
    transition:transform .35s cubic-bezier(.2,.8,.2,1),border-color .35s,background .35s,box-shadow .35s;
  }
  .card::before{ /* cursor spotlight */
    content:"";position:absolute;inset:0;opacity:0;transition:opacity .35s;
    background:radial-gradient(320px circle at var(--mx,50%) var(--my,0%),rgba(167,139,250,.2),transparent 60%);
  }
  .card:hover{transform:translateY(-6px);border-color:rgba(167,139,250,.45);background:var(--glass-hi);box-shadow:0 24px 60px -24px rgba(124,58,237,.55)}
  .card:hover::before{opacity:1}
  .card > *{position:relative}

  .top{display:flex;justify-content:space-between;align-items:flex-start}
  .ico{width:46px;height:46px;border-radius:14px;display:grid;place-items:center;
    background:linear-gradient(140deg,rgba(167,139,250,.28),rgba(103,232,249,.14));
    border:1px solid rgba(255,255,255,.12)}
  .ico svg{width:22px;height:22px;stroke:var(--ink);fill:none;stroke-width:1.6;stroke-linecap:round;stroke-linejoin:round}
  .tag{font-family:'JetBrains Mono',monospace;font-size:.66rem;letter-spacing:.12em;color:var(--muted);
    padding:4px 9px;border:1px solid var(--line);border-radius:7px}
  .card h3{font-family:'Fraunces',serif;font-weight:400;font-size:1.28rem;line-height:1.25;margin-bottom:6px}
  .card p{font-size:.86rem;color:var(--muted);font-weight:300}
  .cta{display:flex;align-items:center;justify-content:space-between;
    font-size:.82rem;font-weight:500;padding-top:16px;border-top:1px solid var(--line)}
  .cta span{background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
  .cta svg{width:18px;height:18px;stroke:var(--pink);fill:none;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round;transition:transform .3s}
  .card:hover .cta svg{transform:translate(4px,-4px)}

  /* featured award card */
  .card.feature{grid-column:1/-1;flex-direction:row;align-items:center;gap:34px;padding:34px;
    background:linear-gradient(135deg,rgba(167,139,250,.14),rgba(240,171,252,.06) 50%,rgba(103,232,249,.1))}
  .feature .body{flex:1}
  .feature h3{font-size:1.75rem}
  .feature .cta{border:none;padding:0;flex-direction:column;align-items:flex-end;gap:14px;min-width:150px}
  .medal{width:84px;height:84px;flex:none;border-radius:50%;display:grid;place-items:center;
    background:conic-gradient(from 200deg,var(--violet),var(--pink),var(--cyan),var(--violet));
    box-shadow:0 0 48px rgba(240,171,252,.35)}
  .medal svg{width:34px;height:34px;stroke:#0a0912;fill:none;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
  .btn{display:inline-flex;align-items:center;gap:8px;padding:11px 20px;border-radius:999px;font-size:.84rem;font-weight:500;color:#0a0912;background:var(--grad);white-space:nowrap}

  /* ---------- footer ---------- */
  footer{margin-top:90px;padding:34px 0 54px;border-top:1px solid var(--line);text-align:center;color:var(--muted);font-size:.82rem}
  footer .quote{font-family:'Fraunces',serif;font-style:italic;font-weight:300;font-size:1.15rem;color:var(--ink);margin-bottom:10px}
  footer small{display:block;margin-top:6px;opacity:.7}

  /* reveal */
  .reveal{opacity:0;transform:translateY(24px);transition:opacity .8s ease,transform .8s cubic-bezier(.2,.8,.2,1)}
  .reveal.in{opacity:1;transform:none}

  @media (max-width:680px){
    header{padding-top:80px}
    .card.feature{flex-direction:column;align-items:flex-start;padding:26px}
    .feature .cta{align-items:flex-start;min-width:0}
    .medal{width:68px;height:68px}
  }
  @media (prefers-reduced-motion:reduce){
    *{animation:none!important;transition:none!important}
    .reveal{opacity:1;transform:none}
  }
</style>
</head>
<body>
<div class="aurora"><span></span><span></span><span></span></div>
<div class="grain"></div>

<header class="wrap">
  <div class="eyebrow"><i></i> Verified documents</div>
  <h1>Keerthana <em>M Renjith</em></h1>
  <p class="lead">An undergraduate experimental physics enthusiast. This page contains my verified academic documents for applications and evaluation.</p>
  <div class="chips">
    <span class="chip"><b>B.Sc.</b> Physics (Honours)</span>
    <span class="chip">Sacred Heart College, Ernakulam</span>
    <span class="chip">Project Student · <b>TIFR</b> Mumbai</span>
  </div>

  <div class="spectrum"><canvas id="spec"></canvas></div>
  <div class="axis"><span>200</span><span>600</span><span>1000</span><span>1400</span><span>1800 cm⁻¹</span></div>
</header>

<main class="wrap">

  <!-- 01 -->
  <section class="reveal">
    <div class="sec-head"><span class="sec-num">01</span><h2>Academic Records</h2></div>
    <div class="grid">
      <a class="card" href="Keerthana_degree_Marksheets.pdf" target="_blank" rel="noopener">
        <div class="top">
          <div class="ico"><svg viewBox="0 0 24 24"><path d="M2 9l10-5 10 5-10 5z"/><path d="M6 11v5c0 1.5 2.7 3 6 3s6-1.5 6-3v-5"/></svg></div>
          <span class="tag">PDF</span>
        </div>
        <div><h3>UG Degree Marksheets</h3><p>B.Sc. Physics (Honours) · up to Semester 4</p></div>
        <div class="cta"><span>View marksheets</span><svg viewBox="0 0 24 24"><path d="M7 17L17 7M8 7h9v9"/></svg></div>
      </a>

      <a class="card" href="Keerthana_12th.jpg" target="_blank" rel="noopener">
        <div class="top">
          <div class="ico"><svg viewBox="0 0 24 24"><path d="M4 5a2 2 0 012-2h12a2 2 0 012 2v14a2 2 0 01-2 2H6a2 2 0 01-2-2z"/><path d="M8 8h8M8 12h8M8 16h5"/></svg></div>
          <span class="tag">JPG</span>
        </div>
        <div><h3>Higher Secondary Marksheet</h3><p>Science (PCMB)</p></div>
        <div class="cta"><span>View marksheet</span><svg viewBox="0 0 24 24"><path d="M7 17L17 7M8 7h9v9"/></svg></div>
      </a>

      <a class="card" href="Keerthana_10th.jpeg" target="_blank" rel="noopener">
        <div class="top">
          <div class="ico"><svg viewBox="0 0 24 24"><path d="M4 5a2 2 0 012-2h12a2 2 0 012 2v14a2 2 0 01-2 2H6a2 2 0 01-2-2z"/><path d="M8 8h8M8 12h8M8 16h5"/></svg></div>
          <span class="tag">JPEG</span>
        </div>
        <div><h3>Secondary Education Marksheet</h3><p>Class X</p></div>
        <div class="cta"><span>View marksheet</span><svg viewBox="0 0 24 24"><path d="M7 17L17 7M8 7h9v9"/></svg></div>
      </a>
    </div>
  </section>

  <!-- 02 -->
  <section class="reveal">
    <div class="sec-head"><span class="sec-num">02</span><h2>Honours &amp; Recognition</h2></div>
    <div class="grid">
      <a class="card feature" href="best_research_paper_award.pdf" target="_blank" rel="noopener">
        <div class="medal"><svg viewBox="0 0 24 24"><circle cx="12" cy="9" r="6"/><path d="M8.5 14L7 22l5-3 5 3-1.5-8"/></svg></div>
        <div class="body">
          <span class="tag">2026 · PDF</span>
          <h3 style="margin-top:14px">Best Research Paper Award</h3>
          <p>SPARK'26 · National Level Student Research Conclave</p>
        </div>
        <div class="cta"><span class="btn">View certificate ↗</span></div>
      </a>

      <a class="card" href="NIUS_Keerthana.pdf" target="_blank" rel="noopener">
        <div class="top">
          <div class="ico"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="2"/><ellipse cx="12" cy="12" rx="10" ry="4"/><ellipse cx="12" cy="12" rx="10" ry="4" transform="rotate(60 12 12)"/><ellipse cx="12" cy="12" rx="10" ry="4" transform="rotate(120 12 12)"/></svg></div>
          <span class="tag">2025 · PDF</span>
        </div>
        <div><h3>NIUS Physics 2025</h3><p>National Initiative on Undergraduate Science · HBCSE–TIFR</p></div>
        <div class="cta"><span>View certificate</span><svg viewBox="0 0 24 24"><path d="M7 17L17 7M8 7h9v9"/></svg></div>
      </a>
    </div>
  </section>

  <!-- 03 -->
  <section class="reveal">
    <div class="sec-head"><span class="sec-num">03</span><h2>Scholarships</h2></div>
    <div class="grid">
      <a class="card" href="INSPIRE_Keerthana.pdf" target="_blank" rel="noopener">
        <div class="top">
          <div class="ico"><svg viewBox="0 0 24 24"><path d="M12 3l2.4 5.6L20 9.3l-4.3 3.9L17 19l-5-3-5 3 1.3-5.8L4 9.3l5.6-.7z"/></svg></div>
          <span class="tag">PDF</span>
        </div>
        <div><h3>INSPIRE Offer Letter</h3><p>Department of Science and Technology, Government of India</p></div>
        <div class="cta"><span>View offer letter</span><svg viewBox="0 0 24 24"><path d="M7 17L17 7M8 7h9v9"/></svg></div>
      </a>

      <a class="card" href="MCYscholarship_Keerthana.jpeg" target="_blank" rel="noopener">
        <div class="top">
          <div class="ico"><svg viewBox="0 0 24 24"><path d="M12 21s-7-4.5-9.3-9A5.2 5.2 0 0112 6.5 5.2 5.2 0 0121.3 12C19 16.5 12 21 12 21z"/></svg></div>
          <span class="tag">2022 · JPEG</span>
        </div>
        <div><h3>Medha Chhatravriti Yojana</h3><p>Kerala State Education Board scholarship</p></div>
        <div class="cta"><span>View certificate</span><svg viewBox="0 0 24 24"><path d="M7 17L17 7M8 7h9v9"/></svg></div>
      </a>
    </div>
  </section>
</main>

<footer class="wrap">
  <div class="quote">“Measure what is measurable, and make measurable what is not.”</div>
  <div>Keerthana M Renjith · Physics Undergraduate</div>
  <small>All documents above are original and available for verification.</small>
</footer>

<script>
  /* scroll reveal */
  const io = new IntersectionObserver(es => es.forEach(e => { if(e.isIntersecting){ e.target.classList.add('in'); io.unobserve(e.target);} }), {threshold:.12});
  document.querySelectorAll('.reveal').forEach(el => io.observe(el));

  /* card spotlight follows cursor */
  document.querySelectorAll('.card').forEach(c => c.addEventListener('pointermove', e => {
    const r = c.getBoundingClientRect();
    c.style.setProperty('--mx', (e.clientX - r.left) + 'px');
    c.style.setProperty('--my', (e.clientY - r.top) + 'px');
  }));

  /* animated Raman-style spectrum */
  (function(){
    const cv = document.getElementById('spec'), ctx = cv.getContext('2d');
    const reduce = matchMedia('(prefers-reduced-motion: reduce)').matches;
    let W, H, dpr;
    const peaks = [ // position (0-1), height, width
      {x:.13,a:.30,w:.010},{x:.27,a:.55,w:.008},{x:.41,a:.34,w:.012},
      {x:.56,a:.95,w:.007},{x:.70,a:.48,w:.010},{x:.83,a:.72,w:.009},{x:.92,a:.28,w:.011}
    ];
    function size(){
      dpr = Math.min(devicePixelRatio||1, 2);
      W = cv.clientWidth; H = cv.clientHeight;
      cv.width = W*dpr; cv.height = H*dpr; ctx.setTransform(dpr,0,0,dpr,0,0);
    }
    function noise(i,t){ return (Math.sin(i*12.9898+t*.9)*43758.5453 % 1) * .5; }
    function draw(t){
      ctx.clearRect(0,0,W,H);
      const N = Math.floor(W/2), base = H-18;
      const g = ctx.createLinearGradient(0,0,W,0);
      g.addColorStop(0,'#a78bfa'); g.addColorStop(.5,'#f0abfc'); g.addColorStop(1,'#67e8f9');
      const pts = [];
      for(let i=0;i<=N;i++){
        const x = i/N; let y = .04;
        for(const p of peaks){
          const amp = p.a*(1 + .08*Math.sin(t*.0012 + p.x*9));
          const d = (x - p.x)/p.w; y += amp/(1+d*d);
        }
        y += noise(i,t*.002)*.012;
        pts.push([x*W, base - y*(H-40)]);
      }
      // fill
      ctx.beginPath(); ctx.moveTo(0,base);
      pts.forEach(p=>ctx.lineTo(p[0],p[1])); ctx.lineTo(W,base); ctx.closePath();
      const f = ctx.createLinearGradient(0,0,0,H);
      f.addColorStop(0,'rgba(167,139,250,.28)'); f.addColorStop(1,'rgba(167,139,250,0)');
      ctx.fillStyle = f; ctx.fill();
      // glow line
      ctx.beginPath(); pts.forEach((p,i)=> i?ctx.lineTo(p[0],p[1]):ctx.moveTo(p[0],p[1]));
      ctx.lineJoin='round'; ctx.strokeStyle=g; ctx.shadowColor='rgba(240,171,252,.7)'; ctx.shadowBlur=14; ctx.lineWidth=1.8; ctx.stroke();
      ctx.shadowBlur=0;
      // baseline
      ctx.strokeStyle='rgba(255,255,255,.1)'; ctx.lineWidth=1; ctx.beginPath(); ctx.moveTo(0,base+.5); ctx.lineTo(W,base+.5); ctx.stroke();
    }
    size(); addEventListener('resize', size);
    if(reduce){ draw(0); return; }
    (function loop(t){ draw(t); requestAnimationFrame(loop); })(0);
  })();
</script>
</body>
</html>
