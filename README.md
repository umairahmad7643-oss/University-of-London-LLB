<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>UoL LLB Guide</title>
<meta name="description" content="Exam guidance, important topics, notes and answers for University of London LLB students (Levels 4, 5 and 6).">
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Hanken+Grotesk:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
:root{--paper:#f4eee1;--card:#fffdf7;--ink:#1d1c24;--muted:#6a6455;--line:#ddd1b9;--ox:#7a1d2c;--ox2:#5c1421;--gold:#b88a2b;--navy:#17202e;--green:#2f6b4f;--blue:#285a8f;--red:#a3323b;--r:14px}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:64px}
body{margin:0;background:var(--paper);color:var(--ink);font:16px/1.65 'Hanken Grotesk',system-ui,sans-serif;-webkit-font-smoothing:antialiased;
 background-image:radial-gradient(circle at 12% -10%,rgba(184,138,43,.14),transparent 40%),radial-gradient(circle at 100% 0,rgba(122,29,44,.08),transparent 38%)}
h1,h2,h3,h4{font-family:'Fraunces',Georgia,serif;line-height:1.2;margin:0}
a{color:var(--ox)}
/* ---------- slim sticky nav ---------- */
.nav{position:sticky;top:0;z-index:50;height:52px;background:var(--navy);color:#fff;display:flex;align-items:center;gap:14px;padding:0 14px;border-bottom:2px solid var(--gold);box-shadow:0 2px 12px rgba(0,0,0,.18)}
.brand{font-family:'Fraunces',Georgia,serif;font-weight:700;font-size:18px;white-space:nowrap;letter-spacing:.2px;color:#fff;text-decoration:none;display:flex;align-items:center;gap:8px}
.brand i{display:inline-grid;place-items:center;width:26px;height:26px;border-radius:7px;background:var(--gold);color:var(--navy);font-style:normal;font-size:14px;font-weight:800}
.links{display:flex;gap:2px;overflow-x:auto;scrollbar-width:none;flex:1;-webkit-overflow-scrolling:touch}
.links::-webkit-scrollbar{display:none}
.links a{color:#cdd3de;text-decoration:none;font-size:14px;font-weight:500;padding:6px 11px;border-radius:8px;white-space:nowrap}
.links a:hover{background:rgba(255,255,255,.09);color:#fff}
.links a.on{background:var(--gold);color:var(--navy);font-weight:700}
/* ---------- layout ---------- */
main{max-width:1040px;margin:0 auto;padding:30px 16px 60px}
.tab{display:none}.tab.on{display:block;animation:in .35s ease both}
@keyframes in{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
.eyebrow{font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--ox);font-weight:700;margin:0 0 8px}
.ph{margin:0 0 22px}.ph h2{font-size:clamp(28px,5vw,40px)}.ph p{color:var(--muted);margin:8px 0 0;max-width:62ch}
.card{background:var(--card);border:1px solid var(--line);border-radius:var(--r);padding:22px;box-shadow:0 1px 0 rgba(0,0,0,.03)}
.muted{color:var(--muted)}.fine{color:var(--muted);font-size:14px;margin:6px 4px 0}
/* ---------- hero ---------- */
.hero{background:linear-gradient(135deg,var(--navy),#26334a 60%,var(--ox2));color:#fff;border-radius:22px;padding:clamp(26px,5vw,52px);position:relative;overflow:hidden}
.hero:after{content:'\00a7';position:absolute;right:-10px;top:-60px;font:700 340px/1 'Fraunces',serif;color:rgba(255,255,255,.05);pointer-events:none}
.hero h1{font-size:clamp(32px,6vw,54px);max-width:16ch}
.hero p{max-width:58ch;color:#d6dbe6;font-size:18px;margin:14px 0 0}
.hero .stmt{display:inline-block;margin-top:20px;background:rgba(184,138,43,.2);border:1px solid var(--gold);color:#f5e3b3;padding:9px 16px;border-radius:999px;font-weight:600;font-size:15px}
.cta{display:flex;flex-wrap:wrap;gap:10px;margin-top:22px}
.btn{display:inline-block;border:0;cursor:pointer;background:var(--ox);color:#fff;font:700 15px 'Hanken Grotesk',sans-serif;padding:12px 22px;border-radius:10px;text-decoration:none;transition:.2s}
.btn:hover{background:var(--ox2);transform:translateY(-1px)}
.btn.alt{background:transparent;border:1.5px solid rgba(255,255,255,.55)}.btn.alt:hover{background:rgba(255,255,255,.12)}
.grid3{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:22px}
.feat h3{font-size:19px;margin:6px 0}.feat p{margin:0;color:var(--muted);font-size:15px}
.feat .n{font:700 13px 'Hanken Grotesk';color:var(--gold);letter-spacing:.1em}
.glance{margin-top:22px}.glance h3{font-size:20px;margin-bottom:10px}
/* ---------- accordions ---------- */
details>summary{list-style:none;cursor:pointer}details>summary::-webkit-details-marker{display:none}
details.level{margin:0 0 16px}
details.level>summary{display:flex;flex-wrap:wrap;gap:4px 14px;align-items:baseline;justify-content:space-between;background:linear-gradient(120deg,var(--navy),var(--ox2));color:#fff;padding:18px 22px;border-radius:var(--r);position:relative;padding-right:56px}
details.level>summary:after,details.acc>summary:after{content:'';position:absolute;right:20px;top:50%;width:9px;height:9px;border:solid currentColor;border-width:0 2.5px 2.5px 0;transform:translateY(-70%) rotate(45deg);transition:.25s}
details[open]>summary:after{transform:translateY(-30%) rotate(-135deg)}
.lv-t{font:700 24px 'Fraunces',serif}.lv-p{color:#f0d9a0;font-weight:600;font-size:14px}
.lv-body{padding:12px 0 0;display:grid;gap:10px}
details.acc{background:var(--card);border:1px solid var(--line);border-radius:12px;overflow:hidden}
details.acc>summary{display:flex;align-items:center;gap:10px;flex-wrap:wrap;padding:15px 48px 15px 18px;position:relative}
details.acc>summary:hover{background:#faf5e9}
.acc-n{font:600 18px 'Fraunces',serif}
.acc-b{padding:4px 20px 20px;border-top:1px dashed var(--line)}
.acc-b h4{font:700 12px 'Hanken Grotesk';letter-spacing:.12em;text-transform:uppercase;color:var(--ox);margin:16px 0 6px}
.acc-b p{margin:6px 0}.acc-b ul{margin:6px 0;padding-left:20px}.acc-b li{margin:3px 0}
.note{background:#fbf1d6;border-left:3px solid var(--gold);padding:8px 12px;border-radius:6px;font-size:14px}
.pill{font:700 12px 'Hanken Grotesk';padding:3px 10px;border-radius:999px}
.pill.code{background:#ece3cd;color:#4b3f1d}.pill.req{background:#dcefe4;color:var(--green)}.pill.opt{background:#e6e9f1;color:#41506d}
.lvh{font-size:22px;margin:26px 0 10px;padding-bottom:6px;border-bottom:2px solid var(--gold)}
.lvh:first-of-type{margin-top:0}
.acc-b.notes h4{font:600 17px 'Fraunces',serif;letter-spacing:0;text-transform:none;color:var(--ink);margin:18px 0 4px}
.acc-b.notes p,.acc-b.notes li{font-size:15.5px}
.endnote{margin-top:20px;background:var(--navy);color:#e6e9f1;padding:14px 16px;border-radius:10px;font-size:15px}
.endnote a{color:#f0d9a0;font-weight:700}
/* reading */
.tip{background:#fbf1d6;border:1px solid var(--gold);border-radius:var(--r);padding:16px 18px;margin-bottom:18px}
.tip b{color:var(--ox)}
.flag{display:inline-block;font:800 12px 'Hanken Grotesk';letter-spacing:.1em;padding:5px 12px;border-radius:6px;margin:14px 0 2px}
.flag.must{background:#f7dcdc;color:var(--red)}.flag.extra{background:#fbefc4;color:#8a6a0a;margin-top:22px}
.reading h4{margin-top:18px}
.ref{display:flex;gap:12px;padding:10px 0;border-bottom:1px solid #eee5d0}
.ref:last-child{border-bottom:0}
.refn{flex:none;width:26px;height:26px;border-radius:50%;background:var(--ox);color:#fff;font:700 12px/26px 'Hanken Grotesk';text-align:center}
.rt{font-weight:700}.stars{color:var(--gold);font-size:13px;font-weight:700}
.ref p{margin:4px 0;color:#403c33;font-size:15px}.ref ul{margin:4px 0;padding-left:20px;columns:2;column-gap:28px;font-size:15px}
.shortlist{margin-top:16px;background:#e9efe9;border-left:4px solid var(--green);padding:10px 14px;border-radius:6px;font-size:15px}
/* exam guidance */
.two{display:grid;grid-template-columns:repeat(auto-fit,minmax(310px,1fr));gap:16px;align-items:start}
.step{border-left:4px solid var(--green);background:#f1f6f2;padding:10px 14px;border-radius:0 8px 8px 0;margin:10px 0}
.step.key{background:#e2f0e7;border-color:var(--ox)}.step b{display:block}
.bad{color:var(--red)}.good{color:var(--green)}
.box{border-radius:10px;padding:14px 16px;margin-top:14px}.box.blue{background:#e8eef7}.box.red{background:#f8e6e6}
.box h4{font-size:17px;margin-bottom:6px}.box ul{margin:4px 0;padding-left:20px}
.q{background:#f2ecf7;border-radius:10px;padding:12px 14px;margin:9px 0}.q b{color:#4f2d6b}.q span{display:block;font-size:14.5px;color:#3d3646}
/* pricing */
.banner{background:linear-gradient(120deg,var(--ox),var(--ox2));color:#fff;border-radius:var(--r);padding:20px;text-align:center;font:600 clamp(18px,3vw,24px) 'Fraunces',serif;margin-bottom:26px}
.sec{margin:34px 0 14px;font-size:26px}
.p3{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:14px}
.p3 div{background:#f5efdf;border-radius:10px;padding:10px;text-align:center}.p3 span{display:block;font-size:13px;color:var(--muted)}.p3 b{font:700 clamp(15px,2.4vw,21px) 'Fraunces',serif}
.tier{background:var(--card);border:1px solid var(--line);border-radius:var(--r);margin-bottom:16px;overflow:hidden}
.tier-h{display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap;align-items:center;padding:16px 20px;color:#fff}
.tier-h h3{font-size:21px}.tier-h p{margin:2px 0 0;opacity:.9;font-size:14.5px}
.t-green .tier-h{background:var(--green)}.t-blue .tier-h{background:var(--blue)}.t-red .tier-h{background:var(--red)}
.tier-b{padding:16px 20px 20px}.ticks{list-style:none;padding:0;margin:0}.ticks li{padding:3px 0 3px 26px;position:relative}.ticks li:before{content:'\2713';position:absolute;left:0;color:var(--green);font-weight:800}
.pos{text-align:center;margin:12px 0 0;font:italic 600 17px 'Fraunces',serif;color:var(--muted)}
.badge{background:var(--gold);color:var(--navy);font:800 11px 'Hanken Grotesk';letter-spacing:.08em;padding:5px 11px;border-radius:999px}
.bundles{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:14px}
.bundle{background:var(--card);border:1px solid var(--line);border-top:4px solid var(--navy);border-radius:var(--r);padding:18px}
.bundle.hl{border-top-color:var(--gold);box-shadow:0 0 0 3px #f1e1b6}
.bundle h3{font-size:19px;margin-bottom:10px;display:flex;justify-content:space-between;gap:8px;align-items:center}
.brow{display:flex;justify-content:space-between;background:#f5efdf;padding:8px 12px;border-radius:8px;margin-top:6px}
.addons{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:14px}
.addons .card h3{font-size:18px}.addons .card b{display:block;font:700 26px 'Fraunces',serif;color:var(--ox);margin-top:4px}
.rules{background:#f8e6e6;border:1px solid #e3b9b9;border-radius:var(--r);padding:16px 20px;margin-top:20px}
.rules ul{margin:6px 0 0;padding-left:20px}
.check-intro{background:linear-gradient(120deg,#e8eef7,#f2ecf7);border:1px solid #cfd6e6;border-radius:var(--r);padding:20px;margin-bottom:16px}
.check-intro h3{font-size:22px}
.speed{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px;margin-top:14px}
.speed div{background:#fff;border-radius:10px;padding:12px 14px;border:1px solid #d8def0}.speed b{display:block;font:700 18px 'Fraunces',serif}.speed span{color:var(--muted);font-size:14.5px}
/* forms */
.forms{display:grid;grid-template-columns:repeat(auto-fit,minmax(310px,1fr));gap:16px;align-items:start;margin-top:14px}
.form h3{font-size:21px;margin-bottom:6px}.form .muted{margin:0 0 12px;font-size:15px}
label.f{display:block;margin-top:12px}label.f>span,.turn .lbl{display:block;font-weight:700;font-size:14px;margin-bottom:4px}
input[type=text],input[type=email],select,textarea{width:100%;font:16px 'Hanken Grotesk',sans-serif;padding:11px 13px;border:1.5px solid var(--line);border-radius:10px;background:#fff;color:var(--ink)}
input:focus,select:focus,textarea:focus{outline:0;border-color:var(--ox);box-shadow:0 0 0 3px rgba(122,29,44,.15)}
.form .btn{width:100%;margin-top:18px}
.checks{margin-top:12px;display:grid;gap:6px;font-size:14.5px}.checks input{margin-right:6px}
.turn{margin-top:14px;display:grid;gap:8px}.turn .lbl{margin:0}
.opt{display:flex;align-items:center;gap:10px;border:1.5px solid var(--line);border-radius:10px;padding:10px 12px;cursor:pointer;background:#fff}
.opt:has(input:checked){border-color:var(--ox);background:#fbeff1}.opt b{display:block}.opt span{font-size:14px;color:var(--muted)}
.fmsg{margin:12px 0 0;font-weight:600;min-height:1.2em}.fmsg.ok{color:var(--green)}.fmsg.err{color:var(--red)}
/* about */
.about p{font-size:17px}.contact{background:#e9efe9;border:1px solid #bfd3c6;border-radius:12px;padding:16px 18px;margin-top:18px}
.mission{background:#f5efdf;border-radius:12px;padding:16px 18px;margin-top:18px}
.mission h3{font-size:19px;margin-bottom:6px}
.soon{text-align:center;padding:50px 20px}.soon h3{font-size:30px;margin-bottom:8px}
footer{background:var(--navy);color:#cdd3de;text-align:center;padding:30px 16px;font-size:14.5px;border-top:2px solid var(--gold)}
footer b{font:700 20px 'Fraunces',serif;color:#fff;display:block;margin-bottom:4px}footer a{color:#f0d9a0}
@media(max-width:620px){.brand span{display:none}.ref ul{columns:1}.nav{padding:0 8px;gap:8px}.p3{gap:6px}}

</style>
</head>
<body data-email="umairahmad7643@gmail.com">

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
  <div class="hero">
    <p class="eyebrow" style="color:#f0d9a0">University of London LLB &middot; Levels 4, 5 &amp; 6</p>
    <h1>Study smarter for your LLB exams</h1>
    <p>Important topics, paper patterns, answer structures and techniques for every level, so you don&rsquo;t have to face the same problems and uncertainties others have.</p>
    <div class="stmt">&#10003; Get structured, exam-ready answers for UoL papers</div>
    <div class="cta"><a class="btn" href="#modules" data-tab="modules">Browse modules</a><a class="btn alt" href="#samples" data-tab="samples">Read free sample notes</a></div>
  </div>
  <div class="grid3">
    <div class="card feat"><span class="n">01</span><h3>Every module covered</h3><p>Exam patterns and the topics that matter for all Level 4, 5 and 6 modules.</p></div>
    <div class="card feat"><span class="n">02</span><h3>Exam technique</h3><p>IRAC, ILAC and MIRAT for problem questions; what &ldquo;discuss&rdquo; and &ldquo;critically evaluate&rdquo; really ask for.</p></div>
    <div class="card feat"><span class="n">03</span><h3>Notes, answers &amp; checking</h3><p>Affordable notes, model answers, and marking for single questions or a full past paper.</p></div>
  </div>
  <div class="card glance">
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
<details class="level" ><summary><span class="lv-t">Level 5 (Year 2)</span><span class="lv-p">Full module notes · PKR 2,500 per module</span></summary><div class="lv-body">
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
<details class="level" ><summary><span class="lv-t">Level 6 (Final Year)</span><span class="lv-p">Full module notes · PKR 3,000 per module</span></summary><div class="lv-body">
<details class="acc"><summary><span class="pill code">LA 3005</span><span class="acc-n">Jurisprudence</span><span class="pill req">Required</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory | Part B: Attempt three questions from a choice of nine questions.</p>
<h4>Important topics</h4><ul><li>Part A (compulsory): Naturalism, Liberalism, Ronald Dworkin’s Theory</li><li>Part B (any three questions): Command Theory (John Austin), Marxism (Karl Marx), Pure Theory (Kelsen), Feminism, Distributive Theory (John Rawls)</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3011</span><span class="acc-n">Alternative Dispute Resolution</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Compulsory | Part B: Attempt two problem questions from a choice of three | Part C: Attempt one essay question from a choice of two.</p>
<h4>Important topics</h4><ul><li>Nature &amp; Purpose of ADR</li><li>Negotiation</li><li>Mediation (VERY IMPORTANT)</li><li>Arbitration (MOST IMPORTANT TOPIC)</li><li>Arbitration Law &amp; Principles</li><li>Confidentiality &amp; Without Prejudice Rule</li><li>ADR vs Litigation</li><li>Ethics in ADR</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3012</span><span class="acc-n">Company Law</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Part A: Essay – attempt one question from a choice of four | Part B: Problem – attempt one question from a choice of four. It is up to you whether to attempt more from either part.</p>
<h4>Important topics</h4><ul><li>Forms of Business Organisation</li><li>Separate Legal Personality</li><li>Lifting the Veil of Incorporation</li><li>Management of the Company</li><li>Director Duties</li><li>Enforcing Director Duties</li><li>Statutory Minority Protection</li></ul>
</div></details>
<details class="acc"><summary><span class="pill code">LA 3014</span><span class="acc-n">Conflict of Laws</span><span class="pill opt">Optional</span></summary><div class="acc-b">
<h4>Exam pattern</h4><p>Attempt three questions from a choice of six questions.</p>
<h4>Important topics</h4><ul><li>Domicile</li><li>Jurisdiction</li><li>Choice of Law – Tort</li><li>Choice of Law – Contract</li></ul>
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
<h4>Exam pattern</h4><p>Part A: Essay – attempt at least one | Part B: Problem – attempt at least one. You choose which part the last question comes from.</p>
<h4>Important topics</h4><ul><li>Essay: Primary Sources (Qur’an &amp; Sunnah), Secondary Sources (Qiyas &amp; Ijma), Istihsan, Istishab, Ijtihad (standalone essay), Usul al-Fiqh (methods of interpretation), Six Periods of Islamic History</li><li>Problem – Family Law: Capacity to Marry, Marriage Conditions and Requirements, Duties of Husband and Wife, Polygamy, Maintenance, Custody, Dower (mahr), Dissolution of Marriage</li><li>Problem – Penal Law: Types of Offences (Hudud, Ta’zir), Qisas and Diyat</li><li>Financial Law (prepare as a backup)</li><li>Core book: Q &amp; A’s</li></ul>
</div></details>
<p class="fine">Dissertation: no exam, coursework only.</p>
</div></details>
</section>

<!-- EXAM GUIDANCE -->
<section id="exam" class="tab">
  <div class="ph"><p class="eyebrow">Exam guidance</p><h2>Techniques that earn marks</h2><p>How to structure problem questions and what each essay instruction word expects.</p></div>
  <div class="two">
    <div class="card">
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
    <div class="card">
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
  <div class="card" style="border-left:6px solid var(--gold)">
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
<li><strong>Fisher v Bell [1961]</strong> — A flick knife displayed in a shop window was an invitation to treat, not an offer for sale.</li>
<li><strong>Pharmaceutical Society of Great Britain v Boots [1953]</strong> — Shelf displays were invitations to treat; the customer made the offer at the till, where the sale was accepted. This allows the pharmacist to supervise sales.</li>
<li><strong>Thornton v Shoe Lane Parking [1971]</strong> — A machine-operated car park made an offer; the customer accepted by entering/using the machine in the manner indicated. Also important for timing and incorporation of exclusion terms.</li>
<li><strong>Partridge v Crittenden [1968]</strong> — An ordinary advertisement offering birds for sale was an invitation to treat, not an offer to sell to everyone who responded.</li>
<li><strong>Grainger &amp; Son v Gough [1896]</strong> — A wine merchant’s catalogue/price list was an invitation to treat.</li>
<li><strong>Carlill v Carbolic Smoke Ball Co [1893]</strong> — An advertisement can be a unilateral offer where its wording shows a definite promise to anyone who performs specified conditions; the deposit of money supported intention to be bound. Acceptance occurred by performing the stated conditions; separate notification was not required in the circumstances.</li>
</ul>
<h4>Auctions</h4>
<ul>
<li><strong>Payne v Cave (1789)</strong> — A bid is an offer and may be withdrawn before the auctioneer accepts it by bringing down the hammer. An auction with reserve is generally an invitation to bid.</li>
<li><strong>Warlow v Harrison (1859)</strong> — An auction advertised without reserve may give rise to a collateral obligation to sell to the highest bona fide bidder; distinguish the collateral promise from the main sale contract.</li>
<li><strong>Barry v Davies [2000]</strong> — In a genuine auction without reserve, the auctioneer was liable in damages for refusing to sell to the highest bona fide bidder. Prefer this authority for the modern rule.</li>
</ul>
<h4>Tenders</h4>
<ul>
<li><strong>Spencer v Harding (1870)</strong> — An invitation to submit tenders did not, without more, promise to accept the highest or any tender.</li>
<li><strong>Harvela Investments Ltd v Royal Trust Co of Canada [1986]</strong> — A promise to accept the highest conforming bid was binding; a referential bid (a bid defined by reference to another bid) was not permitted under the invitation.</li>
<li><strong>Blackpool &amp; Fylde Aero Club Ltd v Blackpool Borough Council [1990]</strong> — An invitation to a limited group to submit tenders by a deadline implied a unilateral obligation to consider a conforming, timely tender. It did not promise acceptance of the tender.</li>
</ul>
<h4>Termination of an offer</h4>
<ul>
<li><strong>Ramsgate Victoria Hotel Co v Montefiore (1866)</strong> — An offer to take shares lapsed after an unreasonable delay; acceptance must occur within the stated or a reasonable time.</li>
<li><strong>Routledge v Grant (1828)</strong> — An offeror may revoke an offer before acceptance even if the offer stated it would remain open for a period, unless an option is supported by consideration or otherwise binding.</li>
<li><strong>Byrne v Van Tienhoven (1880)</strong> — Revocation is effective only when communicated to the offeree; posting a revocation is not enough.</li>
<li><strong>Dickinson v Dodds (1876)</strong> — An offeree who reliably learned that the offeror had sold the property to someone else knew the offer was no longer open; revocation need not always be communicated directly by the offeror.</li>
<li><strong>The Brimnes [1975]</strong> — A telex revocation received during ordinary office hours took effect when it could reasonably be read, not when the recipient actually read it.</li>
<li><strong>Errington v Errington and Woods [1952]</strong> — Once performance of a unilateral offer had begun, the offeror could not revoke it so as to prevent completion, provided the offeree continued to perform the required conditions.</li>
<li><strong>Hyde v Wrench (1840)</strong> — A counter-offer rejects and terminates the original offer.</li>
<li><strong>Stevenson, Jacques &amp; Co v McLean (1880)</strong> — A request for information is not a counteroffer and does not terminate the original offer.</li>
<li><strong>Harvey v Facey [1893]</strong> — A reply stating the lowest price was information, not an offer to sell.</li>
<li><strong>Harris v Nickerson (1873)</strong> — An announcement that an auction would be held was a statement of intention, not a contractual promise that every item would be auctioned.</li>
<li><strong>Bradbury v Morgan (1862)</strong> — A continuing guarantee was not automatically terminated by the guarantor’s death on the facts; do not generalise that every offer survives death. Death and revocation depend on the type of offer, knowledge, and circumstances.</li>
</ul>
<p>Problem-question checklist: Is there a definite offer? Is the statement only an invitation to treat? Was the offer still open? Was it revoked, rejected, counter-offered, or allowed to lapse?</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 1020</span><span class="acc-n">Public Law</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 1031</span><span class="acc-n">Legal System and Method</span></summary><div class="acc-b notes">
<h4>Legal System and Method — Revised Exam Notes</h4>
<p>University of London LLB | Exam-focused revision edition | Checked against the public UOLLB module overview</p>
<h4>Scope and use</h4>
<p>These notes revise the supplied text, correct legal inaccuracies, remove repetition and develop explanations that were too short. The public UOLLB overview identifies a broader module than the pasted material: common law, constitutional principles, justice, sources of law, legal research, case notes/reports, judicial reasoning, courts, precedent, statutory interpretation, judiciary, legal professionals, and civil/criminal processes. The main body below focuses on the topics developed in your pasted notes; a short supplementary checklist flags other areas to verify against your current University of London subject guide.</p>
<p><strong>Jurisdiction:</strong> the court structure discussed is principally that of England and Wales. The UK Supreme Court is a UK-wide institution for qualifying appeals, but the routes and limits differ between jurisdictions. Do not describe the English court system as identical throughout the United Kingdom.</p>
<p><strong>Exam method:</strong> for a problem question, identify the relevant court/rule, state the legal test accurately, apply it to the facts, and reach a reasoned conclusion. For an essay, explain the rule, use leading authorities, evaluate advantages and criticisms, and answer the precise wording of the question.</p>
<h4>Part I — Courts and institutions</h4>
<h4>1. Basic concepts</h4>
<h4>Civil and criminal proceedings</h4>
<p>Civil proceeding resolves disputes about legal rights and obligations, such as contract, tort, property, family matters and challenges to public decisions. The party bringing a claim is usually the claimant; the opposing party is the defendant. Remedies may include damages, injunctions, declarations or other orders.</p>
<p>Criminal proceeding determines whether the accused has committed an offence. The prosecution must prove guilt beyond reasonable doubt; the defendant is presumed innocent unless and until guilt is proved.</p>
<p>First-instance court hears a case initially and determines facts and law. An appellate court reviews a lower decision within the limits of its appellate jurisdiction. An appeal is not automatically a complete rehearing.</p>
<p><strong>Unanimous judgment:</strong> all judges agree on the result and reasoning. Concurring judgment: a judge agrees with the result but gives different or additional reasons. Dissenting judgment: a judge disagrees with the majority; it is not the binding decision, though it may later influence legal development.</p>
<h4>Why courts matter</h4>
<p>Courts resolve disputes authoritatively, interpret legislation, apply and develop common law, supervise the legality of public action, and protect procedural rights. They do not resolve every dispute: negotiation, mediation, arbitration, ombudsmen and tribunals may provide alternatives. Access to justice depends not only on formal rights but on whether people can realistically enforce them.</p>
<h4>2. Court structure in England and Wales</h4>
<p>The following is a simplified guide, not an exhaustive appeal chart. Appeal routes depend on the court, the judge, the type of decision and permission requirements.</p>
<h4>UK Supreme Court</h4>
<p>Established in 2009 under the Constitutional Reform Act 2005, the Supreme Court is the final domestic appellate court for qualifying cases.</p>
<p>Hears civil appeals from across the UK and criminal appeals from England, Wales and Northern Ireland; Scottish criminal appeals ordinarily remain within Scotland&#x27;s own system.</p>
<p>Usually considers cases involving a point of law of public importance, with permission required in the ordinary course.</p>
<p>Determines certain devolution issues and develops authoritative interpretations of law.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 1010</span><span class="acc-n">Criminal Law</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<h3 class="lvh">Level 5</h3>
<details class="acc"><summary><span class="pill code">LA 2003</span><span class="acc-n">Property Law</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 2001</span><span class="acc-n">Tort Law</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 2024</span><span class="acc-n">European Union Law</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 2029</span><span class="acc-n">International Protection of Human Rights</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 2017</span><span class="acc-n">Commercial Law</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 2008</span><span class="acc-n">Administrative Law</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<h3 class="lvh">Level 6</h3>
<details class="acc"><summary><span class="pill code">LA 3005</span><span class="acc-n">Jurisprudence</span><span class="pill req">Required</span></summary><div class="acc-b notes">
<h4>Exam method</h4>
<p><strong>For an essay:</strong> define the theory; explain its central concepts; develop the strongest argument; evaluate it using named rival thinkers; apply it to the question; and conclude with a reasoned judgment. Avoid simply listing features.</p>
<h4>Legal Positivism: John Austin</h4>
<h4>Central claim</h4>
<p>Legal positivism distinguishes what the law is from whether the law is morally good. A rule may be legally valid because it comes from a recognised legal source even if it is unjust. This separation thesis does not mean positivists consider morality unimportant.</p>
<p><strong>Austin wrote:</strong> “The existence of law is one thing; its merit or demerit is another.” The point is that identifying a law and morally evaluating it are separate questions.</p>
<h4>Austin’s command theory</h4>
<p>Austin defines positive law, in outline, as a command issued by a political superior to political inferiors and backed by a sanction.</p>
<ul>
<li><strong>Command:</strong> an expression of a superior’s wish that another act or refrain from acting, accompanied by the prospect of an adverse consequence for disobedience.</li>
<li><strong>Duty:</strong> the obligation imposed by the command.</li>
<li><strong>Sanction:</strong> threatened harm or punishment, such as a fine or imprisonment.</li>
<li><strong>Sovereign:</strong> a determinate human superior whom the bulk of society habitually obeys and who does not habitually obey another human superior.</li>
</ul>
<p>Austin’s analytical approach aims to identify the structure of positive law, not to determine whether each law is just.</p>
<h4>What counts as law?</h4>
<ul>
<li><strong>Positive law properly so called:</strong> commands laid down by a political superior, including statutes and rules made under sovereign authority.</li>
<li><strong>Divine law:</strong> commands attributed to God, treated separately from human positive law.</li>
<li><strong>Positive morality:</strong> rules such as international law, social conventions and customs not adopted or sanctioned by the sovereign. They are not positive law properly so called in Austin’s strict account.</li>
<li><strong>Custom:</strong> may become positive law when recognised or adopted by the sovereign. Do not say that Austin necessarily excludes every custom in all circumstances.</li>
<li><strong>International law:</strong> Austin classifies it as positive morality because it lacks a determinate political sovereign of the kind his theory requires. Avoid the overbroad statement that every treaty can never be law in any legal system.</li>
</ul>
<h4>Difficulties for the command model</h4>
<p>Repealing laws remove existing rules; declaratory laws clarify law; and power-conferring rules enable people to make contracts, wills or companies. These rules do not naturally look like threats backed by punishment. Austin may try to explain them through sanctions or sovereign commands, but the account becomes strained.</p>
<h4>Criticisms of Austin</h4>
<ul>
<li><strong>Sovereign problem:</strong> modern states divide authority among legislatures, courts and executives. Constitutions may limit legislatures, making a single unlimited sovereign difficult to identify.</li>
<li><strong>Habitual obedience:</strong> a new law can be valid immediately, and a legal system can survive a change of ruler. Habitual obedience to a person does not adequately explain legal succession.</li>
<li><strong>Sanctions are not the whole of law:</strong> power-conferring rules enable legal acts rather than simply threaten punishment.</li>
<li><strong>Legal limits on government:</strong> constitutional and administrative rules constrain public authorities. Austin struggles to explain legal limits on the supposed ultimate sovereign.</li>
<li><strong>International law and custom:</strong> these are treated as law in modern practice despite lacking Austin’s centralised sovereign and sanction structure.</li>
<li><strong>Judicial development:</strong> courts interpret statutes and develop common law; law cannot always be reduced to a prior command.</li>
<li><strong>Legal obligation:</strong> people often treat rules as standards that justify criticism, not merely as predictions of punishment.</li>
</ul>
<h4>Hart’s refinement</h4>
<p>H.L.A. Hart argues that law is a system of rules, not merely orders backed by threats.</p>
<ul>
<li>Primary rules impose duties and regulate conduct.</li>
<li>Secondary rules govern how legal rules are identified, changed and applied:</li>
<li><strong>Rule of recognition:</strong> criteria used by officials to identify valid law.</li>
<li><strong>Rules of change:</strong> procedures for creating, amending and repealing law.</li>
<li><strong>Rules of adjudication:</strong> procedures and powers for deciding whether rules have been breached.</li>
<li><strong>Internal point of view:</strong> officials treat rules as standards guiding and justifying conduct, not merely as predictions of sanctions.</li>
</ul>
<p><strong>Evaluation:</strong> Austin’s theory promotes clarity and separates legal validity from moral merit. Hart provides a stronger account of constitutional systems, power-conferring rules, legal continuity and legal institutions.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3011</span><span class="acc-n">Alternative Dispute Resolution</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3014</span><span class="acc-n">Conflict of Laws</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3007</span><span class="acc-n">Evidence</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3013</span><span class="acc-n">Public International Law</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3026</span><span class="acc-n">Intellectual Property Law</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3019</span><span class="acc-n">Introduction to Islamic Law</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<h4>How to use these notes</h4>
<p>These notes revise the topics present in the supplied material. They are not a guarantee of complete syllabus coverage: the public UOLLB page describes Introduction to Islamic Law broadly as covering legal sources and jurisprudence, contract law, family law and modern applications of penal law, but it does not provide a full examinable syllabus or confirm that every topic below is required. Check these notes against your current University of London subject guide, lectures and past papers.</p>
<h4>For an exam answer:</h4>
<ul>
<li>Define the relevant concept accurately.</li>
<li>State the general rule and its conditions.</li>
<li>Explain important differences between schools of law and between classical doctrine and modern legislation.</li>
<li>Apply the rule to the facts in a problem question.</li>
<li>For an essay, evaluate the rule with a supported argument rather than merely listing advantages and criticisms.</li>
</ul>
<p><strong>Terminology:</strong> Use mahr (dower), not “dowry”, for the financial obligation owed by the husband to the wife. In South Asian usage, “dowry” often means property supplied by the bride or her family; that is a different concept.</p>
<h4>1. Sources and methodology of Islamic law</h4>
<h4>1.1 Shariah and fiqh</h4>
<ul>
<li>Shariah refers to the divinely ordained path or normative guidance of Islam.</li>
<li>Fiqh is the human juristic understanding and interpretation of that guidance. It is therefore capable of disagreement, development and error.</li>
<li>The distinction helps explain why jurists and schools can disagree even though they recognise the same foundational revelation.</li>
</ul>
<p>Avoid saying that Shariah is “inaccessible” or that all Islamic law is simply fiqh. The distinction is conceptual; how a particular rule is classified and applied depends on its source and interpretation.</p>
<h4>1.2 Usul al-fiqh</h4>
<p>Usul al-fiqh is the methodology used to identify, interpret and derive legal rules from recognised sources. It considers the authority of evidence, language and context, reconciliation of texts, and the permissible use of juristic reasoning.</p>
<h4>A useful exam distinction:</h4>
<ul>
<li>Sources/evidence are the materials from which a rule is derived.</li>
<li>Usul al-fiqh explains how jurists’ reason from those materials.</li>
<li>Fiqh is the resulting body of legal doctrine.</li>
</ul>
<p>Do not treat the Qur&#x27;an as simply a statute, the Sunnah as simply case law, or usul as exactly equivalent to common-law interpretation. Such comparisons can help beginners but are imperfect analogies.</p>
<h4>1.3 Principal sources</h4>
<ul>
<li><strong>Qur&#x27;an</strong> — the primary source of revelation and legal guidance.</li>
<li><strong>Sunnah</strong> — the Prophet&#x27;s normative example, known principally through reports of his words, actions and approvals (hadith).</li>
<li><strong>Ijma</strong> — juristic consensus; its scope and requirements are defined differently by legal theorists.</li>
<li><strong>Qiyas</strong> — analogical reasoning, accepted as a source by the principal Sunni schools, though not in the same way by every school or jurist.</li>
</ul>
<p>Other methods include istihsan (juristic preference, especially associated with Hanafi jurisprudence), maslahah (consideration of public interest, particularly associated with Maliki jurisprudence), istishab (presumption of continuity) and &#x27;urf (recognised custom).</p>
<p>Their status and scope vary between schools. Do not present every method as universally accepted on identical terms.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3012</span><span class="acc-n">Company Law</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<h4>Forms of business organisation</h4>
<ul>
<li><strong>Sole trader:</strong> one individual owns and runs the business; there is no separate legal entity and the owner is personally liable for business debts.</li>
<li><strong>Partnership:</strong> under s 1 Partnership Act 1890, the relationship between persons carrying on business in common with a view of profit. Partners are generally personally liable for partnership obligations.</li>
<li><strong>Company:</strong> an incorporated legal person separate from its members. A company may be private or public, and limited or unlimited. Limited companies may be limited by shares or by guarantee.</li>
</ul>
<p><strong>Exam point:</strong> compare separate personality, liability, management, continuity, and ability to raise capital. Do not say every company is limited or that a shareholder owns company assets.</p>
<h4>Separate legal personality and limited liability</h4>
<h4>Core rule</h4>
<p>Once incorporated, a company is a legal person distinct from its shareholders. It owns its property, enters contracts, and incurs its own liabilities. Limited liability is a related but distinct principle: a member of a company limited by shares is generally liable only for any unpaid amount on their shares, not for company debts merely because they are a shareholder.</p>
<h4>Essential cases</h4>
<ul>
<li><strong>Salomon v A Salomon &amp; Co Ltd [1897] AC 22</strong> — Salomon incorporated his boot-making business and held nearly all the shares. The House of Lords held that the properly incorporated company was legally separate from him, despite his control. Principle: courts respect separate personality where incorporation requirements are satisfied.</li>
<li><strong>Macaura v Northern Assurance Co Ltd [1925] AC 619</strong> — a shareholder who had transferred timber to a company tried to claim under an insurance policy in his own name. He had no insurable interest in the company’s timber. Principle: company assets belong to the company, not its shareholders.</li>
<li><strong>Lee v Lee’s Air Farming Ltd [1961] AC 12</strong> — Lee controlled the company and also worked for it as a pilot. He could still be an employee of the separate company. Principle: control and employment by the company can coexist.</li>
</ul>
<h4>Limited liability: exam analysis</h4>
<p>Advantages include encouraging investment, entrepreneurship, and portfolio diversification.</p>
<p>The counterpoint is that some insolvency risk is borne by creditors, particularly involuntary or poorly informed creditors. Separate personality and limited liability are not identical: the former identifies the company as a separate person; the latter limits members’ exposure.</p>
<h4>Corporate veil and personal liability</h4>
<h4>General rule</h4>
<p>Courts do not pierce the corporate veil merely because a company is controlled by one person, belongs to a corporate group, or because imposing personal liability appears fair. First identify a recognised statutory basis, an existing personal obligation, agency/trust principles, or another ordinary legal route. True veil piercing is narrow.</p>
<h4>Essential cases</h4>
<ul>
<li><strong>Adams v Cape Industries plc [1990] Ch 433</strong> — the Court of Appeal rejected a general power to disregard a corporate group simply because justice or economic reality seemed to require it. Principle: group ownership alone does not justify veil piercing.</li>
<li><strong>Gilford Motor Co Ltd v Horne [1933] Ch 935</strong> — a former employee subject to a non-solicitation covenant used a company to solicit the employer’s customers. The company was used to evade an existing obligation. Principle: a company interposed to evade a pre-existing legal duty may be restrained.</li>
<li><strong>Jones v Lipman [1962] 1 WLR 832</strong> — a seller transferred land to a company he controlled to avoid specific performance of an earlier sale contract. The court ordered specific performance. Principle: a company cannot be used as a mask to evade an existing obligation.</li>
<li><strong>VTB Capital plc v Nutritek International Corp [2013] UKSC 5</strong> — the Supreme Court refused to extend veil piercing so that a controller could be treated as a party to a company’s contract. Principle: veil piercing does not provide a broad route to impose contractual liability on a controller.</li>
<li><strong>Prest v Petrodel Resources Ltd [2013] UKSC 34</strong> — the Supreme Court emphasised the narrow evasion principle: piercing may be available where a person already subject to an obligation deliberately interposes a company to frustrate its enforcement. The case itself was resolved through beneficial ownership/trust principles, not veil piercing.</li>
</ul>
<h4>Statutory insolvency routes</h4>
<ul>
<li><strong>Insolvency Act 1986, s 213</strong> — fraudulent trading: in a winding up, if business was carried on with intent to defraud creditors or for a fraudulent purpose, the court may order persons knowingly party to it to contribute to the company’s assets. Actual dishonesty is central.</li>
<li><strong>Insolvency Act 1986, s 214</strong> — wrongful trading: where a director knew or ought to have concluded that there was no reasonable prospect of avoiding insolvent liquidation or administration, and failed to take every step to minimise potential loss to creditors, the court may order a contribution. Fraudulent intent is not required.</li>
<li><strong>Insolvency Act 1986, s 216:</strong> restricts certain re-use of a name associated with an insolvent company. This is a separate statutory control, not a general veil-piercing rule.</li>
</ul>
<p><strong>Exam warning:</strong> do not describe s 213 and s 214 as the same offence. Section 213 concerns fraudulent trading; s 214 concerns wrongful trading and the director’s failure to minimise creditor loss.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3015</span><span class="acc-n">Equity and Trusts</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<h4>Exam method</h4>
<p>For a problem question, identify the issue, state the rule, use the leading case, apply the facts and reach a conclusion. For a case, learn (1) material facts, (2) decision, (3) legal principle. Do not memorise long facts that do not explain the rule.</p>
<h4>1. Introduction: equity and trusts</h4>
<h4>Equity</h4>
<p>Equity developed through the Court of Chancery to mitigate the rigidity of common law and provide remedies or rights where common-law rules were inadequate. The Judicature Acts 1873–75 fused the administration of law and equity in the courts; they did not erase the substantive distinction between legal and equitable rights. Equity is now administered by the High Court, including the Chancery Division.</p>
<h4>Conflict between common law and equity</h4>
<p>Earl of Oxford’s Case (1615): where common law and equity directly conflict, equity prevails. Equity generally supplements common law and presupposes its existence; it is not simply free-floating fairness.</p>
<p><strong>Maitland:</strong> equity is dependent on common law—without common law, equity would be “a castle in the air”. Use this quotation only if relevant to an essay about equity’s relationship with common law.</p>
<h4>Equity is principled, not arbitrary</h4>
<p>Equitable doctrines are constrained by precedent and legal principles. Lord Eldon’s warning against equity varying with the “length of the Chancellor’s foot” expresses the need for consistency rather than personal discretion.</p>
<h4>What is a trust?</h4>
<p>A trust separates legal title from beneficial ownership. The trustee holds legal title to property and must deal with it for beneficiaries or a legally permitted purpose. Beneficiaries generally have equitable rights enforceable against the trustee.</p>
<h4>Trusts may be useful to:</h4>
<ul>
<li>manage property for children or people unable to manage it themselves;</li>
<li>manage pension or investment assets collectively;</li>
<li>provide different people with successive or discretionary benefits;</li>
<li>hold property for charitable purposes.</li>
</ul>
<p>Do not present tax avoidance or creditor protection as automatic benefits. Trusts must comply with applicable law; transfers intended to defeat creditors or evade tax may be challenged.</p>
<h4>Trusts arising by operation of law</h4>
<p>A constructive trust may be imposed by law, for example where a fiduciary makes an unauthorised profit. It is not necessarily based on an express intention to create a trust.</p>
<p>FHR European Ventures LLP v Cedar Capital Partners LLC [2014] UKSC 45: an agent received a secret commission from a hotel seller while acting for the buyer. The commission was held on constructive trust for the principal. The case is a leading authority that a bribe or secret commission received by a fiduciary is held on trust for the principal.</p>
<h4>Legal and equitable ownership</h4>
<p>DKLR Holding Co (No 2) Pty Ltd v Commissioner of Stamp Duties (NSW) (1982): a transfer of legal title and the creation of an equitable interest are not necessarily two separate transfers of pre-existing interests. An equitable interest is not always a slice carved out of the legal estate; it may arise when the trust is created. Use the case to explain the relationship between legal title and equitable ownership, but check the precise tax context if the question concerns stamp duty.</p>
<p>Trustees are not ordinarily agents of beneficiaries. A trustee contracting in their capacity as trustee may incur personal contractual liability; beneficiaries do not automatically become parties to the contract merely because they benefit from it.</p>
<h4>Types of trust</h4>
<ul>
<li><strong>Express trust:</strong> deliberately created by a settlor.</li>
<li><strong>Fixed trust:</strong> each beneficiary’s entitlement is fixed.</li>
<li><strong>Discretionary trust:</strong> trustees choose which eligible beneficiaries receive distributions and/or the amount, within the trust terms.</li>
<li><strong>Bare trust:</strong> trustee holds property for an absolutely entitled beneficiary and generally has little active discretion.</li>
<li><strong>Resulting trust:</strong> beneficial ownership returns to the settlor or transferor, or their estate, where the law presumes or requires that result.</li>
<li><strong>Constructive trust:</strong> arises by operation of law in recognised circumstances.</li>
<li><strong>Inter vivos trust:</strong> created during the settlor’s lifetime.</li>
<li><strong>Testamentary trust:</strong> created under a will and taking effect on death.</li>
<li><strong>Charitable trust:</strong> created for legally recognised charitable purposes and public benefit.</li>
<li><strong>Private purpose trust:</strong> trust for a non-charitable purpose; generally invalid unless it falls within narrow exceptions.</li>
</ul>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
<details class="acc"><summary><span class="pill code">LA 3014</span><span class="acc-n">Criminology</span><span class="pill opt">Optional</span></summary><div class="acc-b notes">
<p class="muted">The free sample page for this module is being prepared.</p>
<div class="endnote"><strong>That is only a part of the notes.</strong> To access the full notes, please head to the <a href="#modules" data-tab="modules">Modules</a> tab in the navigation bar, or order them from the <a href="#purchase" data-tab="purchase">Purchase</a> tab.</div></div></details>
</section>

<!-- FURTHER READING -->
<section id="reading" class="tab">
  <div class="ph"><p class="eyebrow">Level 6</p><h2>Further reading</h2><p>Extra reading beyond the module guide, including articles worth reading for higher marks.</p></div>
  <div class="tip"><b>Tip:</b> Read to the extent that you can remember and quote in an exam realistically. Don&rsquo;t try to read more than you can understand and remember.</div>
  <details class="acc"><summary><span class="acc-n">Company Law</span></summary><div class="acc-b reading"><div class="flag must">MUST READ</div><h4>Corporate personality</h4><div class="ref"><span class="refn">1</span><div><div class="rt">Hansmann &amp; Kraakman — The Essential Role of Organizational Law</div></div></div><h4>Veil piercing</h4><div class="ref"><span class="refn">2</span><div><div class="rt">Watkins &amp; Nsubuga — The Road to Prest</div></div></div><div class="ref"><span class="refn">3</span><div><div class="rt">Mujih — Piercing the Corporate Veil as a Remedy of Last Resort after Prest</div></div></div><h4>s.213 / s.214</h4><div class="ref"><span class="refn">4</span><div><div class="rt">Keay — Fraudulent Trading: The Intent to Defraud Element</div></div></div><div class="ref"><span class="refn">5</span><div><div class="rt">Cooke &amp; Hicks — Wrongful Trading – Predicting Insolvency</div></div></div><h4>Directors</h4><div class="ref"><span class="refn">6</span><div><div class="rt">Keay — Good Faith and Directors&#x27; Duty to Promote the Success of Their Company</div></div></div><div class="ref"><span class="refn">7</span><div><div class="rt">Keay — The Duty of Directors to Take Account of Creditors&#x27; Interests</div></div></div><h4>Minority shareholders</h4><div class="ref"><span class="refn">8</span><div><div class="rt">McVea — Section 994 of the Companies Act 2006 and the Primacy of Contract</div></div></div><div class="ref"><span class="refn">9</span><div><div class="rt">Keay — Assessing and Rethinking the Statutory Scheme for Derivative Actions</div></div></div><div class="flag extra">READ IF YOU HAVE EXTRA TIME</div><div class="ref"><span class="refn">10</span><div><div class="rt">Leebron — Limited Liability, Tort Victims and Creditors</div></div></div><div class="ref"><span class="refn">11</span><div><div class="rt">Watson — The Corporate Legal Person</div></div></div><div class="ref"><span class="refn">12</span><div><div class="rt">Prentice — The Theory of the Firm: Minority Shareholder Oppression</div></div></div></div></details>
<details class="acc"><summary><span class="acc-n">Jurisprudence</span></summary><div class="acc-b reading"><div class="flag must">MUST READ</div><h4>Dworkin</h4><div class="ref"><div><div class="rt">Legal Interpretivism — Stanford Encyclopedia of Philosophy (SEP)</div></div></div><div class="ref"><div><div class="rt">Hart, “Policies, Principles, and Adjudication”</div></div></div><h4>Mill</h4><div class="ref"><div><div class="rt">Mill&#x27;s Moral and Political Philosophy — SEP</div></div></div><div class="ref"><div><div class="rt">Selected sections of On Liberty</div></div></div><h4>Berlin</h4><div class="ref"><div><div class="rt">“Two Concepts of Liberty”</div></div></div><h4>Rawls</h4><div class="ref"><div><div class="rt">John Rawls — SEP</div></div></div><div class="ref"><div><div class="rt">Original Position — SEP</div></div></div><h4>Marxism</h4><div class="ref"><div><div class="rt">Belliotti, “Marxist Jurisprudence: Historical Necessity and Radical Contingency”</div></div></div><h4>Bentham</h4><div class="ref"><div><div class="rt">Perreau-Saussine, “Bentham and the Boot-Strappers of Jurisprudence”</div></div></div><h4>Austin</h4><div class="ref"><div><div class="rt">John Austin — SEP</div></div></div><div class="ref"><div><div class="rt">Selected passages from The Province of Jurisprudence Determined</div></div></div></div></details>
<details class="acc"><summary><span class="acc-n">Islamic Law</span></summary><div class="acc-b reading"><h4>Core reading</h4><div class="ref"><span class="refn">1</span><div><div class="rt">M.A. Baderin — Islamic Law: A Very Short Introduction (2021)</div><p>Read particularly for:</p><ul><li>Shariah vs fiqh</li><li>Historical development</li><li>Sources</li><li>Islamic law in modern states</li><li>Relationship between Islamic and international law</li><li>Contemporary reform</li></ul></div></div><div class="ref"><span class="refn">2</span><div><div class="rt">M.H. Kamali — Principles of Islamic Jurisprudence</div><p>This is your technical / usul al-fiqh book. Focus on:</p><ul><li>Qur&#x27;an</li><li>Sunnah</li><li>Ijma&#x27;</li><li>Qiyas</li><li>Ijtihad</li><li>Istihsan</li><li>Maslahah</li><li>Darurah</li><li>Istishab</li></ul></div></div><div class="ref"><span class="refn">3</span><div><div class="rt">N.J. Coulson — A History of Islamic Law</div><div class="stars">Priority: ★★★★</div><p>Excellent for questions concerning:</p><ul><li>Development of Islamic law</li><li>Early schools</li><li>Sunni legal schools</li><li>Authority of jurists</li><li>Historical development</li><li>Codification and modernisation</li></ul></div></div><h4>Further academic reading</h4><div class="ref"><div><div class="rt">Wael B. Hallaq — Shari&#x27;a: Theory, Practice, Transformations</div><p>Useful for: Shariah → fiqh → juristic authority → colonialism → modern state. Also available through the UoL Online Library resources.</p></div></div><div class="ref"><div><div class="rt">Peters — Crime and Punishment in Islamic Law</div><p>Particularly useful for:</p><ul><li>Hudud</li><li>Qisas</li><li>Ta&#x27;zir</li><li>Islamic criminal justice</li><li>Contemporary application</li></ul></div></div></div></details>
<details class="acc"><summary><span class="acc-n">Equity and Trusts</span></summary><div class="acc-b reading"><h4>Core</h4><div class="ref"><span class="refn">1</span><div><div class="rt">J.E. Penner — The Law of Trusts (12th ed, 2022)</div><div class="stars">Priority: ★★★★★</div><p>This should be your principal textbook. Use it for:</p><ul><li>Express trusts</li><li>Constitution</li><li>Certainty</li><li>Trustees</li><li>Breach</li><li>Remedies</li><li>Tracing</li><li>Constructive trusts</li></ul></div></div><div class="ref"><span class="refn">2</span><div><div class="rt">Graham Virgo — The Principles of Equity and Trusts (6th ed, 2026)</div><div class="stars">Priority: ★★★★★</div><p>Particularly valuable for critical analysis. UoL currently lists both Penner and Virgo as essential reading. Virgo is excellent when you need to answer “Why does equity take this approach?” rather than merely “What is the rule?”</p></div></div><h4>Further reading</h4><div class="ref"><div><div class="rt">Andrew Burrows — The Law of Restitution</div><p>Very useful for:</p><ul><li>Unjust enrichment</li><li>Constructive trusts</li><li>Restitutionary remedies</li><li>Proprietary remedies</li></ul></div></div><div class="ref"><div><div class="rt">A. Hudson — Equity and Trusts</div><p>Good alternative explanation when Penner/Virgo becomes dense. UoL’s recent acquisitions include Hudson’s text.</p></div></div><div class="ref"><div><div class="rt">Y.K. Liew — Rationalising Constructive Trusts</div><p>More advanced but excellent for constructive trusts, especially essay/problem questions involving:</p><ul><li>Fiduciaries</li><li>Bribes</li><li>Wrongful enrichment</li><li>Institutional vs remedial constructive trusts</li></ul></div></div><div class="shortlist"><strong>Shortlist:</strong> Penner → Virgo → targeted article/book chapter on the specific controversy. Don’t attempt to read five Equity textbooks.</div></div></details>
<details class="acc"><summary><span class="acc-n">Alternative Dispute Resolution</span></summary><div class="acc-b reading"><h4>Core</h4><div class="ref"><div><div class="rt">Roberts &amp; Palmer — Dispute Processes: ADR and the Primary Forms of Decision-Making</div><div class="stars">Priority: ★★★★★</div><p>This should be your principal academic book. Focus on:</p><ul><li>Negotiation</li><li>Mediation</li><li>Adjudication</li><li>Arbitration</li><li>Decision-making</li><li>Ethical issues</li><li>Relationship between ADR and courts</li></ul></div></div><h4>Articles I&#x27;d actually read</h4><div class="ref"><div><div class="rt">Cappelletti — “Alternative Dispute Resolution Processes within the Framework of the World-Wide Access-to-Justice Movement”</div><p>Read for ADR and access to justice. UoL specifically identifies this as essential reading.</p></div></div><div class="ref"><div><div class="rt">Sander &amp; Rozdeiczer — “Matching Cases and Dispute Resolution Procedures: Detailed Analysis Leading to a Mediation-Centred Approach”</div><p>Read for: which dispute-resolution mechanism should be used for which dispute? Directly identified in UoL’s reading guide.</p></div></div><div class="ref"><div><div class="rt">Gulliver — “Negotiations as a Mode of Dispute Settlement: Towards a General Model”</div><p>Read for negotiation theory.</p></div></div><div class="ref"><div><div class="rt">Spencer &amp; Brogan — Mediation Law and Practice</div><p>Focus on:</p><ul><li>Theory/philosophy of mediation</li><li>Mediator role</li><li>Ethics</li><li>Mediation procedure</li></ul></div></div><h4>Arbitration</h4><div class="ref"><div><div class="rt">Redfern &amp; Hunter — International Arbitration</div><p>UoL&#x27;s ADR reading guide specifically points students toward it. Focus on:</p><ul><li>Arbitration agreements</li><li>Arbitral tribunals</li><li>Procedure</li><li>Challenges to awards</li></ul></div></div><div class="shortlist"><strong>Shortlist:</strong> 1. Roberts &amp; Palmer  2. Cappelletti  3. Sander &amp; Rozdeiczer  4. One mediation article  5. Redfern &amp; Hunter chapters relevant to arbitration. That’s enough.</div></div></details>
<details class="acc"><summary><span class="acc-n">Conflict of Laws</span></summary><div class="acc-b reading"><h4>Core</h4><div class="ref"><span class="refn">1</span><div><div class="rt">David McClean — Morris: The Conflict of Laws (11th ed, 2025)</div><p>This is UoL’s current essential reading.</p></div></div><h4>Second textbook</h4><div class="ref"><span class="refn">2</span><div><div class="rt">Adrian Briggs — The Conflict of Laws</div><p>Particularly good for understanding the conceptual structure of private international law. The UoL Online Library has a recent acquisition of Briggs.</p></div></div><h4>Another useful source</h4><div class="ref"><div><div class="rt">P. Rogerson — Collier’s Conflict of Laws</div></div></div><h4>Areas where I’d specifically do further reading</h4><p class="muted">Don’t randomly read articles. Target:</p><div class="ref"><div><div class="rt">Jurisdiction</div><ul><li>Forum non conveniens</li><li>Brussels regime / post-Brexit jurisdiction</li><li>Access to justice</li></ul></div></div><div class="ref"><div><div class="rt">Choice of law</div><ul><li>Contractual choice of law</li><li>Rome I</li><li>Rome II</li><li>Closest connection</li></ul></div></div><div class="ref"><div><div class="rt">Foreign judgments</div><ul><li>Recognition</li><li>Enforcement</li><li>Public policy</li></ul></div></div><div class="ref"><div><div class="rt">Theoretical</div><ul><li>Territoriality</li><li>Comity</li><li>Party autonomy</li><li>Certainty vs flexibility</li></ul></div></div><div class="shortlist"><strong>Shortlist:</strong> McClean → Briggs → targeted academic commentary on the topic in your past paper.</div></div></details>
<details class="acc"><summary><span class="acc-n">Intellectual Property Law</span></summary><div class="acc-b reading"><h4>Core</h4><div class="ref"><span class="refn">1</span><div><div class="rt">Bently, Sherman, Gangjee &amp; Johnson — Intellectual Property Law (6th ed)</div><p>This would be my primary choice.</p></div></div><div class="ref"><span class="refn">2</span><div><div class="rt">Cornish, Llewelyn &amp; Aplin — Intellectual Property: Patents, Copyright, Trade Marks and Allied Rights (10th ed)</div><p>Particularly useful for deeper doctrinal analysis.</p></div></div><h4>Shorter conceptual reading</h4><div class="ref"><div><div class="rt">Siva Vaidhyanathan — Intellectual Property: A Very Short Introduction</div><p>Excellent if you want to understand the policy justification behind IP rather than memorise rules. Part of UoL’s Very Short Introductions collection.</p></div></div><h4>Particularly useful academic area</h4><div class="ref"><div><div class="rt">Justifications for intellectual property</div><p>Focus your further reading here. This gives you material for critical paragraphs instead of simply explaining infringement tests.</p><ul><li>Incentive theory</li><li>Labour theory</li><li>Personality theory</li><li>Public interest</li><li>Access to information</li><li>Monopoly concerns</li><li>Innovation</li><li>Balance between creators and users</li></ul></div></div><h4>Bonus</h4><div class="ref"><div><div class="rt">Bellido (ed.) — Landmark Cases in Intellectual Property Law</div><p>UoL’s library has this available. Useful for quickly understanding the significance of major cases.</p></div></div><div class="shortlist"><strong>Shortlist:</strong> Bently et al. → Cornish → Vaidhyanathan → one targeted article on the policy issue in your question.</div></div></details>
<details class="acc"><summary><span class="acc-n">Evidence</span></summary><div class="acc-b reading"><h4>Core</h4><div class="ref"><span class="refn">1</span><div><div class="rt">A. Choo — Evidence (7th ed, 2026)</div><p>This is currently UoL’s essential text. Use it as your main book.</p></div></div><h4>Second source</h4><div class="ref"><div><div class="rt">Roberts &amp; Zuckerman — Criminal Evidence</div><p>More analytical and particularly useful when dealing with:</p><ul><li>Criminal evidence</li><li>Admissibility</li><li>Reliability</li><li>Fairness</li><li>Exclusion</li><li>Jury decision-making</li></ul></div></div><div class="ref"><div><div class="rt">Colin Taylor — Evidence</div><p>Also worth using as a supplementary explanation; UoL’s recent acquisitions include Taylor’s text.</p></div></div><h4>Areas I’d do further reading on</h4><div class="ref"><div><div class="rt">1. Hearsay</div><p>Read academic criticism concerning:</p><ul><li>Reliability</li><li>Exceptions</li><li>Fairness</li><li>Jury evaluation</li></ul></div></div><div class="ref"><div><div class="rt">2. Expert evidence</div><p>Very important academically. Look at:</p><ul><li>Reliability of expert testimony</li><li>Scientific evidence</li><li>Judicial gatekeeping</li><li>Risk of wrongful conviction</li></ul></div></div><div class="ref"><div><div class="rt">3. Confessions</div><p>Focus on:</p><ul><li>Reliability</li><li>Police interrogation</li><li>Oppression</li><li>Improperly obtained evidence</li></ul></div></div><div class="ref"><div><div class="rt">4. Character evidence</div><p>Look for the tension between probative value vs unfair prejudice.</p></div></div><div class="shortlist"><strong>Shortlist:</strong> Choo → Roberts &amp; Zuckerman → one academic article per major controversial topic.</div></div></details>
<details class="acc"><summary><span class="acc-n">Public International Law</span></summary><div class="acc-b reading"><h4>Core</h4><div class="ref"><span class="refn">1</span><div><div class="rt">Mansell &amp; Openshaw — International Law: A Critical Introduction</div><p>One of UoL’s current essential texts. The word “critical” matters: it gives you material for evaluation rather than merely rules.</p></div></div><div class="ref"><span class="refn">2</span><div><div class="rt">Wallace &amp; Martin-Ortega — International Law</div><p>UoL also lists this as essential.</p></div></div><h4>Third book</h4><div class="ref"><div><div class="rt">Malcolm Shaw — International Law</div><p>A much larger reference work. Do NOT read it cover-to-cover. Use it when you need additional authority on a particular topic. UoL’s Online Library has a recent edition.</p></div></div><h4>The really valuable PIL academic reading</h4><div class="ref"><div><div class="rt">A. Is international law actually “law”?</div><p>Extremely useful for theoretical questions. Look at H.L.A. Hart and Louis Henkin — How Nations Behave. The question is essentially: is international law genuinely binding despite the absence of a central sovereign?</p></div></div><div class="ref"><div><div class="rt">B. Third World Approaches to International Law</div><div class="stars">Priority: ★★★★★</div><p>Antony Anghie — Imperialism, Sovereignty and the Making of International Law (priority for critical essays). A major critical perspective on:</p><ul><li>Colonialism</li><li>Sovereignty</li><li>International institutions</li><li>Development</li><li>Historical construction of international law</li></ul></div></div><div class="ref"><div><div class="rt">C. Feminist approaches</div><p>Hilary Charlesworth — The Boundaries of International Law: A Feminist Analysis. Useful if a question touches:</p><ul><li>Gender</li><li>Human rights</li><li>International institutions</li><li>Structural inequality</li><li>Theoretical approaches to international law</li></ul></div></div><div class="ref"><div><div class="rt">D. Critical approaches</div><p>B.S. Chimni / TWAIL literature. Very useful for questions involving sovereignty + colonialism + international institutions + developing states.</p></div></div></div></details>
</section>

<!-- PURCHASE -->
<section id="purchase" class="tab">
  <div class="ph"><p class="eyebrow">Purchase</p><h2>Notes, answers &amp; checking</h2></div>
  <div class="banner">&#10003; Get structured, exam-ready answers for UoL papers</div>

  <h2 class="sec" style="margin-top:0">&#128218; Module notes</h2>
  <div class="card" style="margin-bottom:16px"><h3 style="font-size:20px">Full module notes</h3><p class="muted" style="margin:6px 0 0">The complete notes for a module, per module.</p>
    <div class="p3"><div><span>Level 4</span><b>PKR 2,000</b></div><div><span>Level 5</span><b>PKR 2,500</b></div><div><span>Level 6</span><b>PKR 3,000</b></div></div></div>
  <div class="tier t-green"><div class="tier-h"><div><h3>🟢 Tier 1: Basic (Entry Level)</h3><p>For students who just want cheap help to pass</p></div></div><div class="tier-b"><ul class="ticks"><li>Concise exam-focused notes</li><li>Key topics only (no deep explanations)</li><li>Bullet-point summaries</li></ul><div class="p3 "><div><span>Level 4</span><b>PKR 1,500</b></div><div><span>Level 5</span><b>PKR 2,500</b></div><div><span>Level 6</span><b>PKR 3,500</b></div></div></div></div>

  <h2 class="sec">&#10067; Paid answers</h2>
  <div class="tier t-green"><div class="tier-h"><div><h3>🟢 Tier 1: Basic Answer</h3><p>For students who just want something to submit/pass</p></div></div><div class="tier-b"><ul class="ticks"><li>Direct answer</li><li>Basic structure</li><li>Minimal case law</li><li>600–900 words</li></ul><div class="p3 "><div><span>Level 4</span><b>PKR 500</b></div><div><span>Level 5</span><b>PKR 700</b></div><div><span>Level 6</span><b>PKR 1,000</b></div></div><p class="pos">“Simple Pass Answer”</p></div></div><div class="tier t-blue"><div class="tier-h"><div><h3>🔵 Tier 2: Standard Answer</h3><p>Our main offering</p></div><span class="badge">BEST SELLER</span></div><div class="tier-b"><ul class="ticks"><li>Proper IRAC / essay structure</li><li>Relevant case law</li><li>Clear arguments + application</li><li>900–1,500 words</li></ul><div class="p3 "><div><span>Level 4</span><b>PKR 1,000</b></div><div><span>Level 5</span><b>PKR 1,500</b></div><div><span>Level 6</span><b>PKR 2,000</b></div></div><p class="pos">“Exam-Ready Answer”</p></div></div><div class="tier t-red"><div class="tier-h"><div><h3>🔴 Tier 3: Premium Answer</h3><p>For serious students aiming for higher marks</p></div><span class="badge">HIGH VALUE</span></div><div class="tier-b"><ul class="ticks"><li>Everything in Standard</li><li>Strong case law integration</li><li>Critical analysis + evaluation</li><li>Polished structure (first-class style)</li><li>1,500–2,500 words</li></ul><div class="p3 "><div><span>Level 4</span><b>PKR 1,500</b></div><div><span>Level 5</span><b>PKR 2,500</b></div><div><span>Level 6</span><b>PKR 3,500</b></div></div><p class="pos">“High-Scoring Model Answer”</p></div></div>

  <h2 class="sec">&#128230; Bundle pricing</h2>
  <div class="bundles"><div class="bundle "><h3>4 Answers Pack</h3><div class="brow"><span>Level 4</span><b>PKR 2,500</b></div><div class="brow"><span>Level 5</span><b>PKR 4,000</b></div><div class="brow"><span>Level 6</span><b>PKR 6,000</b></div></div><div class="bundle hl"><h3>6 Answers Pack<span class="badge">BEST VALUE</span></h3><div class="brow"><span>Level 4</span><b>PKR 4,000</b></div><div class="brow"><span>Level 5</span><b>PKR 6,500</b></div><div class="brow"><span>Level 6</span><b>PKR 10,000</b></div></div><div class="bundle "><h3>10 Answers Pack</h3><div class="brow"><span>Level 4</span><b>PKR 7,500</b></div><div class="brow"><span>Level 5</span><b>PKR 12,000</b></div><div class="brow"><span>Level 6</span><b>PKR 18,000</b></div></div></div>

  <h2 class="sec">&#128184; Add-ons</h2>
  <div class="addons"><div class="card"><h3>&#9889; Urgent delivery (12&ndash;24 hrs)</h3><b>PKR 500 &ndash; 1,000</b></div><div class="card"><h3>&#9997;&#65039; Extra length / deep analysis</h3><b>PKR 500 &ndash; 1,500</b></div></div>
  <div class="rules"><b>&#9888;&#65039; Important rules</b><ul><li>Each tier has a word limit.</li><li>Standard delivery time is 24&ndash;48 hours.</li><li>An extra charge applies for urgent work.</li></ul></div>

  <h2 class="sec">&#9989; Get your answers checked</h2>
  <div class="check-intro"><h3>Two ways to get marked</h3>
    <p class="muted" style="margin:6px 0 0">Check a single question, or submit an entire past paper. For a full paper, choose how quickly you need it back.</p>
    <div class="speed"><div><b>&#9889; Fast track</b><span>Full paper marked within 1 day</span></div><div><b>&#128337; Regular</b><span>Full paper marked within 3 days</span></div><div><b>&#127919; Individual questions</b><span>Available for Levels 4, 5 and 6 below</span></div></div>
    <p class="fine" style="margin-top:12px">Fees for full-paper checking are confirmed by email after you submit.</p></div>
  <div class="forms"><form class="card form" data-fs action="https://formspree.io/f/xgodbanw" method="POST"><h3>Get a full past paper checked</h3><p class="muted">Attempted an entire past paper? Submit all your answers and get them marked with feedback. Choose how fast you need it back.</p><input type="hidden" name="service" value="Full past paper checking"><input type="hidden" name="_subject" value="New full-paper checking request"><label class="f"><span>Your name</span><input type="text" name="name" placeholder="Full name" required></label><label class="f"><span>Email address</span><input type="email" name="email" placeholder="you@example.com" required></label><label class="f"><span>Level</span><select name="level" required><option value="">Select…</option><option value="Level 4">Level 4</option><option value="Level 5">Level 5</option><option value="Level 6">Level 6</option></select></label><label class="f"><span>Module</span><input type="text" name="module" placeholder="e.g. Tort Law (LA 2001)" required></label><label class="f"><span>Paper (year / session)</span><input type="text" name="paper" placeholder="e.g. 2024 exam paper" required></label><div class="turn"><span class="lbl">Turnaround</span><label class="opt"><input type="radio" name="turnaround" value="Fast track – marked within 1 day" required><span><b>Fast track</b>Marked within 1 day</span></label><label class="opt"><input type="radio" name="turnaround" value="Regular – marked within 3 days"><span><b>Regular</b>Marked within 3 days</span></label></div><label class="f"><span>Your answers</span><textarea name="answers" rows="9" placeholder="Paste all your answers here, or paste a link to a shared document (Google Drive, OneDrive…) with edit/comment access off." required></textarea></label><label class="f"><span>Notes for the marker</span><textarea name="additional_info" rows="3" placeholder="Target grade, areas you are worried about, etc. (optional)" ></textarea></label><button class="btn" type="submit">Submit paper for checking</button><p class="fmsg" role="status"></p></form><form class="card form" data-fs action="https://formspree.io/f/xgodbanw" method="POST"><h3>Individual questions — submit up to 10</h3><p class="muted">Send a past-paper question (or up to 10 of them) for a written answer. Pick a tier, or a bundle for 4, 6 or 10 answers.</p><input type="hidden" name="service" value="Individual question(s)"><input type="hidden" name="_subject" value="New question submission"><label class="f"><span>Your name</span><input type="text" name="name" placeholder="Full name" required></label><label class="f"><span>Email address</span><input type="email" name="email" placeholder="you@example.com" required></label><label class="f"><span>Level</span><select name="level" required><option value="">Select…</option><option value="Level 4">Level 4</option><option value="Level 5">Level 5</option><option value="Level 6">Level 6</option></select></label><label class="f"><span>Answer tier</span><select name="answer_tier" required><option value="">Select…</option><option value="Basic">Tier 1 – Basic (Simple Pass Answer)</option><option value="Standard">Tier 2 – Standard (Exam-Ready Answer) – BEST SELLER</option><option value="Premium">Tier 3 – Premium (High-Scoring Model Answer)</option></select></label><label class="f"><span>Single question or bundle</span><select name="bundle_type" required><option value="">Select…</option><option value="Single question">Single question</option><option value="4 answers pack">4 Answers Pack</option><option value="6 answers pack">6 Answers Pack (best value)</option><option value="10 answers pack">10 Answers Pack</option></select></label><label class="f"><span>Module name(s)</span><input type="text" name="modules" placeholder="e.g. Contract Law, Tort Law" required></label><label class="f"><span>Your question(s)</span><textarea name="questions" rows="9" placeholder="Paste your question(s). If sending several, number them 1, 2, 3 … (maximum 10 per submission)." required></textarea></label><div class="checks"><label><input type="checkbox" name="urgent_delivery" value="yes"> Urgent delivery (12–24 hrs) – PKR 500–1,000</label><label><input type="checkbox" name="extra_analysis" value="yes"> Extra length / deep analysis – PKR 500–1,500</label></div><label class="f"><span>Additional instructions</span><textarea name="additional_instructions" rows="3" placeholder="Optional" ></textarea></label><button class="btn" type="submit">Submit question(s)</button><p class="fmsg" role="status"></p></form></div>

  <h2 class="sec">&#128221; Order notes</h2>
  <div class="forms"><form class="card form" data-fs action="https://formspree.io/f/mqenoeov" method="POST"><h3>Order notes</h3><p class="muted">Tell us which module you need and we will reply by email.</p><input type="hidden" name="_subject" value="New notes order"><label class="f"><span>Your name</span><input type="text" name="name" placeholder="Full name" required></label><label class="f"><span>Email address</span><input type="email" name="email" placeholder="you@example.com" required></label><label class="f"><span>Level</span><select name="level" required><option value="">Select…</option><option value="Level 4">Level 4</option><option value="Level 5">Level 5</option><option value="Level 6">Level 6</option></select></label><label class="f"><span>Notes tier</span><select name="notes_tier" required><option value="">Select…</option><option value="Full module notes">Full module notes (L4 PKR 2,000 / L5 PKR 2,500 / L6 PKR 3,000)</option><option value="Tier 1 Basic notes">Tier 1: Basic notes (L4 PKR 1,500 / L5 PKR 2,500 / L6 PKR 3,500)</option></select></label><label class="f"><span>Module name</span><input type="text" name="module" placeholder="e.g. Contract Law (LA 1040)" required></label><label class="f"><span>Anything else?</span><textarea name="additional_info" rows="3" placeholder="Special requests (optional)" ></textarea></label><button class="btn" type="submit">Submit notes order</button><p class="fmsg" role="status"></p></form></div>
</section>

<!-- LAW-GAT -->
<section id="lawgat" class="tab">
  <div class="ph"><p class="eyebrow">LAW-GAT</p><h2>LAW-GAT</h2></div>
  <div class="card soon"><h3>Coming soon</h3><p class="muted">This section is being prepared. Questions? Email <a href="mailto:umairahmad7643@gmail.com">umairahmad7643@gmail.com</a>.</p></div>
</section>

<!-- ABOUT -->
<section id="about" class="tab">
  <div class="ph"><p class="eyebrow">About</p><h2>About the founder</h2></div>
  <div class="card about">
    <p style="margin-top:0">This platform was created by a University of London LLB graduate who understands the challenges of this demanding programme. Having experienced the difficulties first-hand, the founder is committed to helping students who have just enrolled, or are already enrolled, achieve their academic goals.</p>
    <div class="mission"><h3>Mission</h3><p style="margin:0;font-size:16px">To guide University of London LLB students so they don&rsquo;t have to face the same problems and uncertainties. By sharing structured exam guidance, important topics and affordable study materials, this platform aims to help students at every level approach their examinations with confidence.</p></div>
    <div class="contact"><b>&#128222; Contact</b><br><a href="mailto:umairahmad7643@gmail.com">umairahmad7643@gmail.com</a><p class="muted" style="font-size:15px;margin:6px 0 0">For the Francis Ng articles (Tort Law, Equity and Trusts), email the address above.</p></div>
  </div>
</section>

<!-- COMPLAINTS -->
<section id="complaints" class="tab">
  <div class="ph"><p class="eyebrow">Feedback</p><h2>Submit a complaint</h2><p>Found an error or inaccuracy in any module information on this website? Please tell us so we can fix it.</p></div>
  <div class="forms" style="grid-template-columns:minmax(0,640px)"><form class="card form" data-fs action="https://formspree.io/f/mwvyjvdn" method="POST"><h3>Report an error</h3><input type="hidden" name="_subject" value="Website error report"><label class="f"><span>Your name</span><input type="text" name="name" placeholder="Your name" required></label><label class="f"><span>Email address</span><input type="email" name="email" placeholder="you@example.com" required></label><label class="f"><span>Module / section</span><input type="text" name="module" placeholder="Which module or section has an error?" required></label><label class="f"><span>Description of the error</span><textarea name="complaint" rows="6" placeholder="Please describe the error or issue in detail…" required></textarea></label><button class="btn" type="submit">Submit complaint</button><p class="fmsg" role="status"></p></form></div>
</section>

</main>

<footer><b>UoL LLB Guide</b>Helping University of London LLB students prepare with confidence.<br><a href="mailto:umairahmad7643@gmail.com">umairahmad7643@gmail.com</a><br>&copy; 2026 UoL LLB Guide</footer>

<script>
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

  // Formspree forms: submit in place and show a message
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
