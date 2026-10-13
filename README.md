<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Suruchi Seva Foundation | Clean India, Caring Hearts</title>
<meta name="description" content="Suruchi Seva Foundation works for a cleaner, healthier and more compassionate India through community service.">
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 10 10'><circle cx='5' cy='5' r='5' fill='%23E8891D'/></svg>">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600&family=Figtree:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --saffron:#E8891D;
  --saffron-deep:#C96F0E;
  --green:#2E7D4F;
  --green-deep:#1F5C39;
  --cream:#FBF8F2;
  --sand:#F1EBDD;
  --ink:#1C2620;
  --muted:#5F6A62;
  --line:#E4DDCC;
  --radius:14px;
  --serif:'Fraunces', Georgia, 'Times New Roman', serif;
  --sans:'Figtree', system-ui, -apple-system, 'Segoe UI', sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;scroll-padding-top:90px}
body{font-family:var(--sans);color:var(--ink);background:var(--cream);line-height:1.6;font-size:16px;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
img,svg{display:block;max-width:100%}
a{color:inherit}
:focus-visible{outline:3px solid var(--saffron);outline-offset:3px;border-radius:6px}
.wrap{width:min(1180px,92%);margin-inline:auto}
.serif{font-family:var(--serif)}

/* Header */
header{position:sticky;top:0;z-index:50;background:rgba(251,248,242,.94);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
.bar{display:flex;align-items:center;justify-content:space-between;gap:20px;height:72px}
.brand{display:flex;align-items:center;gap:10px;text-decoration:none;font-family:var(--serif);font-weight:600;font-size:1.05rem;line-height:1.15}
.brand small{display:block;font-family:var(--sans);font-weight:500;font-size:.72rem;color:var(--muted);letter-spacing:.02em}
nav ul{display:flex;gap:26px;list-style:none;font-weight:500;font-size:.95rem}
nav a{text-decoration:none;color:var(--ink);padding:6px 0;border-bottom:2px solid transparent}
nav a:hover{border-color:var(--saffron)}
.head-cta{display:flex;align-items:center;gap:14px}
.phone{font-weight:600;font-size:.92rem;text-decoration:none;white-space:nowrap}
.btn{display:inline-flex;align-items:center;gap:8px;padding:13px 24px;border-radius:999px;font-weight:600;font-size:.95rem;text-decoration:none;border:2px solid transparent;cursor:pointer;font-family:inherit;transition:background .2s,color .2s}
.btn-saffron{background:var(--saffron);color:#fff}
.btn-saffron:hover{background:var(--saffron-deep)}
.btn-ink{background:var(--ink);color:#fff}
.btn-ink:hover{background:#000}
.btn-line{background:transparent;color:var(--ink);border-color:var(--ink)}
.btn-line:hover{background:var(--ink);color:#fff}
.menu-btn{display:none;background:none;border:0;font-size:1.6rem;cursor:pointer;color:var(--ink)}

/* Hero */
.hero{position:relative;overflow:hidden;padding:88px 0 96px}
.hero-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:48px;align-items:center}
.hero h1{font-family:var(--serif);font-weight:600;font-size:clamp(2.6rem,5.4vw,4.4rem);line-height:1.04;letter-spacing:-.02em;margin-bottom:24px}
.hero p.lead{font-size:1.08rem;color:var(--muted);max-width:480px;margin-bottom:34px}
.hero-actions{display:flex;flex-wrap:wrap;gap:14px}
.hero-art{position:relative;aspect-ratio:1/1;max-width:520px;width:100%;justify-self:end}
.blob{position:absolute;border-radius:50%;overflow:hidden}
.blob.big{inset:0;background:radial-gradient(circle at 30% 30%,#F6C27A 0%,var(--saffron) 45%,var(--green) 100%)}
.blob.big::after{content:"";position:absolute;inset:0;background:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='20' height='20'%3E%3Ccircle cx='2' cy='2' r='1.4' fill='%23ffffff' fill-opacity='.22'/%3E%3C/svg%3E")}
.blob.small{width:34%;aspect-ratio:1/1;background:var(--green);border:6px solid var(--cream);left:-4%;bottom:6%}
.blob.tiny{width:24%;aspect-ratio:1/1;background:var(--sand);border:6px solid var(--cream);right:-2%;top:4%}
.dot{position:absolute;width:12px;height:12px;border-radius:50%;background:var(--saffron)}
.stat-chip{position:absolute;right:-8px;bottom:12%;background:#fff;border-radius:var(--radius);padding:16px 20px;box-shadow:0 12px 30px rgba(28,38,32,.12);min-width:190px}
.stat-chip strong{display:block;font-family:var(--serif);font-size:1.9rem;color:var(--green-deep);line-height:1.1}
.stat-chip span{font-size:.85rem;color:var(--muted)}

/* Sections */
section{padding:96px 0}
.head{text-align:center;max-width:620px;margin:0 auto 56px}
.head h2{font-family:var(--serif);font-weight:600;font-size:clamp(2rem,3.6vw,2.8rem);line-height:1.12;letter-spacing:-.015em;margin-bottom:14px}
.head p{color:var(--muted)}
.kicker{display:inline-block;color:var(--saffron-deep);font-weight:600;font-size:.9rem;margin-bottom:10px}

/* Pillars */
.pillars{display:grid;grid-template-columns:repeat(4,1fr);gap:22px}
.pillar{background:#fff;border:1px solid var(--line);border-radius:var(--radius);padding:34px 26px;text-align:center}
.pillar .ico{width:64px;height:64px;margin:0 auto 20px;border-radius:50%;background:var(--sand);display:grid;place-items:center}
.pillar h3{font-family:var(--serif);font-weight:600;font-size:1.25rem;margin-bottom:10px}
.pillar p{font-size:.92rem;color:var(--muted)}

/* About */
.about{background:var(--sand)}
.about-grid{display:grid;grid-template-columns:1fr 1fr;gap:72px;align-items:center}
.about-art{position:relative;height:460px}
.about-art .main{position:absolute;left:0;top:40px;width:72%;aspect-ratio:1/1;border-radius:50%;background:radial-gradient(circle at 40% 35%,#8FBF9F,var(--green-deep));display:grid;place-items:center;color:#fff;font-family:var(--serif);font-size:1.4rem;text-align:center;padding:30px}
.about-art .side{position:absolute;right:0;top:0;width:36%;aspect-ratio:1/1;border-radius:50%;background:var(--saffron);border:6px solid var(--sand)}
.about-art .side2{position:absolute;right:8%;bottom:0;width:26%;aspect-ratio:1/1;border-radius:50%;background:#F6C27A;border:6px solid var(--sand)}
.about h2{font-family:var(--serif);font-weight:600;font-size:clamp(2rem,3.4vw,2.7rem);line-height:1.15;margin-bottom:20px}
.about .promise{font-weight:600;margin-bottom:14px}
.about p{color:var(--muted);margin-bottom:14px}
.about .btns{display:flex;gap:14px;flex-wrap:wrap;margin-top:24px}
.checks{list-style:none;margin:18px 0 0;display:grid;gap:10px}
.checks li{padding-left:28px;position:relative;font-size:.97rem}
.checks li::before{content:"";position:absolute;left:0;top:7px;width:12px;height:12px;border-radius:50%;background:var(--green)}

/* Campaigns */
.campaigns{display:grid;grid-template-columns:repeat(3,1fr);gap:26px}
.card{background:#fff;border-radius:var(--radius);overflow:hidden;border:1px solid var(--line);display:flex;flex-direction:column}
.card .img{aspect-ratio:16/10;position:relative}
.card .img.c1{background:linear-gradient(135deg,#7FB58F,#2E7D4F)}
.card .img.c2{background:linear-gradient(135deg,#8ECBE0,#3A7CA5)}
.card .img.c3{background:linear-gradient(135deg,#F6C27A,#E8891D)}
.card .img span{position:absolute;left:14px;bottom:14px;background:#fff;color:var(--ink);font-size:.8rem;font-weight:600;padding:5px 12px;border-radius:999px}
.card .body{padding:22px 22px 26px;display:flex;flex-direction:column;gap:12px;flex:1}
.card h3{font-family:var(--serif);font-weight:600;font-size:1.3rem;line-height:1.25}
.card p{font-size:.92rem;color:var(--muted)}
.progress{height:8px;border-radius:99px;background:var(--sand);overflow:hidden;margin-top:auto}
.progress i{display:block;height:100%;background:var(--green);border-radius:99px}
.meta{display:flex;justify-content:space-between;font-size:.85rem;color:var(--muted)}
.meta strong{color:var(--ink)}

/* Donate band */
.donate{background:var(--green-deep);color:#fff}
.donate-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:56px;align-items:center}
.donate h2{font-family:var(--serif);font-weight:600;font-size:clamp(2rem,3.4vw,2.7rem);line-height:1.15;margin-bottom:16px}
.donate p{color:#D5E7DA}
.amounts{display:flex;flex-wrap:wrap;gap:10px;margin:24px 0 18px}
.amt{background:transparent;color:#fff;border:2px solid rgba(255,255,255,.4);border-radius:999px;padding:11px 20px;font-weight:600;cursor:pointer;font-family:inherit;font-size:.95rem}
.amt[aria-pressed="true"],.amt:hover{background:#fff;color:var(--green-deep);border-color:#fff}
.donate-box{background:#fff;color:var(--ink);border-radius:20px;padding:32px}
.donate-box h3{font-family:var(--serif);font-weight:600;font-size:1.4rem;margin-bottom:6px}
.donate-box .sub{color:var(--muted);font-size:.92rem;margin-bottom:20px}
.toggle{display:flex;background:var(--sand);border-radius:999px;padding:4px;margin-bottom:20px}
.toggle button{flex:1;border:0;background:transparent;padding:10px;border-radius:999px;font-weight:600;cursor:pointer;font-family:inherit;color:var(--muted)}
.toggle button[aria-pressed="true"]{background:#fff;color:var(--ink);box-shadow:0 2px 8px rgba(0,0,0,.08)}
.donate-box .btn{width:100%;justify-content:center;margin-top:18px}
.fine{font-size:.8rem;color:var(--muted);margin-top:12px;text-align:center}

/* Volunteer */
.vol{display:grid;grid-template-columns:repeat(3,1fr);gap:22px;margin-bottom:44px}
.vol-stat{background:#fff;border:1px solid var(--line);border-radius:var(--radius);padding:28px}
.vol-stat strong{font-family:var(--serif);font-size:2.4rem;color:var(--green-deep);display:block;line-height:1.1}
.vol-stat span{color:var(--muted);font-size:.95rem}
.vol-cta{display:flex;justify-content:center;gap:14px;flex-wrap:wrap}

/* Contact / Footer */
.contact{display:grid;grid-template-columns:1fr 1fr;gap:56px}
.contact h2{font-family:var(--serif);font-weight:600;font-size:clamp(2rem,3.4vw,2.7rem);line-height:1.15;margin-bottom:14px}
.contact p{color:var(--muted)}
form{display:grid;grid-template-columns:1fr 1fr;gap:14px}
form .full{grid-column:1/-1}
input,select,textarea{font:inherit;width:100%;padding:14px 16px;border:1px solid var(--line);border-radius:12px;background:#fff;color:var(--ink)}
input:focus,select:focus,textarea:focus{outline:3px solid rgba(232,137,29,.35);border-color:var(--saffron)}
textarea{min-height:110px;resize:vertical}
footer{background:var(--ink);color:#C9D1CB;padding:64px 0 28px}
.foot-grid{display:grid;grid-template-columns:1.6fr 1fr 1fr 1fr;gap:40px}
footer h4{color:#fff;font-family:var(--serif);font-weight:600;font-size:1.05rem;margin-bottom:14px}
footer ul{list-style:none;display:grid;gap:9px;font-size:.93rem}
footer a{text-decoration:none}
footer a:hover{color:#fff}
footer .brand{color:#fff}
footer .brand small{color:#9AA69F}
.copy{margin-top:48px;padding-top:22px;border-top:1px solid rgba(255,255,255,.12);font-size:.85rem;color:#9AA69F;display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap}

/* AI assistant launcher */
.assist{position:fixed;right:20px;bottom:20px;z-index:60;display:flex;align-items:center;gap:10px;background:var(--green);color:#fff;border:0;border-radius:999px;padding:14px 20px;font-weight:600;font-family:inherit;font-size:.95rem;cursor:pointer;box-shadow:0 10px 30px rgba(31,92,57,.35)}
.assist .dot2{width:9px;height:9px;border-radius:50%;background:#7CF0A8}

/* Responsive */
@media (max-width:1024px){
  nav ul{gap:18px}
  .phone{display:none}
  .pillars{grid-template-columns:repeat(2,1fr)}
}
@media (max-width:860px){
  nav{position:fixed;inset:72px 0 auto 0;background:var(--cream);border-bottom:1px solid var(--line);display:none;padding:18px 4%}
  nav.open{display:block}
  nav ul{flex-direction:column;gap:4px}
  nav a{display:block;padding:12px 0}
  .menu-btn{display:block}
  .head-cta .btn{display:none}
  .hero{padding:56px 0 64px}
  .hero-grid,.about-grid,.donate-grid,.contact{grid-template-columns:1fr;gap:40px}
  .hero-art{justify-self:center;max-width:420px}
  .about-art{height:400px}
  .campaigns,.vol{grid-template-columns:1fr}
  .foot-grid{grid-template-columns:1fr 1fr}
  section{padding:72px 0}
}
@media (max-width:560px){
  .pillars{grid-template-columns:1fr}
  form{grid-template-columns:1fr}
  .foot-grid{grid-template-columns:1fr}
  .stat-chip{right:0}
}
@media (prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
  *{transition:none!important;animation:none!important}
}
</style>
</head>
<body>

<header>
  <div class="wrap bar">
    <a class="brand" href="#top" aria-label="Suruchi Seva Foundation home">
      <svg width="34" height="34" viewBox="0 0 34 34" aria-hidden="true"><circle cx="17" cy="17" r="16" fill="#2E7D4F"/><path d="M9 20c3-6 13-6 16 0" stroke="#E8891D" stroke-width="3" fill="none" stroke-linecap="round"/><circle cx="17" cy="11" r="3.2" fill="#E8891D"/></svg>
      <span>Suruchi Seva<small>Foundation</small></span>
    </a>
    <nav id="nav" aria-label="Main">
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#work">What we do</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#campaigns">Projects</a></li>
        <li><a href="#volunteer">Volunteer</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="head-cta">
      <a class="phone" href="tel:+910000000000">+91 00000 00000</a>
      <a class="btn btn-saffron" href="#donate">Donate now</a>
      <button class="menu-btn" aria-label="Open menu" aria-expanded="false" aria-controls="nav" id="menuBtn">&#9776;</button>
    </div>
  </div>
</header>

<main id="top">

<!-- Hero -->
<section class="hero" id="home" style="padding-top:88px">
  <div class="wrap hero-grid">
    <div>
      <h1>Clean streets, healthy families, a stronger India.</h1>
      <p class="lead">Suruchi Seva Foundation brings cleanliness, education and care to communities that need it most. Every rupee and every volunteer hour goes back into the neighbourhood.</p>
      <div class="hero-actions">
        <a class="btn btn-ink" href="#donate">Donate now</a>
        <a class="btn btn-line" href="#volunteer">Become a volunteer</a>
      </div>
    </div>
    <div class="hero-art" aria-hidden="true">
      <div class="blob big"></div>
      <div class="blob small"></div>
      <div class="blob tiny"></div>
      <span class="dot" style="left:-2%;top:8%"></span>
      <span class="dot" style="right:12%;top:-3%;background:var(--green)"></span>
      <div class="stat-chip">
        <strong>12,400+</strong>
        <span>people reached through our drives</span>
      </div>
    </div>
  </div>
</section>

<!-- Pillars -->
<section id="work">
  <div class="wrap">
    <div class="head">
      <span class="kicker">Our work</span>
      <h2>Small acts of service, shared widely</h2>
      <p>Four areas where we focus our time, our people and our funds.</p>
    </div>
    <div class="pillars">
      <article class="pillar">
        <div class="ico"><svg width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="#2E7D4F" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M3 21h18M6 21V10l6-6 6 6v11"/><path d="M10 21v-5h4v5"/></svg></div>
        <h3>Clean India drives</h3>
        <p>Neighbourhood clean-ups, waste segregation and awareness campaigns in towns and villages.</p>
      </article>
      <article class="pillar">
        <div class="ico"><svg width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="#2E7D4F" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M2 9l10-5 10 5-10 5z"/><path d="M6 11v5c0 1.5 3 3 6 3s6-1.5 6-3v-5"/></svg></div>
        <h3>Education support</h3>
        <p>Books, uniforms and tutoring so that children stay in school and keep learning.</p>
      </article>
      <article class="pillar">
        <div class="ico"><svg width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="#2E7D4F" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 21s-7-4.5-7-10a4 4 0 0 1 7-2.6A4 4 0 0 1 19 11c0 5.5-7 10-7 10z"/></svg></div>
        <h3>Health and hygiene</h3>
        <p>Health camps, sanitation kits and hygiene lessons for families and schools.</p>
      </article>
      <article class="pillar">
        <div class="ico"><svg width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="#2E7D4F" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><circle cx="9" cy="8" r="3.5"/><path d="M3 20c0-3.3 2.7-6 6-6s6 2.7 6 6"/><path d="M16 11l2 2 4-4"/></svg></div>
        <h3>Women empowerment</h3>
        <p>Skill training and self-help groups that give women income and independence.</p>
      </article>
    </div>
  </div>
</section>

<!-- About -->
<section class="about" id="about">
  <div class="wrap about-grid">
    <div class="about-art" aria-hidden="true">
      <div class="main">Changing lives, one neighbourhood at a time</div>
      <div class="side"></div>
      <div class="side2"></div>
    </div>
    <div>
      <span class="kicker">About us</span>
      <h2>Changing lives with care and knowledge</h2>
      <p class="promise">Our promise: every contribution is spent on the work it was given for, and we report back openly.</p>
      <p>Founded on the belief that a clean environment and an educated child can change a family's future, we work alongside local leaders, schools and volunteers. We measure our impact in real outcomes, not just events held.</p>
      <ul class="checks">
        <li>Transparent use of funds, reported every quarter</li>
        <li>Local teams who know the community first-hand</li>
        <li>Projects guided by partners and government bodies</li>
      </ul>
      <div class="btns">
        <a class="btn btn-ink" href="#contact">Learn more</a>
      </div>
    </div>
  </div>
</section>

<!-- Campaigns -->
<section id="campaigns">
  <div class="wrap">
    <div class="head">
      <span class="kicker">Current campaigns</span>
      <h2>Projects that need your help</h2>
      <p>Each campaign shows how much has been raised so far and what is still needed.</p>
    </div>
    <div class="campaigns">
      <article class="card">
        <div class="img c1"><span>Clean India</span></div>
        <div class="body">
          <h3>Clean Village Mission</h3>
          <p>Waste bins, cleaning equipment and community training for 20 villages this year.</p>
          <div class="meta"><span>Raised <strong>₹3,20,000</strong></span><span>Goal ₹5,00,000</span></div>
          <div class="progress" role="progressbar" aria-label="Clean Village Mission progress" aria-valuenow="64" aria-valuemin="0" aria-valuemax="100"><i style="width:64%"></i></div>
        </div>
      </article>
      <article class="card">
        <div class="img c2"><span>Education</span></div>
        <div class="body">
          <h3>Books for Every Child</h3>
          <p>School supplies, uniforms and after-school reading support for children in government schools.</p>
          <div class="meta"><span>Raised <strong>₹1,45,000</strong></span><span>Goal ₹2,00,000</span></div>
          <div class="progress" role="progressbar" aria-label="Books for Every Child progress" aria-valuenow="72" aria-valuemin="0" aria-valuemax="100"><i style="width:72%"></i></div>
        </div>
      </article>
      <article class="card">
        <div class="img c3"><span>Health</span></div>
        <div class="body">
          <h3>Hygiene Kits for Families</h3>
          <p>Soap, sanitary products and health guidance delivered to households without access.</p>
          <div class="meta"><span>Raised <strong>₹88,000</strong></span><span>Goal ₹1,50,000</span></div>
          <div class="progress" role="progressbar" aria-label="Hygiene Kits progress" aria-valuenow="59" aria-valuemin="0" aria-valuemax="100"><i style="width:59%"></i></div>
        </div>
      </article>
    </div>
  </div>
</section>

<!-- Donate -->
<section class="donate" id="donate">
  <div class="wrap donate-grid">
    <div>
      <span class="kicker" style="color:#F6C27A">Give today</span>
      <h2>Your gift keeps a community clean and a child in school.</h2>
      <p>Choose an amount, pick monthly or one-time giving, and we will send a receipt for tax purposes.</p>
      <div class="amounts" role="group" aria-label="Donation amount">
        <button class="amt" aria-pressed="false" data-amt="500">₹500</button>
        <button class="amt" aria-pressed="true" data-amt="1000">₹1,000</button>
        <button class="amt" aria-pressed="false" data-amt="2500">₹2,500</button>
        <button class="amt" aria-pressed="false" data-amt="5000">₹5,000</button>
      </div>
    </div>
    <div class="donate-box">
      <h3>Make a donation</h3>
      <p class="sub">Secure payment. You can request an 80G receipt.</p>
      <div class="toggle" role="group" aria-label="Donation type">
        <button aria-pressed="true" id="once">One-time</button>
        <button aria-pressed="false" id="monthly">Monthly</button>
      </div>
      <p><strong>Selected: <span id="picked">₹1,000</span></strong></p>
      <a class="btn btn-saffron" href="#contact" id="donateBtn">Donate ₹1,000</a>
      <p class="fine">Payments are processed by a secure gateway. We never store card details.</p>
    </div>
  </div>
</section>

<!-- Volunteer -->
<section id="volunteer">
  <div class="wrap">
    <div class="head">
      <span class="kicker">Get involved</span>
      <h2>Give your time, grow your community</h2>
      <p>Volunteers join clean-up drives, teach in our centres and help run health camps.</p>
    </div>
    <div class="vol">
      <div class="vol-stat"><strong>850+</strong><span>active volunteers across our districts</span></div>
      <div class="vol-stat"><strong>64</strong><span>clean-up and awareness events last year</span></div>
      <div class="vol-stat"><strong>20</strong><span>villages and wards where we work</span></div>
    </div>
    <div class="vol-cta">
      <a class="btn btn-saffron" href="#contact">Register as a volunteer</a>
      <a class="btn btn-line" href="#contact">See upcoming events</a>
    </div>
  </div>
</section>

<!-- Contact -->
<section id="contact" style="background:var(--sand)">
  <div class="wrap contact">
    <div>
      <span class="kicker">Contact</span>
      <h2>Let's talk about how we can work together</h2>
      <p>Write to us about donations, volunteering, partnerships or a community need you have seen. A member of our team will reply within two working days.</p>
      <p style="margin-top:22px"><strong style="color:var(--ink)">Office:</strong> [Your office address, city, Madhya Pradesh]<br><strong style="color:var(--ink)">Email:</strong> [your@email.org]<br><strong style="color:var(--ink)">Phone:</strong> [+91 00000 00000]</p>
    </div>
    <form onsubmit="event.preventDefault();this.reset();alert('Thank you. We will be in touch soon.');">
      <div><label for="n" style="font-size:.85rem;font-weight:600">Full name</label><input id="n" required placeholder="Your name"></div>
      <div><label for="e" style="font-size:.85rem;font-weight:600">Email</label><input id="e" type="email" required placeholder="you@example.com"></div>
      <div class="full"><label for="t" style="font-size:.85rem;font-weight:600">I would like to</label>
        <select id="t"><option>Donate</option><option>Volunteer</option><option>Partner with us</option><option>Ask a question</option></select></div>
      <div class="full"><label for="m" style="font-size:.85rem;font-weight:600">Message</label><textarea id="m" placeholder="Tell us a little about yourself"></textarea></div>
      <div class="full"><button class="btn btn-ink" type="submit" style="width:100%;justify-content:center">Send message</button></div>
    </form>
  </div>
</section>

</main>

<footer>
  <div class="wrap">
    <div class="foot-grid">
      <div>
        <div class="brand">
          <svg width="34" height="34" viewBox="0 0 34 34" aria-hidden="true"><circle cx="17" cy="17" r="16" fill="#E8891D"/><path d="M9 20c3-6 13-6 16 0" stroke="#2E7D4F" stroke-width="3" fill="none" stroke-linecap="round"/><circle cx="17" cy="11" r="3.2" fill="#2E7D4F"/></svg>
          <span>Suruchi Seva<small>Foundation</small></span>
        </div>
        <p style="margin-top:16px;font-size:.93rem;max-width:300px">Clean India vision. Helping people. Built on transparency and trust.</p>
      </div>
      <div><h4>Explore</h4><ul><li><a href="#work">What we do</a></li><li><a href="#about">About us</a></li><li><a href="#campaigns">Projects</a></li></ul></div>
      <div><h4>Get involved</h4><ul><li><a href="#donate">Donate</a></li><li><a href="#volunteer">Volunteer</a></li><li><a href="#contact">Partner with us</a></li></ul></div>
      <div><h4>Legal</h4><ul><li><a href="#">Privacy policy</a></li><li><a href="#">Terms of use</a></li><li><a href="#">Registration details</a></li></ul></div>
    </div>
    <div class="copy"><span>© 2026 Suruchi Seva Foundation. All rights reserved.</span><span>Made with care for a cleaner India.</span></div>
  </div>
</footer>

<button class="assist" aria-label="Chat with our assistant"><span class="dot2" aria-hidden="true"></span>Ask our assistant</button>

<script>
  // Mobile menu
  const menuBtn = document.getElementById('menuBtn');
  const nav = document.getElementById('nav');
  menuBtn.addEventListener('click', () => {
    const open = nav.classList.toggle('open');
    menuBtn.setAttribute('aria-expanded', open);
  });
  nav.querySelectorAll('a').forEach(a => a.addEventListener('click', () => {
    nav.classList.remove('open');
    menuBtn.setAttribute('aria-expanded', 'false');
  }));

  // Donation amount and frequency
  const amounts = document.querySelectorAll('.amt');
  const picked = document.getElementById('picked');
  const donateBtn = document.getElementById('donateBtn');
  const once = document.getElementById('once');
  const monthly = document.getElementById('monthly');
  let freq = 'one-time';

  function fmt(n){ return '₹' + Number(n).toLocaleString('en-IN'); }
  function render(amt){
    picked.textContent = fmt(amt) + (freq === 'monthly' ? ' every month' : '');
    donateBtn.textContent = 'Donate ' + fmt(amt) + (freq === 'monthly' ? ' monthly' : '');
  }
  amounts.forEach(b => b.addEventListener('click', () => {
    amounts.forEach(x => x.setAttribute('aria-pressed', 'false'));
    b.setAttribute('aria-pressed', 'true');
    render(b.dataset.amt);
  }));
  function setFreq(f){
    freq = f;
    once.setAttribute('aria-pressed', f === 'one-time');
    monthly.setAttribute('aria-pressed', f === 'monthly');
    const active = document.querySelector('.amt[aria-pressed="true"]');
    render(active.dataset.amt);
  }
  once.addEventListener('click', () => setFreq('one-time'));
  monthly.addEventListener('click', () => setFreq('monthly'));
</script>
</body>
</html>
