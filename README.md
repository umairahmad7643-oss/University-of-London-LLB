<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>UoL LLB Guide — 3D</title>
<meta name="description" content="Exam guidance, important topics, notes and answers for University of London LLB students (Levels 4, 5 and 6).">
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Hanken+Grotesk:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
:root{--paper:#0b0e17;--card:rgba(23,32,46,.72);--ink:#f2eee2;--muted:#b9b2a0;--line:rgba(240,217,160,.22);--ox:#c73a50;--ox2:#7a1d2c;--gold:#d9a83c;--navy:#17202e;--green:#4ea87e;--blue:#4d84c4;--red:#d95f68;--r:16px}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:64px}
body{margin:0;background:var(--paper);color:var(--ink);font:16px/1.65 'Hanken Grotesk',system-ui,sans-serif;-webkit-font-smoothing:antialiased;overflow-x:hidden}
#bg3d{position:fixed;inset:0;z-index:0;pointer-events:none}
.vignette{position:fixed;inset:0;z-index:1;pointer-events:none;background:radial-gradient(ellipse at 50% 30%,transparent 40%,rgba(5,7,12,.55) 100%)}
h1,h2,h3,h4{font-family:'Fraunces',Georgia,serif;line-height:1.2;margin:0}
a{color:var(--gold)}
/* ---------- slim sticky nav ---------- */
.nav{position:sticky;top:0;z-index:50;height:56px;background:rgba(11,14,23,.72);backdrop-filter:blur(14px) saturate(1.3);-webkit-backdrop-filter:blur(14px) saturate(1.3);color:#fff;display:flex;align-items:center;gap:14px;padding:0 14px;border-bottom:1px solid rgba(217,168,60,.4);box-shadow:0 6px 24px rgba(0,0,0,.45)}
.brand{font-family:'Fraunces',Georgia,serif;font-weight:700;font-size:18px;white-space:nowrap;letter-spacing:.2px;color:#fff;text-decoration:none;display:flex;align-items:center;gap:8px}
.brand i{display:inline-grid;place-items:center;width:28px;height:28px;border-radius:8px;background:linear-gradient(135deg,var(--gold),#a87c1e);color:#1a1305;font-style:normal;font-size:15px;font-weight:800;box-shadow:0 4px 14px rgba(217,168,60,.45);transform:translateZ(0);transition:transform .4s}
.brand:hover i{transform:rotateY(360deg)}
.links{display:flex;gap:2px;overflow-x:auto;scrollbar-width:none;flex:1;-webkit-overflow-scrolling:touch}
.links::-webkit-scrollbar{display:none}
.links a{color:#c6cdda;text-decoration:none;font-size:14px;font-weight:500;padding:6px 11px;border-radius:8px;white-space:nowrap;transition:.2s}
.links a:hover{background:rgba(255,255,255,.09);color:#fff}
.links a.on{background:linear-gradient(135deg,var(--gold),#b8862a);color:#1a1305;font-weight:700;box-shadow:0 3px 12px rgba(217,168,60,.4)}
/* ---------- layout ---------- */
main{position:relative;z-index:2;max-width:1040px;margin:0 auto;padding:30px 16px 60px}
.tab{display:none}.tab.on{display:block;animation:in .5s cubic-bezier(.2,.8,.2,1) both}
@keyframes in{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:none}}
.eyebrow{font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--gold);font-weight:700;margin:0 0 8px}
.ph{margin:0 0 22px}.ph h2{font-size:clamp(28px,5vw,40px);text-shadow:0 4px 30px rgba(0,0,0,.5)}.ph p{color:var(--muted);margin:8px 0 0;max-width:62ch}
.card{background:var(--card);backdrop-filter:blur(16px);-webkit-backdrop-filter:blur(16px);border:1px solid var(--line);border-radius:var(--r);padding:22px;box-shadow:0 20px 50px rgba(0,0,0,.45),inset 0 1px 0 rgba(255,255,255,.07);transform-style:preserve-3d;transition:transform .25s ease,box-shadow .25s ease;will-change:transform}
.card.glow:hover{box-shadow:0 30px 70px rgba(0,0,0,.6),0 0 40px rgba(217,168,60,.15),inset 0 1px 0 rgba(255,255,255,.1)}
.muted{color:var(--muted)}.fine{color:var(--muted);font-size:14px;margin:6px 4px 0}
/* ---------- hero ---------- */
.hero{position:relative;border-radius:24px;padding:clamp(26px,5vw,52px);overflow:hidden;background:linear-gradient(135deg,rgba(23,32,46,.85),rgba(92,20,33,.7) 70%);border:1px solid rgba(217,168,60,.35);backdrop-filter:blur(18px);box-shadow:0 40px 90px rgba(0,0,0,.6);transform-style:preserve-3d}
.hero .eyebrow{color:#f0d9a0}
.hero h1{font-size:clamp(32px,6vw,54px);max-width:16ch;text-shadow:0 8px 40px rgba(0,0,0,.6);transform:translateZ(50px)}
.hero p{max-width:58ch;color:#d6dbe6;font-size:18px;margin:14px 0 0;transform:translateZ(30px)}
.hero .stmt{display:inline-block;margin-top:20px;background:rgba(217,168,60,.16);border:1px solid var(--gold);color:#f5e3b3;padding:9px 16px;border-radius:999px;font-weight:600;font-size:15px;transform:translateZ(40px);box-shadow:0 0 30px rgba(217,168,60,.2)}
.cta{display:flex;flex-wrap:wrap;gap:10px;margin-top:22px;transform:translateZ(40px)}
.btn{display:inline-block;border:0;cursor:pointer;background:linear-gradient(135deg,var(--ox),var(--ox2));color:#fff;font:700 15px 'Hanken Grotesk',sans-serif;padding:12px 22px;border-radius:10px;text-decoration:none;transition:.2s;box-shadow:0 10px 26px rgba(122,29,44,.5)}
.btn:hover{transform:translateY(-2px) scale(1.02);box-shadow:0 16px 36px rgba(122,29,44,.65)}
.btn.alt{background:rgba(255,255,255,.06);border:1.5px solid rgba(255,255,255,.5);box-shadow:none}.btn.alt:hover{background:rgba(255,255,255,.14)}
.grid3{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:22px}
.feat h3{font-size:19px;margin:6px 0}.feat p{margin:0;color:var(--muted);font-size:15px}
.feat .n{font:700 13px 'Hanken Grotesk';color:var(--gold);letter-spacing:.1em}
.glance{margin-top:22px}.glance h3{font-size:20px;margin-bottom:10px}
/* ---------- accordions ---------- */
details>summary{list-style:none;cursor:pointer}details>summary::-webkit-details-marker{display:none}
details.level{margin:0 0 16px}
details.level>summary{display:flex;flex-wrap:wrap;gap:4px 14px;align-items:baseline;justify-content:space-between;background:linear-gradient(120deg,rgba(23,32,46,.9),rgba(92,20,33,.85));color:#fff;padding:18px 22px;border-radius:var(--r);position:relative;padding-right:56px;border:1px solid rgba(217,168,60,.3);box-shadow:0 14px 40px rgba(0,0,0,.45);backdrop-filter:blur(10px)}
details.level>summary:after,details.acc>summary:after{content:'';position:absolute;right:20px;top:50%;width:9px;height:9px;border:solid currentColor;border-width:0 2.5px 2.5px 0;transform:translateY(-70%) rotate(45deg);transition:.25s}
details[open]>summary:after{transform:translateY(-30%) rotate(-135deg)}
.lv-t{font:700 24px 'Fraunces',serif}.lv-p{color:#f0d9a0;font-weight:600;font-size:14px}
.lv-body{padding:12px 0 0;display:grid;gap:10px}
details.acc{background:var(--card);backdrop-filter:blur(14px);border:1px solid var(--line);border-radius:14px;overflow:hidden;box-shadow:0 12px 32px rgba(0,0,0,.4);transition:box-shadow .25s}
details.acc[open]{box-shadow:0 24px 60px rgba(0,0,0,.55),0 0 30px rgba(217,168,60,.08)}
details.acc>summary{display:flex;align-items:center;gap:10px;flex-wrap:wrap;padding:15px 48px 15px 18px;position:relative}
details.acc>summary:hover{background:rgba(255,255,255,.05)}
.acc-n{font:600 18px 'Fraunces',serif}
.acc-b{padding:4px 20px 20px;border-top:1px dashed var(--line)}
.acc-b h4{font:700 12px 'Hanken Grotesk';letter-spacing:.12em;text-transform:uppercase;color:var(--gold);margin:16px 0 6px}
.acc-b p{margin:6px 0}.acc-b ul{margin:6px 0;padding-left:20px}.acc-b li{margin:3px 0}
.note{background:rgba(217,168,60,.12);border-left:3px solid var(--gold);padding:8px 12px;border-radius:6px;font-size:14px}
.pill{font:700 12px 'Hanken Grotesk';padding:3px 10px;border-radius:999px}
.pill.code{background:rgba(217,168,60,.18);color:#f0d9a0}.pill.req{background:rgba(78,168,126,.2);color:var(--green)}.pill.opt{background:rgba(77,132,196,.2);color:#9db9dd}
.lvh{font-size:22px;margin:26px 0 10px;padding-bottom:6px;border-bottom:2px solid var(--gold)}
.lvh:first-of-type{margin-top:0}
.acc-b.notes h4{font:600 17px 'Fraunces',serif;letter-spacing:0;text-transform:none;color:var(--ink);margin:18px 0 4px}
.acc-b.notes p,.acc-b.notes li{font-size:15.5px}
.endnote{margin-top:20px;background:rgba(23,32,46,.9);border:1px solid var(--line);color:#e6e9f1;padding:14px 16px;border-radius:10px;font-size:15px}
.endnote a{color:#f0d9a0;font-weight:700}
/* exam guidance */
.two{display:grid;grid-template-columns:repeat(auto-fit,minmax(310px,1fr));gap:16px;align-items:start}
.step{border-left:4px solid var(--green);background:rgba(78,168,126,.1);padding:10px 14px;border-radius:0 8px 8px 0;margin:10px 0}
.step.key{background:rgba(122,29,44,.18);border-color:var(--ox)}.step b{display:block}
.bad{color:var(--red)}.good{color:var(--green)}
.box{border-radius:10px;padding:14px 16px;margin-top:14px}.box.blue{background:rgba(77,132,196,.12);border:1px solid rgba(77,132,196,.3)}.box.red{background:rgba(217,95,104,.1);border:1px solid rgba(217,95,104,.3)}
.box h4{font-size:17px;margin-bottom:6px}.box ul{margin:4px 0;padding-left:20px}
.q{background:rgba(180,140,220,.1);border:1px solid rgba(180,140,220,.25);border-radius:10px;padding:12px 14px;margin:9px 0}.q b{color:#cfa9f0}.q span{display:block;font-size:14.5px;color:#cfc9de}
/* pricing */
.banner{background:linear-gradient(120deg,var(--ox),var(--ox2));color:#fff;border-radius:var(--r);padding:20px;text-align:center;font:600 clamp(18px,3vw,24px) 'Fraunces',serif;margin-bottom:26px;box-shadow:0 18px 44px rgba(122,29,44,.5)}
.sec{margin:34px 0 14px;font-size:26px}
.p3{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:14px}
.p3 div{background:rgba(217,168,60,.1);border:1px solid rgba(217,168,60,.25);border-radius:10px;padding:10px;text-align:center}.p3 span{display:block;font-size:13px;color:var(--muted)}.p3 b{font:700 clamp(15px,2.4vw,21px) 'Fraunces',serif;color:#f0d9a0}
.tier{background:var(--card);backdrop-filter:blur(14px);border:1px solid var(--line);border-radius:var(--r);margin-bottom:16px;overflow:hidden;box-shadow:0 18px 44px rgba(0,0,0,.45)}
.tier-h{display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap;align-items:center;padding:16px 20px;color:#fff}
.tier-h h3{font-size:21px}.tier-h p{margin:2px 0 0;opacity:.9;font-size:14.5px}
.t-green .tier-h{background:linear-gradient(120deg,rgba(47,107,79,.9),rgba(23,32,46,.9))}.t-blue .tier-h{background:linear-gradient(120deg,rgba(40,90,143,.9),rgba(23,32,46,.9))}.t-red .tier-h{background:linear-gradient(120deg,rgba(163,50,59,.9),rgba(23,32,46,.9))}
.tier-b{padding:16px 20px 20px}.ticks{list-style:none;padding:0;margin:0}.ticks li{padding:3px 0 3px 26px;position:relative}.ticks li:before{content:'\2713';position:absolute;left:0;color:var(--green);font-weight:800}
.pos{text-align:center;margin:12px 0 0;font:italic 600 17px 'Fraunces',serif;color:var(--muted)}
.badge{background:var(--gold);color:#1a1305;font:800 11px 'Hanken Grotesk';letter-spacing:.08em;padding:5px 11px;border-radius:999px;box-shadow:0 4px 14px rgba(217,168,60,.5)}
.bundles{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:14px}
.bundle{background:var(--card);backdrop-filter:blur(14px);border:1px solid var(--line);border-top:4px solid #4d84c4;border-radius:var(--r);padding:18px;box-shadow:0 14px 36px rgba(0,0,0,.4)}
.bundle.hl{border-top-color:var(--gold);box-shadow:0 0 0 3px rgba(217,168,60,.25),0 18px 44px rgba(0,0,0,.5)}
.bundle h3{font-size:19px;margin-bottom:10px;display:flex;justify-content:space-between;gap:8px;align-items:center}
.brow{display:flex;justify-content:space-between;background:rgba(217,168,60,.1);padding:8px 12px;border-radius:8px;margin-top:6px}
.addons{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:14px}
.addons .card h3{font-size:18px}.addons .card b{display:block;font:700 26px 'Fraunces',serif;color:#f0d9a0;margin-top:4px}
.rules{background:rgba(217,95,104,.1);border:1px solid rgba(217,95,104,.3);border-radius:var(--r);padding:16px 20px;margin-top:20px}
.rules ul{margin:6px 0 0;padding-left:20px}
.check-intro{background:linear-gradient(120deg,rgba(77,132,196,.14),rgba(180,140,220,.12));border:1px solid rgba(77,132,196,.3);border-radius:var(--r);padding:20px;margin-bottom:16px}
.check-intro h3{font-size:22px}
.speed{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px;margin-top:14px}
.speed div{background:rgba(255,255,255,.04);border-radius:10px;padding:12px 14px;border:1px solid rgba(217,168,60,.2)}.speed b{display:block;font:700 18px 'Fraunces',serif}.speed span{color:var(--muted);font-size:14.5px}
/* forms */
.forms{display:grid;grid-template-columns:repeat(auto-fit,minmax(310px,1fr));gap:16px;align-items:start;margin-top:14px}
.form h3{font-size:21px;margin-bottom:6px}.form .muted{margin:0 0 12px;font-size:15px}
label.f{display:block;margin-top:12px}label.f>span,.turn .lbl{display:block;font-weight:700;font-size:14px;margin-bottom:4px}
input[type=text],input[type=email],select,textarea{width:100%;font:16px 'Hanken Grotesk',sans-serif;padding:11px 13px;border:1.5px solid var(--line);border-radius:10px;background:rgba(11,14,23,.6);color:var(--ink)}
input:focus,select:focus,textarea:focus{outline:0;border-color:var(--gold);box-shadow:0 0 0 3px rgba(217,168,60,.2)}
.form .btn{width:100%;margin-top:18px}
.checks{margin-top:12px;display:grid;gap:6px;font-size:14.5px}.checks input{margin-right:6px}
.turn{margin-top:14px;display:grid;gap:8px}.turn .lbl{margin:0}
.opt{display:flex;align-items:center;gap:10px;border:1.5px solid var(--line);border-radius:10px;padding:10px 12px;cursor:pointer;background:rgba(255,255,255,.03)}
.opt:has(input:checked){border-color:var(--gold);background:rgba(217,168,60,.12)}.opt b{display:block}.opt span{font-size:14px;color:var(--muted)}
.fmsg{margin:12px 0 0;font-weight:600;min-height:1.2em}.fmsg.ok{color:var(--green)}.fmsg.err{color:var(--red)}
/* about / reading */
.about p{font-size:17px}.contact{background:rgba(78,168,126,.12);border:1px solid rgba(78,168,126,.3);border-radius:12px;padding:16px 18px;margin-top:18px}
.mission{background:rgba(217,168,60,.08);border:1px solid rgba(217,168,60,.25);border-radius:12px;padding:16px 18px;margin-top:18px}
.mission h3{font-size:19px;margin-bottom:6px}
.soon{text-align:center;padding:50px 20px}.soon h3{font-size:30px;margin-bottom:8px}
.tip{background:rgba(217,168,60,.1);border:1px solid var(--gold);border-radius:var(--r);padding:16px 18px;margin-bottom:18px}
.tip b{color:#f0d9a0}
.flag{display:inline-block;font:800 12px 'Hanken Grotesk';letter-spacing:.1em;padding:5px 12px;border-radius:6px;margin:14px 0 2px}
.flag.must{background:rgba(217,95,104,.2);color:var(--red)}.flag.extra{background:rgba(217,168,60,.16);color:#f0d9a0;margin-top:22px}
.reading h4{margin-top:18px;color:#f0d9a0}
.ref{display:flex;gap:12px;padding:10px 0;border-bottom:1px solid rgba(240,217,160,.15)}
.ref:last-child{border-bottom:0}
.refn{flex:none;width:26px;height:26px;border-radius:50%;background:linear-gradient(135deg,var(--gold),#a87c1e);color:#1a1305;font:700 12px/26px 'Hanken Grotesk';text-align:center;box-shadow:0 4px 12px rgba(217,168,60,.4)}
.rt{font-weight:700}.stars{color:var(--gold);font-size:13px;font-weight:700}
.ref p{margin:4px 0;color:#d5cfbe;font-size:15px}.ref ul{margin:4px 0;padding-left:20px;columns:2;column-gap:28px;font-size:15px}
.shortlist{margin-top:16px;background:rgba(78,168,126,.12);border-left:4px solid var(--green);padding:10px 14px;border-radius:6px;font-size:15px}
footer{position:relative;z-index:2;background:rgba(11,14,23,.85);backdrop-filter:blur(10px);color:#c6cdda;text-align:center;padding:30px 16px;font-size:14.5px;border-top:1px solid rgba(217,168,60,.4)}
footer b{font:700 20px 'Fraunces',serif;color:#fff;display:block;margin-bottom:4px}footer a{color:#f0d9a0}
@media(max-width:620px){.brand span{display:none}.ref ul{columns:1}.nav{padding:0 8px;gap:8px}.p3{gap:6px}}
</style>
</head>
<body data-email="umairahmad7643@gmail.com">

<canvas id="bg3d"></canvas>
<div class="vignette"></div>

<nav class="nav" aria-label="Main">
  <a class="brand" href="#home" data-tab="home"><i>&sect;</i><span>UoL LLB Guide</span></a>
  <div class="links">
    <a href="#home" data-tab="home">Home</a>
    <a href="#modules" data-tab="modules">Modules</a>
    <a href="#exam" data-tab="exam">Exam Guidance</a>
    <a href="#qualifying" data-tab="qualifying">Qualifying Degree</a>
    <a href="#samples" data-tab="samples">Sample Notes</a>
    <a href="#reading" data-tab="reading">Further Reading</a>
    <a href="#purchase" data-tab="purchase">Purchase</a>
    <a href="#lawgat" data-tab="lawgat">LAW-GAT</a>
    <a href="#about" data-tab="about">About</a>
    <a href="#complaints" data-tab="complaints">Complaints</a>
  </div>
</nav>

<main>

<!-- HOME -->
<section id="home" class="tab">
  <div class="hero" id="hero3d">
    <p class="eyebrow">University of London LLB &middot; Levels 4, 5 &amp; 6</p>
    <h1>Study smarter for your LLB exams</h1>
    <p>Important topics, paper patterns, answer structures and techniques for every level, so you don&rsquo;t have to face the same problems and uncertainties others have.</p>
    <div class="stmt">&#10003; Get structured, exam-ready answers for UoL papers</div>
    <div class="cta"><a class="btn" href="#modules" data-tab="modules">Browse modules</a><a class="btn alt" href="#samples" data-tab="samples">Read free sample notes</a></div>
  </div>
  <div class="grid3">
    <div class="card feat tilt"><span class="n">01</span><h3>Every module covered</h3><p>Exam patterns and the topics that matter for all Level 4, 5 and 6 modules.</p></div>
    <div class="card feat tilt"><span class="n">02</span><h3>Exam technique</h3><p>IRAC, ILAC and MIRAT for problem questions; what &ldquo;discuss&rdquo; and &ldquo;critically evaluate&rdquo; really ask for.</p></div>
    <div class="card feat tilt"><span class="n">03</span><h3>Notes, answers &amp; checking</h3><p>Affordable notes, model answers, and marking for single questions or a full past paper.</p></div>
  </div>
  <div class="card glance glow">
    <h3>Full module notes at a glance</h3>
    <div class="p3"><div><span>Level 4 &middot; per module</span><b>PKR 2,000</b></div><div><span>Level 5 &middot; per module</span><b>PKR 2,500</b></div><div><span>Level 6 &middot; per module</span><b>PKR 3,000</b></div></div>
  </div>
</section>

<!-- MODULES -->
<section id="modules" class="tab">
  <div class="ph"><p class="eyebrow">Module directory</p><h2>Modules, patterns &amp; important topics</h2><p>Tap a level, then a module, to see its paper pattern and the topics to prioritise.</p></div>
  <details class="level" open><summary><span class="lv-t">Level 4 (Year 1)</span><span class="lv-p">Full module notes · PKR 2,000 per module</span></summary><div class="lv-body">
<details class="acc"><summary><span class="pill code">LA 1040</span><span class="acc-n">Contract Law</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt four questions from a choice of eight questions.</p>
<h4>Important topics</h4><ul><li>Offer and Acceptance</li><li>Intention</li><li>Consideration</li><li>Misrepresentation</li><li>Mistake</li><li>Frustration</li><li>Breach of Contract</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 1010</span><span class="acc-n">Criminal Law</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory Question | Part B: Attempt three questions from a choice of six questions.</p>
<h4>Important topics</h4><ul><li>Basics: Actus Reus, Mens Rea, factual and legal questions</li><li>Rape</li><li>Offences Against the Person</li><li>Property Offences</li><li>Criminal Damage</li><li>Criminal Attempt</li><li>Participation in Crime</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 1020</span><span class="acc-n">Public Law</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory Question | Part B: Attempt three questions from a choice of seven questions.</p>
<h4>Important topics</h4><ul><li>Rule of Law</li><li>Parliamentary Sovereignty</li><li>Royal Prerogative</li><li>Codified and Uncodified Constitution</li><li>Human Rights Act</li><li>Judicial Review</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 1031</span><span class="acc-n">Legal System and Method</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: MCQs | Part B: Attempt two questions from a choice of six questions | Part C: Compulsory Question</p>
<h4>Important topics</h4><ul><li>Judicial Precedent and Judicial Law Making</li><li>Statutory Interpretation</li></ul>
</div></details>
</div></details>
<details class="level"><summary><span class="lv-t">Level 5 (Year 2)</span><span class="lv-p">Full module notes · PKR 2,500 per module</span></summary><div class="lv-body">
<details class="acc"><summary><span class="pill code">LA 2001</span><span class="acc-n">Tort Law</span><span class="pill req">Required</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory Question (Article by Francis Ng) | Part B: Attempt three questions from a choice of eight questions.</p>
<p class="note">For the Francis Ng article, email umairahmad7643@gmail.com (see the About the Founder section).</p>
<h4>Important topics</h4><ul><li>Negligence (Duty of Care, Breach, Causation, Remoteness, Damages, Defences)</li><li>Psychiatric Harm</li><li>Pure Economic Loss (PEL)</li><li>Occupiers Liability Act (OLA)</li><li>Vicarious Liability</li><li>Nuisance (Public/Private) &amp; Rylands v Fletcher</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 2003</span><span class="acc-n">Property Law</span><span class="pill req">Required</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory Question | Part B: Attempt at least one question | Part C: Attempt at least one question. You can choose to answer the last question from either Part A or Part B. It is your call.</p>
<h4>Important topics</h4><ul><li>Unregistered and Registered Land</li><li>Adverse Possession</li><li>Easements</li><li>Mortgage</li><li>Licences and Leases</li><li>Co-ownership</li><li>Proprietary Estoppel</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 2024</span><span class="acc-n">EU Law</span><span class="pill req">Required</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Answer four questions from a choice of eight questions.</p>
<h4>Important topics</h4><ul><li>Essay questions: Direct Effect, Citizenship, Charter of Fundamental Rights, Preliminary Referencing</li><li>Problem questions: Direct Effect, Free movement of goods, Free movement of citizens and workers (these are different topics), Competition Policy, State Liability</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 2029</span><span class="acc-n">International Protection of Human Rights</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt three questions from a choice of seven questions.</p>
<h4>Important topics</h4><ul><li>Universalism vs Culturalism</li><li>Women&#x27;s Rights (CEDAW)</li><li>Refugee Rights</li><li>Child Rights</li><li>Religious Discrimination</li><li>Genocide and Crimes Against Humanity</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 2019</span><span class="acc-n">Family Law</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt four questions from a choice of eight questions.</p>
<h4>Important topics</h4><ul><li>Relationship Status</li><li>Dissolution</li><li>Financial Matters</li><li>Domestic Abuse</li><li>Children and Parentage</li><li>State Intervention</li><li>Adoption</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 2017</span><span class="acc-n">Commercial Law</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt three questions from a choice of six questions.</p>
<h4>Important topics</h4><ul><li>Sale of Goods Act 1979</li><li>International Sales</li><li>Consumer Protection</li><li>Agency and Security</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 2008</span><span class="acc-n">Administrative Law</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt three questions from a choice of six questions.</p>
<h4>Important topics</h4><ul><li>Foundation: Theory of Administrative Law</li><li>Government Processes</li><li>Judicial Review</li><li>Alternative Controls</li><li>Liability and Rights</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 2010</span><span class="acc-n">Introduction to Criminology</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Contact for details.</p>
</div></details>
</div></details>
<details class="level"><summary><span class="lv-t">Level 6 (Final Year)</span><span class="lv-p">Full module notes · PKR 3,000 per module</span></summary><div class="lv-body">
<details class="acc"><summary><span class="pill code">LA 3005</span><span class="acc-n">Jurisprudence</span><span class="pill req">Required</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory | Part B: Attempt three questions from a choice of nine questions.</p>
<h4>Important topics</h4><ul><li>Part A (compulsory): Naturalism, Liberalism, Ronald Dworkin&rsquo;s Theory</li><li>Part B (any three questions): Command Theory (John Austin), Marxism (Karl Marx), Pure Theory (Kelsen), Feminism, Distributive Theory (John Rawls)</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3011</span><span class="acc-n">Alternative Dispute Resolution</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory | Part B: Attempt two problem questions from a choice of three | Part C: Attempt one essay question from a choice of two.</p>
<h4>Important topics</h4><ul><li>Nature &amp; Purpose of ADR</li><li>Negotiation</li><li>Mediation (VERY IMPORTANT)</li><li>Arbitration (MOST IMPORTANT TOPIC)</li><li>Arbitration Law &amp; Principles</li><li>Confidentiality &amp; Without Prejudice Rule</li><li>ADR vs Litigation</li><li>Ethics in ADR</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3012</span><span class="acc-n">Company Law</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Essay &ndash; attempt one question from a choice of four | Part B: Problem &ndash; attempt one question from a choice of four. It is up to you whether to attempt more from either part.</p>
<h4>Important topics</h4><ul><li>Forms of Business Organisation</li><li>Separate Legal Personality</li><li>Lifting the Veil of Incorporation</li><li>Management of the Company</li><li>Director Duties</li><li>Enforcing Director Duties</li><li>Statutory Minority Protection</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3014</span><span class="acc-n">Conflict of Laws</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt three questions from a choice of six questions.</p>
<h4>Important topics</h4><ul><li>Domicile</li><li>Jurisdiction</li><li>Choice of Law &ndash; Tort</li><li>Choice of Law &ndash; Contract</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3014</span><span class="acc-n">Criminology</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt four questions from a choice of eight questions.</p>
<h4>Important topics</h4><ul><li>Crime Theories (CORE)</li><li>Causes of Crime</li><li>Punishment &amp; Sentencing</li><li>Policing &amp; Social Control</li><li>Victimology</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3015</span><span class="acc-n">Equity and Trusts</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory (25 marks, based on a Legal Article by Francis Ng) | Part B: Attempt three questions from a choice of eight questions.</p>
<p class="note">For the Francis Ng article, email umairahmad7643@gmail.com (see the About the Founder section).</p>
<h4>Important topics</h4><ul><li>Three Certainties</li><li>Formalities</li><li>Constitution</li><li>Charitable Purpose Trusts</li><li>Private Purpose Trusts</li><li>Resulting Trusts</li><li>Constructive Trusts (prepare as a backup)</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3007</span><span class="acc-n">Evidence</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Answer four questions from a choice of eight questions.</p>
<h4>Important topics</h4><ul><li>Burden &amp; Standard of Proof (CORE)</li><li>Admissibility of Evidence</li><li>Hearsay Evidence (VERY IMPORTANT)</li><li>Confessions</li><li>Character Evidence</li><li>Witnesses</li><li>Illegally Obtained Evidence</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3026</span><span class="acc-n">Intellectual Property Law</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Answer three questions from a choice of six questions.</p>
<h4>Important topics</h4><ul><li>Copyright (VERY IMPORTANT)</li><li>Patents</li><li>Trademarks</li><li>Defences &amp; Exceptions</li><li>IP vs Public Access</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3013</span><span class="acc-n">Public International Law</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt four questions from a choice of eight questions.</p>
<h4>Important topics</h4><ul><li>Sources of International Law (CORE)</li><li>State Responsibility (VERY IMPORTANT)</li><li>Use of Force</li><li>Jurisdiction</li><li>International Courts (ICJ)</li><li>Sovereignty vs Intervention</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3019</span><span class="acc-n">Introduction to Islamic Law</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Essay &ndash; attempt at least one | Part B: Problem &ndash; attempt at least one. You choose which part the last question comes from.</p>
<h4>Important topics</h4><ul><li>Essay: Primary Sources (Qur&rsquo;an &amp; Sunnah), Secondary Sources (Qiyas &amp; Ijma), Istihsan, Istishab, Ijtihad (standalone essay), Usul al-Fiqh (methods of interpretation), Six Periods of Islamic History</li><li>Problem &ndash; Family Law: Capacity to Marry, Marriage Conditions and Requirements, Duties of Husband and Wife, Polygamy, Maintenance, Custody, Dower (mahr), Dissolution of Marriage</li><li>Problem &ndash; Penal Law: Types of Offences (Hudud, Ta&rsquo;zir), Qisas and Diyat</li><li>Financial Law (prepare as a backup)</li><li>Core book: Q &amp; A&rsquo;s</li></ul>
</div></details>
<p class="fine">Dissertation: no exam, coursework only.</p>
</div></details>
</section>

<!-- EXAM GUIDANCE -->
<section id="exam" class="tab">
  <div class="ph"><p class="eyebrow">Exam guidance</p><h2>Techniques that earn marks</h2><p>How to structure problem questions and what each essay instruction word expects.</p></div>
  <div class="two">
    <div class="card glow tilt">
      <h3>&#9878;&#65039; Problem questions</h3>
      <h4 style="margin-top:14px;color:var(--green)">1. IRAC &mdash; the foundation</h4>
      <div class="step"><b>I &ndash; Issue</b>Identify the legal question and frame it precisely.<br><span class="bad">&#10060; &ldquo;Is there a trust?&rdquo;</span><br><span class="good">&#9989; &ldquo;Whether the wording satisfies certainty of intention for a valid express trust&rdquo;</span></div>
      <div class="step"><b>R &ndash; Rule</b>State the relevant principle with leading case authority and any tests or standards.</div>
      <div class="step key"><b>A &ndash; Application (MOST IMPORTANT)</b>Apply the rule directly to the facts using comparisons with case facts and logical reasoning. This is where most marks are won or lost.</div>
      <div class="step"><b>C &ndash; Conclusion</b>Give a clear, reasoned answer. Avoid vague conclusions like &ldquo;it depends&rdquo;.</div>
      <div class="box blue"><h4>&#128293; 2. Advanced IRAC (2:1 / First)</h4>
        <p style="margin:4px 0"><b>ILAC</b> (Issue &ndash; Law &ndash; Application &ndash; Conclusion): &ldquo;Rule&rdquo; becomes <i>Law</i> in depth, with multiple cases, exceptions and conflicting approaches.</p>
        <p style="margin:4px 0"><b>MIRAT</b>: Material facts &ndash; Issue &ndash; Rule &ndash; Application &ndash; Tentative conclusion (acknowledge ambiguity where relevant).</p></div>
      <div class="box blue"><h4>&#129504; 3. &ldquo;Apply, don&rsquo;t recite&rdquo;</h4>
        <p style="margin:4px 0">Examiners repeatedly penalise students who state correct law but fail to apply it. Link every principle directly to the facts using phrases like &ldquo;Here,&rdquo; &ldquo;On these facts,&rdquo; &ldquo;This is similar to&hellip;&rdquo; and &ldquo;Unlike in [case]&hellip;&rdquo;.</p></div>
      <div class="box blue"><h4>&#9878;&#65039; 4. Issue-spotting</h4>
        <p style="margin:4px 0">Identify <b>all</b> possible issues, not just the obvious one. In trusts: certainty of intention, subject matter and objects, constitution, formalities. Missing one major issue means a mark drop.</p></div>
      <div class="box blue"><h4>&#129513; 5. Layered application</h4>
        <ul><li>Apply the main rule</li><li>Introduce exceptions</li><li>Consider alternative outcomes</li></ul></div>
      <div class="box red"><h4>&#9888;&#65039; 6. Common structural mistakes</h4>
        <ul><li>Writing long introductions</li><li>Explaining law with no application</li><li>Mixing multiple issues in one paragraph</li><li>No clear conclusion</li><li>Case dumping without relevance</li></ul></div>
    </div>
    <div class="card glow tilt">
      <h3>&#128221; Essay questions</h3>
      <div class="q"><b>1. &ldquo;Discuss&rdquo;</b><span>Present multiple perspectives, explain the law accurately, analyse (don&rsquo;t just describe) and reach a reasoned conclusion. It does <u>not</u> mean listing cases or pure explanation. Examiners expect a balanced weighing of arguments, judicial approaches and academic commentary.</span></div>
      <div class="q"><b>2. &ldquo;To what extent&rdquo;</b><span>Explicitly evaluative: &ldquo;how far is this statement true?&rdquo; Argument for &rarr; argument against &rarr; final judgment on the degree of correctness. Avoid a one-sided answer.</span></div>
      <div class="q"><b>3. &ldquo;Critically analyse / critically evaluate&rdquo;</b><span>2:1 / First-class territory. Go beyond what the law is: assess effectiveness, fairness, consistency and policy implications. Include case law, academic opinion, judicial criticism and your own reasoned stance.</span></div>
      <div class="q"><b>4. &ldquo;Assess&rdquo;</b><span>Very similar to &ldquo;critically evaluate&rdquo; but slightly more flexible. Measure strengths and weaknesses and reach a clear judgment.</span></div>
      <div class="q"><b>5. &ldquo;Explain&rdquo;</b><span>Lower-level but still important. Give a clear, accurate account of principles and rules; minimal evaluation unless implied.</span></div>
      <div class="q"><b>6. &ldquo;Analyse&rdquo;</b><span>Between explanation and critique. Break the issue into parts, show how principles interact and identify the underlying reasoning.</span></div>
      <div class="q"><b>7. &ldquo;Consider&rdquo;</b><span>A softer &ldquo;discuss&rdquo;. Explore arguments; a strong conclusion is not strictly required but is still expected at UoL level.</span></div>
      <div class="q"><b>8. &ldquo;Evaluate&rdquo;</b><span>Judge the value or success of something. Requires criteria such as fairness, certainty or efficiency.</span></div>
    </div>
  </div>
</section>

<!-- QUALIFYING DEGREE -->
<section id="qualifying" class="tab">
  <div class="ph"><p class="eyebrow">Good to know</p><h2>Meaning of a Qualifying Degree and the modules required for it</h2></div>
  <div class="card glow" style="border-left:6px solid var(--gold)">
    <p style="font-size:18px;margin-top:0">For a University of London LLB, the key thing to understand is that while subjects like <b>Tort Law, Property Law, and European Union Law</b> form part of the traditional core of a Qualifying Law Degree, your choice of optional modules does not determine whether you can become a lawyer. Entry into the Solicitors Qualifying Examination or the Bar is based on passing professional training stages, not specific module selection.</p>
    <p style="font-size:18px;margin-bottom:0">However, choosing academically strong and relevant modules can give you a real advantage in legal understanding, exam performance, and future preparation, even though it is not a strict requirement.</p>
  </div>
</section>

<!-- SAMPLE NOTES -->
<section id="samples" class="tab">
  <div class="ph"><p class="eyebrow">Free to read</p><h2>Sample notes</h2><p>One page of notes from each module is free. Open a module to read it; the rest of the notes are available when you purchase them.</p></div>
  <h3 class="lvh">Level 4</h3>
<details class="acc"><summary><span class="pill code">LA 1040</span><span class="acc-n">Contract Law</span></summary><div class="acc-b notes">
<h4>1. Offer and invitation to treat</h4>
<p><strong>Offer:</strong> a clear, definite expression of willingness to contract on stated terms, intended to become binding once accepted. An invitation to treat invites offers or negotiation; it is not itself an offer.</p>
<h4>Displays and advertisements</h4>
<ul>
<li><strong>Fisher v Bell [1961]</strong> &mdash; A flick knife displayed in a shop window was an invitation to treat, not an offer for sale.</li>
<li><strong>Pharmaceutical Society of Great Britain v Boots [1953]</strong> &mdash; Shelf displays were invitations to treat; the customer made the offer at the till, where the sale was accepted.</li>
<li><strong>Thornton v Shoe Lane Parking [1971]</strong> &mdash; A machine-operated car park made an offer; the customer accepted by entering/using the machine in the manner indicated.</li>
<li><strong>Partridge v Crittenden [1968]</strong> &mdash; An ordinary advertisement offering birds for sale was an invitation to treat, not an offer to sell to everyone who responded.</li>
<li><strong>Carlill v Carbolic Smoke Ball Co [1893]</strong> &mdash; An advertisement can be a unilateral offer where its wording shows a definite promise to anyone who performs specified conditions.</li>
</ul>
<h4>Termination of an offer</h4>
<ul>
<li><strong>Routledge v Grant (1828)</strong> &mdash; An offeror may revoke an offer before acceptance even if the offer stated it would remain open for a period, unless an option is supported by consideration.</li>
<li><strong>Byrne v Van Tienhoven (1880)</strong> &mdash; Revocation is effective only when communicated to the offeree; posting a revocation is not enough.</li>
<li><strong>Errington v Errington and Woods [1952]</strong> &mdash; Once performance of a unilateral offer had begun, the offeror could not revoke it so as to prevent completion.</li>
<li><strong>Hyde v Wrench (1840)</strong> &mdash; A counter-offer rejects and terminates the original offer.</li>
</ul>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 1010</span><span class="acc-n">Criminal Law</span></summary><div class="acc-b notes"><p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 1020</span><span class="acc-n">Public Law</span></summary><div class="acc-b notes"><p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 1031</span><span class="acc-n">Legal System and Method</span></summary><div class="acc-b notes">
<h4>Legal System and Method &mdash; Exam Notes</h4>
<h4>Civil and criminal proceedings</h4>
<p>Civil proceeding resolves disputes about legal rights and obligations. Criminal proceeding determines whether the accused has committed an offence; the prosecution must prove guilt beyond reasonable doubt.</p>
<h4>Court structure in England and Wales</h4>
<p>The UK Supreme Court was established in 2009 under the Constitutional Reform Act 2005. It hears civil appeals from across the UK and criminal appeals from England, Wales and Northern Ireland; permission is ordinarily required, and cases usually involve a point of law of public importance.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<h3 class="lvh">Level 5</h3>
<details class="acc"><summary><span class="pill code">LA 2001</span><span class="acc-n">Tort Law</span></summary><div class="acc-b notes"><p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 2003</span><span class="acc-n">Property Law</span></summary><div class="acc-b notes"><p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 2024</span><span class="acc-n">European Union Law</span></summary><div class="acc-b notes"><p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<h3 class="lvh">Level 6</h3>
<details class="acc"><summary><span class="pill code">LA 3005</span><span class="acc-n">Jurisprudence</span><span class="pill req">Required</span></summary><div class="acc-b notes">
<h4>Legal Positivism: John Austin</h4>
<p>Legal positivism distinguishes what the law is from whether the law is morally good. Austin&rsquo;s command theory defines positive law as a command issued by a political superior to political inferiors and backed by a sanction. The <strong>sovereign</strong> is a determinate human superior whom the bulk of society habitually obeys and who does not habitually obey another.</p>
<h4>Criticisms of Austin</h4>
<ul>
<li>Modern states divide authority among legislatures, courts and executives; a single unlimited sovereign is difficult to identify.</li>
<li>Power-conferring rules enable legal acts rather than simply threaten punishment.</li>
<li>International law and custom are treated as law in modern practice despite lacking a centralised sovereign and sanction structure.</li>
</ul>
<h4>Hart&rsquo;s refinement</h4>
<p>Law is a system of rules: primary rules impose duties; secondary rules govern identification, change and adjudication, anchored by a rule of recognition and the internal point of view.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3012</span><span class="acc-n">Company Law</span></summary><div class="acc-b notes">
<h4>Separate legal personality</h4>
<ul>
<li><strong>Salomon v A Salomon &amp; Co Ltd [1897]</strong> &mdash; a properly incorporated company is legally separate from its controller.</li>
<li><strong>Macaura v Northern Assurance [1925]</strong> &mdash; company assets belong to the company, not shareholders.</li>
<li><strong>Lee v Lee&rsquo;s Air Farming [1961]</strong> &mdash; control and employment by the company can coexist.</li>
</ul>
<h4>Veil piercing</h4>
<ul>
<li><strong>Adams v Cape Industries [1990]</strong> &mdash; no general power to disregard a corporate group merely because justice seems to require it.</li>
<li><strong>Gilford Motor v Horne [1933]</strong> &mdash; a company interposed to evade a pre-existing obligation may be restrained.</li>
<li><strong>Prest v Petrodel [2013]</strong> &mdash; the evasion principle is narrow; piercing may apply where a person subject to an obligation interposes a company to frustrate enforcement.</li>
</ul>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3015</span><span class="acc-n">Equity and Trusts</span></summary><div class="acc-b notes">
<h4>What is a trust?</h4>
<p>A trust separates legal title from beneficial ownership. The trustee holds legal title and must deal with the property for beneficiaries or a legally permitted purpose.</p>
<h4>Trusts arising by operation of law</h4>
<p><strong>FHR European Ventures v Cedar Capital [2014]</strong> &mdash; a bribe or secret commission received by a fiduciary is held on constructive trust for the principal.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3019</span><span class="acc-n">Introduction to Islamic Law</span></summary><div class="acc-b notes">
<h4>Shariah and fiqh</h4>
<p>Shariah refers to the divinely ordained path; fiqh is the human juristic understanding of that guidance, capable of disagreement and development.</p>
<h4>Principal sources</h4>
<p>Qur&rsquo;an, Sunnah, Ijma (consensus) and Qiyas (analogical reasoning), alongside istihsan, maslahah, istishab and &rsquo;urf whose status varies between schools.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
</section>

<!-- FURTHER READING -->
<section id="reading" class="tab">
  <div class="ph"><p class="eyebrow">Level 6</p><h2>Further reading</h2><p>Extra reading beyond the module guide, including articles worth reading for higher marks.</p></div>
  <div class="tip"><b>Tip:</b> Read to the extent that you can remember and quote in an exam realistically. Don&rsquo;t try to read more than you can understand and remember.</div>
  <details class="acc"><summary><span class="acc-n">Company Law</span></summary><div class="acc-b reading"><div class="flag must">MUST READ</div>
<div class="ref"><span class="refn">1</span><div><div class="rt">Hansmann &amp; Kraakman &mdash; The Essential Role of Organizational Law</div></div></div>
<div class="ref"><span class="refn">2</span><div><div class="rt">Watkins &amp; Nsubuga &mdash; The Road to Prest</div></div></div>
<div class="ref"><span class="refn">3</span><div><div class="rt">Keay &mdash; Fraudulent Trading: The Intent to Defraud Element</div></div></div>
<div class="ref"><span class="refn">4</span><div><div class="rt">Keay &mdash; The Duty of Directors to Take Account of Creditors&rsquo; Interests</div></div></div>
<div class="ref"><span class="refn">5</span><div><div class="rt">McVea &mdash; Section 994 of the Companies Act 2006 and the Primacy of Contract</div></div></div>
<div class="flag extra">READ IF YOU HAVE EXTRA TIME</div>
<div class="ref"><span class="refn">6</span><div><div class="rt">Leebron &mdash; Limited Liability, Tort Victims and Creditors</div></div></div>
</div></details>
<details class="acc"><summary><span class="acc-n">Jurisprudence</span></summary><div class="acc-b reading"><div class="flag must">MUST READ</div>
<div class="ref"><div><div class="rt">Legal Interpretivism &mdash; Stanford Encyclopedia of Philosophy</div></div></div>
<div class="ref"><div><div class="rt">Mill&rsquo;s Moral and Political Philosophy &mdash; SEP</div></div></div>
<div class="ref"><div><div class="rt">Berlin &mdash; &ldquo;Two Concepts of Liberty&rdquo;</div></div></div>
<div class="ref"><div><div class="rt">John Rawls &mdash; SEP &middot; Original Position &mdash; SEP</div></div></div>
<div class="ref"><div><div class="rt">John Austin &mdash; SEP</div></div></div>
</div></details>
<details class="acc"><summary><span class="acc-n">Equity and Trusts</span></summary><div class="acc-b reading">
<div class="ref"><span class="refn">1</span><div><div class="rt">J.E. Penner &mdash; The Law of Trusts (12th ed)</div><div class="stars">Priority: ★★★★★</div></div></div>
<div class="ref"><span class="refn">2</span><div><div class="rt">Graham Virgo &mdash; The Principles of Equity and Trusts</div><div class="stars">Priority: ★★★★★</div></div></div>
<div class="ref"><div><div class="rt">Y.K. Liew &mdash; Rationalising Constructive Trusts</div></div></div>
<div class="shortlist"><strong>Shortlist:</strong> Penner &rarr; Virgo &rarr; targeted article on the specific controversy.</div>
</div></details>
<details class="acc"><summary><span class="acc-n">Alternative Dispute Resolution</span></summary><div class="acc-b reading">
<div class="ref"><div><div class="rt">Roberts &amp; Palmer &mdash; Dispute Processes: ADR and the Primary Forms of Decision-Making</div><div class="stars">Priority: ★★★★★</div></div></div>
<div class="ref"><div><div class="rt">Cappelletti &mdash; &ldquo;Alternative Dispute Resolution Processes within the Framework of the World-Wide Access-to-Justice Movement&rdquo;</div></div></div>
<div class="ref"><div><div class="rt">Sander &amp; Rozdeiczer &mdash; &ldquo;Matching Cases and Dispute Resolution Procedures&rdquo;</div></div></div>
<div class="ref"><div><div class="rt">Redfern &amp; Hunter &mdash; International Arbitration</div></div></div>
</div></details>
<details class="acc"><summary><span class="acc-n">Evidence</span></summary><div class="acc-b reading">
<div class="ref"><span class="refn">1</span><div><div class="rt">A. Choo &mdash; Evidence (7th ed)</div></div></div>
<div class="ref"><div><div class="rt">Roberts &amp; Zuckerman &mdash; Criminal Evidence</div></div></div>
<div class="ref"><div><div class="rt">Further reading: hearsay, expert evidence, confessions, character evidence</div></div></div>
</div></details>
<details class="acc"><summary><span class="acc-n">Public International Law</span></summary><div class="acc-b reading">
<div class="ref"><span class="refn">1</span><div><div class="rt">Mansell &amp; Openshaw &mdash; International Law: A Critical Introduction</div></div></div>
<div class="ref"><span class="refn">2</span><div><div class="rt">Wallace &amp; Martin-Ortega &mdash; International Law</div></div></div>
<div class="ref"><div><div class="rt">Antony Anghie &mdash; Imperialism, Sovereignty and the Making of International Law</div><div class="stars">Priority: ★★★★★</div></div></div>
</div></details>
<details class="acc"><summary><span class="acc-n">Intellectual Property Law</span></summary><div class="acc-b reading">
<div class="ref"><span class="refn">1</span><div><div class="rt">Bently, Sherman, Gangjee &amp; Johnson &mdash; Intellectual Property Law (6th ed)</div></div></div>
<div class="ref"><span class="refn">2</span><div><div class="rt">Cornish, Llewelyn &amp; Aplin &mdash; Intellectual Property (10th ed)</div></div></div>
<div class="ref"><div><div class="rt">Siva Vaidhyanathan &mdash; Intellectual Property: A Very Short Introduction</div></div></div>
</div></details>
<details class="acc"><summary><span class="acc-n">Conflict of Laws</span></summary><div class="acc-b reading">
<div class="ref"><span class="refn">1</span><div><div class="rt">David McClean &mdash; Morris: The Conflict of Laws (11th ed, 2025)</div></div></div>
<div class="ref"><span class="refn">2</span><div><div class="rt">Adrian Briggs &mdash; The Conflict of Laws</div></div></div>
</div></details>
<details class="acc"><summary><span class="acc-n">Islamic Law</span></summary><div class="acc-b reading">
<div class="ref"><span class="refn">1</span><div><div class="rt">M.A. Baderin &mdash; Islamic Law: A Very Short Introduction (2021)</div></div></div>
<div class="ref"><span class="refn">2</span><div><div class="rt">M.H. Kamali &mdash; Principles of Islamic Jurisprudence</div></div></div>
<div class="ref"><span class="refn">3</span><div><div class="rt">N.J. Coulson &mdash; A History of Islamic Law</div><div class="stars">Priority: ★★★★</div></div></div>
</div></details>
</section>

<!-- PURCHASE -->
<section id="purchase" class="tab">
  <div class="ph"><p class="eyebrow">Purchase</p><h2>Notes, answers &amp; checking</h2></div>
  <div class="banner">&#10003; Get structured, exam-ready answers for UoL papers</div>

  <h2 class="sec" style="margin-top:0">&#128218; Module notes</h2>
  <div class="card glow" style="margin-bottom:16px"><h3 style="font-size:20px">Full module notes</h3><p class="muted" style="margin:6px 0 0">The complete notes for a module, per module.</p>
    <div class="p3"><div><span>Level 4</span><b>PKR 2,000</b></div><div><span>Level 5</span><b>PKR 2,500</b></div><div><span>Level 6</span><b>PKR 3,000</b></div></div></div>
  <div class="tier t-green"><div class="tier-h"><div><h3>🟢 Tier 1: Basic (Entry Level)</h3><p>For students who just want cheap help to pass</p></div></div><div class="tier-b"><ul class="ticks"><li>Concise exam-focused notes</li><li>Key topics only (no deep explanations)</li><li>Bullet-point summaries</li></ul><div class="p3"><div><span>Level 4</span><b>PKR 1,500</b></div><div><span>Level 5</span><b>PKR 2,500</b></div><div><span>Level 6</span><b>PKR 3,500</b></div></div></div></div>

  <h2 class="sec">&#10067; Paid answers</h2>
  <div class="tier t-green"><div class="tier-h"><div><h3>🟢 Tier 1: Basic Answer</h3><p>For students who just want something to submit/pass</p></div></div><div class="tier-b"><ul class="ticks"><li>Direct answer</li><li>Basic structure</li><li>Minimal case law</li><li>600&ndash;900 words</li></ul><div class="p3"><div><span>Level 4</span><b>PKR 500</b></div><div><span>Level 5</span><b>PKR 700</b></div><div><span>Level 6</span><b>PKR 1,000</b></div></div><p class="pos">&ldquo;Simple Pass Answer&rdquo;</p></div></div>
  <div class="tier t-blue"><div class="tier-h"><div><h3>🔵 Tier 2: Standard Answer</h3><p>Our main offering</p></div><span class="badge">BEST SELLER</span></div><div class="tier-b"><ul class="ticks"><li>Proper IRAC / essay structure</li><li>Relevant case law</li><li>Clear arguments + application</li><li>900&ndash;1,500 words</li></ul><div class="p3"><div><span>Level 4</span><b>PKR 1,000</b></div><div><span>Level 5</span><b>PKR 1,500</b></div><div><span>Level 6</span><b>PKR 2,000</b></div></div><p class="pos">&ldquo;Exam-Ready Answer&rdquo;</p></div></div>
  <div class="tier t-red"><div class="tier-h"><div><h3>🔴 Tier 3: Premium Answer</h3><p>For serious students aiming for higher marks</p></div><span class="badge">HIGH VALUE</span></div><div class="tier-b"><ul class="ticks"><li>Everything in Standard</li><li>Strong case law integration</li><li>Critical analysis + evaluation</li><li>Polished structure (first-class style)</li><li>1,500&ndash;2,500 words</li></ul><div class="p3"><div><span>Level 4</span><b>PKR 1,500</b></div><div><span>Level 5</span><b>PKR 2,500</b></div><div><span>Level 6</span><b>PKR 3,500</b></div></div><p class="pos">&ldquo;High-Scoring Model Answer&rdquo;</p></div></div>

  <h2 class="sec">&#128230; Bundle pricing</h2>
  <div class="bundles"><div class="bundle tilt"><h3>4 Answers Pack</h3><div class="brow"><span>Level 4</span><b>PKR 2,500</b></div><div class="brow"><span>Level 5</span><b>PKR 4,000</b></div><div class="brow"><span>Level 6</span><b>PKR 6,000</b></div></div><div class="bundle hl tilt"><h3>6 Answers Pack<span class="badge">BEST VALUE</span></h3><div class="brow"><span>Level 4</span><b>PKR 4,000</b></div><div class="brow"><span>Level 5</span><b>PKR 6,500</b></div><div class="brow"><span>Level 6</span><b>PKR 10,000</b></div></div><div class="bundle tilt"><h3>10 Answers Pack</h3><div class="brow"><span>Level 4</span><b>PKR 7,500</b></div><div class="brow"><span>Level 5</span><b>PKR 12,000</b></div><div class="brow"><span>Level 6</span><b>PKR 18,000</b></div></div></div>

  <h2 class="sec">&#128184; Add-ons</h2>
  <div class="addons"><div class="card tilt"><h3>&#9889; Urgent delivery (12&ndash;24 hrs)</h3><b>PKR 500 &ndash; 1,000</b></div><div class="card tilt"><h3>&#9997;&#65039; Extra length / deep analysis</h3><b>PKR 500 &ndash; 1,500</b></div></div>
  <div class="rules"><b>&#9888;&#65039; Important rules</b><ul><li>Each tier has a word limit.</li><li>Standard delivery time is 24&ndash;48 hours.</li><li>An extra charge applies for urgent work.</li></ul></div>

  <h2 class="sec">&#9989; Get your answers checked</h2>
  <div class="check-intro"><h3>Two ways to get marked</h3>
    <p class="muted" style="margin:6px 0 0">Check a single question, or submit an entire past paper. For a full paper, choose how quickly you need it back.</p>
    <div class="speed"><div><b>&#9889; Fast track</b><span>Full paper marked within 1 day</span></div><div><b>&#128337; Regular</b><span>Full paper marked within 3 days</span></div><div><b>&#127919; Individual questions</b><span>Available for Levels 4, 5 and 6 below</span></div></div>
    <p class="fine" style="margin-top:12px">Fees for full-paper checking are confirmed by email after you submit.</p></div>
  <div class="forms"><form class="card form glow" data-fs action="https://formspree.io/f/xgodbanw" method="POST"><h3>Get a full past paper checked</h3><p class="muted">Attempted an entire past paper? Submit all your answers and get them marked with feedback.</p><input type="hidden" name="service" value="Full past paper checking"><input type="hidden" name="_subject" value="New full-paper checking request"><label class="f"><span>Your name</span><input type="text" name="name" placeholder="Full name" required></label><label class="f"><span>Email address</span><input type="email" name="email" placeholder="you@example.com" required></label><label class="f"><span>Level</span><select name="level" required><option value="">Select&hellip;</option><option value="Level 4">Level 4</option><option value="Level 5">Level 5</option><option value="Level 6">Level 6</option></select></label><label class="f"><span>Module</span><input type="text" name="module" placeholder="e.g. Tort Law (LA 2001)" required></label><label class="f"><span>Paper (year / session)</span><input type="text" name="paper" placeholder="e.g. 2024 exam paper" required></label><div class="turn"><span class="lbl">Turnaround</span><label class="opt"><input type="radio" name="turnaround" value="Fast track – marked within 1 day" required><span><b>Fast track</b>Marked within 1 day</span></label><label class="opt"><input type="radio" name="turnaround" value="Regular – marked within 3 days"><span><b>Regular</b>Marked within 3 days</span></label></div><label class="f"><span>Your answers</span><textarea name="answers" rows="9" placeholder="Paste all your answers here, or paste a link to a shared document." required></textarea></label><label class="f"><span>Notes for the marker</span><textarea name="additional_info" rows="3" placeholder="Target grade, areas you are worried about, etc. (optional)"></textarea></label><button class="btn" type="submit">Submit paper for checking</button><p class="fmsg" role="status"></p></form><form class="card form glow" data-fs action="https://formspree.io/f/xgodbanw" method="POST"><h3>Individual questions &mdash; submit up to 10</h3><p class="muted">Send a past-paper question (or up to 10 of them) for a written answer. Pick a tier, or a bundle for 4, 6 or 10 answers.</p><input type="hidden" name="service" value="Individual question(s)"><input type="hidden" name="_subject" value="New question submission"><label class="f"><span>Your name</span><input type="text" name="name" placeholder="Full name" required></label><label class="f"><span>Email address</span><input type="email" name="email" placeholder="you@example.com" required></label><label class="f"><span>Level</span><select name="level" required><option value="">Select&hellip;</option><option value="Level 4">Level 4</option><option value="Level 5">Level 5</option><option value="Level 6">Level 6</option></select></label><label class="f"><span>Answer tier</span><select name="answer_tier" required><option value="">Select&hellip;</option><option value="Basic">Tier 1 &ndash; Basic (Simple Pass Answer)</option><option value="Standard">Tier 2 &ndash; Standard (Exam-Ready Answer) &ndash; BEST SELLER</option><option value="Premium">Tier 3 &ndash; Premium (High-Scoring Model Answer)</option></select></label><label class="f"><span>Single question or bundle</span><select name="bundle_type" required><option value="">Select&hellip;</option><option value="Single question">Single question</option><option value="4 answers pack">4 Answers Pack</option><option value="6 answers pack">6 Answers Pack (best value)</option><option value="10 answers pack">10 Answers Pack</option></select></label><label class="f"><span>Module name(s)</span><input type="text" name="modules" placeholder="e.g. Contract Law, Tort Law" required></label><label class="f"><span>Your question(s)</span><textarea name="questions" rows="9" placeholder="Paste your question(s). If sending several, number them 1, 2, 3 &hellip; (maximum 10 per submission)." required></textarea></label><div class="checks"><label><input type="checkbox" name="urgent_delivery" value="yes"> Urgent delivery (12&ndash;24 hrs) &ndash; PKR 500&ndash;1,000</label><label><input type="checkbox" name="extra_analysis" value="yes"> Extra length / deep analysis &ndash; PKR 500&ndash;1,500</label></div><label class="f"><span>Additional instructions</span><textarea name="additional_instructions" rows="3" placeholder="Optional"></textarea></label><button class="btn" type="submit">Submit question(s)</button><p class="fmsg" role="status"></p></form></div>

  <h2 class="sec">&#128221; Order notes</h2>
  <div class="forms"><form class="card form glow" data-fs action="https://formspree.io/f/mqenoeov" method="POST"><h3>Order notes</h3><p class="muted">Tell us which module you need and we will reply by email.</p><input type="hidden" name="_subject" value="New notes order"><label class="f"><span>Your name</span><input type="text" name="name" placeholder="Full name" required></label><label class="f"><span>Email address</span><input type="email" name="email" placeholder="you@example.com" required></label><label class="f"><span>Level</span><select name="level" required><option value="">Select&hellip;</option><option value="Level 4">Level 4</option><option value="Level 5">Level 5</option><option value="Level 6">Level 6</option></select></label><label class="f"><span>Notes tier</span><select name="notes_tier" required><option value="">Select&hellip;</option><option value="Full module notes">Full module notes (L4 PKR 2,000 / L5 PKR 2,500 / L6 PKR 3,000)</option><option value="Tier 1 Basic notes">Tier 1: Basic notes (L4 PKR 1,500 / L5 PKR 2,500 / L6 PKR 3,500)</option></select></label><label class="f"><span>Module name</span><input type="text" name="module" placeholder="e.g. Contract Law (LA 1040)" required></label><label class="f"><span>Anything else?</span><textarea name="additional_info" rows="3" placeholder="Special requests (optional)"></textarea></label><button class="btn" type="submit">Submit notes order</button><p class="fmsg" role="status"></p></form></div>
</section>

<!-- LAW-GAT -->
<section id="lawgat" class="tab">
  <div class="ph"><p class="eyebrow">LAW-GAT</p><h2>LAW-GAT</h2></div>
  <div class="card soon glow"><h3>Coming soon</h3><p class="muted">This section is being prepared. Questions? Email <a href="mailto:umairahmad7643@gmail.com">umairahmad7643@gmail.com</a>.</p></div>
</section>

<!-- ABOUT -->
<section id="about" class="tab">
  <div class="ph"><p class="eyebrow">About</p><h2>About the founder</h2></div>
  <div class="card about glow">
    <p style="margin-top:0">This platform was created by a University of London LLB graduate who understands the challenges of this demanding programme. Having experienced the difficulties first-hand, the founder is committed to helping students who have just enrolled, or are already enrolled, achieve their academic goals.</p>
    <div class="mission"><h3>Mission</h3><p style="margin:0;font-size:16px">To guide University of London LLB students so they don&rsquo;t have to face the same problems and uncertainties. By sharing structured exam guidance, important topics and affordable study materials, this platform aims to help students at every level approach their examinations with confidence.</p></div>
    <div class="contact"><b>&#128222; Contact</b><br><a href="mailto:umairahmad7643@gmail.com">umairahmad7643@gmail.com</a><p class="muted" style="font-size:15px;margin:6px 0 0">For the Francis Ng articles (Tort Law, Equity and Trusts), email the address above.</p></div>
  </div>
</section>

<!-- COMPLAINTS -->
<section id="complaints" class="tab">
  <div class="ph"><p class="eyebrow">Feedback</p><h2>Submit a complaint</h2><p>Found an error or inaccuracy in any module information on this website? Please tell us so we can fix it.</p></div>
  <div class="forms" style="grid-template-columns:minmax(0,640px)"><form class="card form glow" data-fs action="https://formspree.io/f/mwvyjvdn" method="POST"><h3>Report an error</h3><input type="hidden" name="_subject" value="Website error report"><label class="f"><span>Your name</span><input type="text" name="name" placeholder="Your name" required></label><label class="f"><span>Email address</span><input type="email" name="email" placeholder="you@example.com" required></label><label class="f"><span>Module / section</span><input type="text" name="module" placeholder="Which module or section has an error?" required></label><label class="f"><span>Description of the error</span><textarea name="complaint" rows="6" placeholder="Please describe the error or issue in detail&hellip;" required></textarea></label><button class="btn" type="submit">Submit complaint</button><p class="fmsg" role="status"></p></form></div>
</section>

</main>

<footer><b>UoL LLB Guide</b>Helping University of London LLB students prepare with confidence.<br><a href="mailto:umairahmad7643@gmail.com">umairahmad7643@gmail.com</a><br>&copy; 2026 UoL LLB Guide</footer>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script>
/* ================= 3D BACKGROUND ================= */
(function(){
  var canvas=document.getElementById('bg3d');
  var renderer=new THREE.WebGLRenderer({canvas:canvas,antialias:true,alpha:true});
  renderer.setPixelRatio(Math.min(window.devicePixelRatio,2));
  renderer.setSize(window.innerWidth,window.innerHeight);
  var scene=new THREE.Scene();
  scene.fog=new THREE.FogExp2(0x0b0e17,0.028);
  var camera=new THREE.PerspectiveCamera(60,window.innerWidth/window.innerHeight,.1,100);
  camera.position.set(0,0,14);

  scene.add(new THREE.AmbientLight(0x334466,.8));
  var key=new THREE.PointLight(0xd9a83c,1.4,60);key.position.set(8,10,10);scene.add(key);
  var rim=new THREE.PointLight(0x7a1d2c,1.2,60);rim.position.set(-10,-6,6);scene.add(rim);

  // Floating wireframe solids — "pillars of law"
  var group=new THREE.Group();scene.add(group);
  var geos=[new THREE.IcosahedronGeometry(1,0),new THREE.OctahedronGeometry(1,0),new THREE.TorusGeometry(1,.35,10,28),new THREE.DodecahedronGeometry(1,0)];
  var cols=[0xd9a83c,0x7a1d2c,0x4d84c4,0x4ea87e];
  var solids=[];
  for(var i=0;i<16;i++){
    var m=new THREE.Mesh(geos[i%4],new THREE.MeshBasicMaterial({color:cols[i%4],wireframe:true,transparent:true,opacity:.35}));
    m.position.set((Math.random()-.5)*26,(Math.random()-.5)*16,(Math.random()-.5)*10-2);
    m.scale.setScalar(.5+Math.random()*1.1);
    m.userData={rx:(Math.random()-.5)*.01,ry:(Math.random()-.5)*.012,fy:Math.random()*Math.PI*2,fs:.2+Math.random()*.5,by:m.position.y};
    group.add(m);solids.push(m);
  }

  // Particle field (golden dust)
  var N=900,pos=new Float32Array(N*3);
  for(var j=0;j<N;j++){pos[j*3]=(Math.random()-.5)*60;pos[j*3+1]=(Math.random()-.5)*40;pos[j*3+2]=(Math.random()-.5)*30;}
  var pg=new THREE.BufferGeometry();pg.setAttribute('position',new THREE.BufferAttribute(pos,3));
  var pts=new THREE.Points(pg,new THREE.PointsMaterial({color:0xd9a83c,size:.07,transparent:true,opacity:.7}));
  scene.add(pts);

  // Mouse parallax
  var mx=0,my=0,tx=0,ty=0;
  window.addEventListener('mousemove',function(e){mx=(e.clientX/window.innerWidth-.5)*2;my=(e.clientY/window.innerHeight-.5)*2;});
  window.addEventListener('resize',function(){camera.aspect=window.innerWidth/window.innerHeight;camera.updateProjectionMatrix();renderer.setSize(window.innerWidth,window.innerHeight);});

  var clock=new THREE.Clock();
  (function anim(){
    requestAnimationFrame(anim);
    var t=clock.getElapsedTime();
    tx+=(mx-tx)*.04;ty+=(my-ty)*.04;
    camera.position.x=tx*1.6;camera.position.y=-ty*1.2;camera.lookAt(0,0,0);
    solids.forEach(function(s){s.rotation.x+=s.userData.rx;s.rotation.y+=s.userData.ry;s.position.y=s.userData.by+Math.sin(t*s.userData.fs+s.userData.fy)*.6;});
    pts.rotation.y=t*.015;
    renderer.render(scene,camera);
  })();
})();

/* ================= TABS ================= */
(function(){
  var tabs=[].slice.call(document.querySelectorAll('.tab'));
  var links=[].slice.call(document.querySelectorAll('.links a'));
  function show(id,push){
    if(!document.getElementById(id)) id='home';
    tabs.forEach(function(t){t.classList.toggle('on',t.id===id)});
    links.forEach(function(a){a.classList.toggle('on',a.dataset.tab===id)});
    var on=document.querySelector('.links a.on'); if(on&&on.scrollIntoView){try{on.scrollIntoView({inline:'center',block:'nearest'})}catch(e){}}
    if(push!==false){try{history.replaceState(null,'','#'+id)}catch(e){}}
    window.scrollTo(0,0);
  }
  document.addEventListener('click',function(e){
    var a=e.target.closest('[data-tab]'); if(!a) return;
    e.preventDefault(); show(a.dataset.tab);
  });
  show((location.hash||'#home').slice(1),false);
  window.addEventListener('hashchange',function(){show(location.hash.slice(1),false)});

  /* 3D tilt on cards */
  [].forEach.call(document.querySelectorAll('.tilt, .glow'),function(c){
    c.addEventListener('mousemove',function(e){
      var r=c.getBoundingClientRect();
      var x=(e.clientX-r.left)/r.width-.5, y=(e.clientY-r.top)/r.height-.5;
      c.style.transform='perspective(900px) rotateX('+(-y*6)+'deg) rotateY('+(x*8)+'deg) translateY(-2px)';
    });
    c.addEventListener('mouseleave',function(){c.style.transform='';});
  });

  /* Formspree forms */
  [].forEach.call(document.querySelectorAll('form[data-fs]'),function(f){
    f.addEventListener('submit',function(e){
      e.preventDefault();
      var msg=f.querySelector('.fmsg'),btn=f.querySelector('button[type=submit]'),label=btn.textContent;
      msg.className='fmsg';msg.textContent='';btn.disabled=true;btn.textContent='Sending…';
      fetch(f.action,{method:'POST',body:new FormData(f),headers:{'Accept':'application/json'}})
        .then(function(r){ if(r.ok){f.reset();msg.className='fmsg ok';msg.textContent='Thank you! Your request has been sent. We will reply by email.';}
                           else{throw new Error('bad')}})
        .catch(function(){msg.className='fmsg err';msg.textContent='Sorry, that did not send. Please try again or email '+document.body.dataset.email+'.';})
        .then(function(){btn.disabled=false;btn.textContent=label});
    });
  });
})();
</script>
</body>
</html>
