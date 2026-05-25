<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Adam Elhoseiny</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,600;9..144,700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --accent: #1F4E79;
    --accent-light: #2E6CA8;
    --dark: #1a1a1a;
    --gray: #555;
    --light-gray: #888;
    --bg: #fafafa;
    --card: #ffffff;
    --border: #e8e8e8;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'Inter', sans-serif;
    background: var(--bg);
    color: var(--dark);
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
  }

  h1, h2, h3 { font-family: 'Fraunces', serif; font-weight: 600; }

  .container { max-width: 860px; margin: 0 auto; padding: 0 28px; }

  /* ===== NAV ===== */
  nav {
    position: sticky; top: 0; z-index: 100;
    background: rgba(250,250,250,0.85);
    backdrop-filter: blur(10px);
    border-bottom: 1px solid var(--border);
  }
  nav .container {
    display: flex; justify-content: space-between; align-items: center;
    height: 60px;
  }
  nav .logo { font-family: 'Fraunces', serif; font-weight: 700; font-size: 1.15rem; color: var(--accent); }
  nav .links a {
    color: var(--gray); text-decoration: none; margin-left: 24px;
    font-size: 0.9rem; font-weight: 500; transition: color 0.2s;
  }
  nav .links a:hover { color: var(--accent); }
  @media (max-width: 600px) { nav .links a { margin-left: 14px; font-size: 0.8rem; } }

  /* ===== HERO ===== */
  header {
    padding: 90px 0 70px;
    border-bottom: 1px solid var(--border);
    background:
      radial-gradient(circle at 80% 20%, rgba(46,108,168,0.06), transparent 45%),
      radial-gradient(circle at 10% 80%, rgba(31,78,121,0.05), transparent 40%);
  }
  header .eyebrow {
    color: var(--accent); font-weight: 600; font-size: 0.85rem;
    letter-spacing: 0.12em; text-transform: uppercase; margin-bottom: 14px;
  }
  header h1 { font-size: 3.4rem; line-height: 1.05; color: var(--dark); font-weight: 700; }
  header h1 .accent { color: var(--accent); }
  header .tagline { font-size: 1.2rem; color: var(--gray); margin-top: 18px; max-width: 560px; }
  header .meta { margin-top: 26px; display: flex; flex-wrap: wrap; gap: 10px 22px; color: var(--light-gray); font-size: 0.9rem; }
  header .meta a { color: var(--accent); text-decoration: none; }
  header .meta a:hover { text-decoration: underline; }
  @media (max-width: 600px) { header h1 { font-size: 2.3rem; } header { padding: 56px 0 44px; } }

  /* ===== SECTIONS ===== */
  section { padding: 56px 0; border-bottom: 1px solid var(--border); }
  .section-label {
    color: var(--accent); font-weight: 600; font-size: 0.8rem;
    letter-spacing: 0.14em; text-transform: uppercase; margin-bottom: 8px;
  }
  section h2 { font-size: 1.9rem; margin-bottom: 28px; color: var(--dark); }

  .item { margin-bottom: 26px; }
  .item:last-child { margin-bottom: 0; }
  .item-head { display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 4px; }
  .item-title { font-weight: 600; font-size: 1.08rem; color: var(--dark); }
  .item-meta { color: var(--light-gray); font-size: 0.88rem; }
  .item-role { color: var(--accent); font-size: 0.92rem; font-weight: 500; margin-top: 2px; }
  .item ul { margin: 10px 0 0; padding-left: 18px; }
  .item li { color: var(--gray); margin-bottom: 5px; font-size: 0.97rem; }

  /* ===== PROJECT CARDS ===== */
  .projects-grid { display: grid; gap: 18px; }
  .card {
    background: var(--card); border: 1px solid var(--border); border-radius: 14px;
    padding: 24px 26px; transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
  }
  .card:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 30px rgba(31,78,121,0.10);
    border-color: var(--accent-light);
  }
  .card .badge {
    display: inline-block; background: rgba(31,78,121,0.08); color: var(--accent);
    font-size: 0.72rem; font-weight: 600; letter-spacing: 0.05em;
    padding: 4px 10px; border-radius: 20px; margin-bottom: 12px; text-transform: uppercase;
  }
  .card h3 { font-size: 1.25rem; margin-bottom: 8px; color: var(--dark); }
  .card p { color: var(--gray); font-size: 0.96rem; }
  .card .prize { color: var(--accent); font-weight: 600; }
  .card.featured {
    border: 2px solid var(--accent);
    background: linear-gradient(135deg, rgba(31,78,121,0.04), rgba(46,108,168,0.02));
  }
  .card.featured .badge { background: var(--accent); color: #fff; }

  /* ===== SKILLS ===== */
  .skills-row { margin-bottom: 16px; }
  .skills-row .label { font-weight: 600; color: var(--dark); margin-bottom: 8px; }
  .tags { display: flex; flex-wrap: wrap; gap: 8px; }
  .tag {
    background: var(--card); border: 1px solid var(--border); color: var(--gray);
    padding: 6px 14px; border-radius: 20px; font-size: 0.88rem; font-weight: 500;
  }

  /* ===== CONTACT ===== */
  .contact-box { text-align: center; padding: 20px 0 0; }
  .contact-box p { color: var(--gray); margin-bottom: 22px; font-size: 1.05rem; }
  .btn {
    display: inline-block; background: var(--accent); color: #fff; text-decoration: none;
    padding: 13px 30px; border-radius: 30px; font-weight: 600; font-size: 0.98rem;
    transition: background 0.2s, transform 0.2s;
  }
  .btn:hover { background: var(--accent-light); transform: translateY(-2px); }

  /* ===== FOOTER ===== */
  footer { text-align: center; padding: 34px 0; color: var(--light-gray); font-size: 0.85rem; }

  /* ===== SCROLL ANIMATION ===== */
  .reveal { opacity: 0; transform: translateY(24px); transition: opacity 0.6s ease, transform 0.6s ease; }
  .reveal.visible { opacity: 1; transform: translateY(0); }
</style>
</head>
<body>

<nav>
  <div class="container">
    <span class="logo">Adam Elhoseiny</span>
    <div class="links">
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </div>
</nav>

<header>
  <div class="container">
    <p class="eyebrow">Student · Robotics Builder · Goalkeeper</p>
    <h1>Hi, I'm <span class="accent">Adam</span>.</h1>
    <p class="tagline">A Grade 9 student at The KAUST School with a strong academic record, a habit of starting small ventures, and hands-on robotics experience — including an autonomous robot I presented to the President of KAUST.</p>
    <div class="meta">
      <span>📍 KAUST, Thuwal, Saudi Arabia</span>
      <a href="mailto:adam.m.elhoseiny@gmail.com">✉️ adam.m.elhoseiny@gmail.com</a>
    </div>
  </div>
</header>

<section id="about">
  <div class="container reveal">
    <p class="section-label">About</p>
    <h2>A bit about me</h2>
    <p style="color:var(--gray); font-size:1.05rem; max-width:640px;">
      I'm an entrepreneurial student who likes turning ideas into real things — whether that's a small
      business at school, an AI project with my team, or an autonomous robot. I build and program robots
      for the FIRST Tech Challenge, balance academics with competitive soccer (as a goalkeeper), and I'm
      always looking for the next thing to build.
    </p>
  </div>
</section>

<section id="education">
  <div class="container reveal">
    <p class="section-label">Education</p>
    <h2>Education</h2>
    <div class="item">
      <div class="item-head">
        <span class="item-title">The KAUST School (TKS) — Gardens Secondary School (GSS)</span>
        <span class="item-meta">Thuwal, Saudi Arabia</span>
      </div>
      <div class="item-role">Grade 9 (entering 2026–2027) · attended since Grade 7</div>
    </div>
    <div class="item">
      <div class="item-head">
        <span class="item-title">Christensen Middle School</span>
        <span class="item-meta">Livermore, California, USA</span>
      </div>
      <div class="item-role">Grade 6</div>
      <ul>
        <li>Gold Honor Roll — earned twice for 4.0 GPA terms.</li>
        <li>Silver Honor Roll — earned for a 3.67 GPA term.</li>
      </ul>
    </div>
  </div>
</section>

<section id="projects">
  <div class="container reveal">
    <p class="section-label">Projects</p>
    <h2>Things I've built</h2>
    <div class="projects-grid">
      <div class="card featured">
        <span class="badge">⭐ Presented to the President of KAUST · Featured on Madinah News</span>
        <h3>Autonomous Color-Sorting Robot (VEX Clawbot)</h3>
        <p>Built and modified a VEX Clawbot to autonomously identify and pick up objects by color.
        In November 2025, I presented it to the <span class="prize">President of KAUST</span> and was
        <span class="prize">featured on Madinah news</span>, and also presented the project to the
        KAUST Robotics Club at its launch.</p>
      </div>
      <div class="card">
        <span class="badge">2nd Place · $500 Prize</span>
        <h3>Climate Prediction AI Model</h3>
        <p>Part of a six-person team at the 2025 SAAI Competition that built an AI model forecasting
        climate conditions 10, 50, and 100 years ahead. I led the presentation and editing to communicate
        our results clearly, and we <span class="prize">placed 2nd overall</span>.</p>
      </div>
      <div class="card">
        <span class="badge">Nov 2021</span>
        <h3>Cardboard Cereal Dispenser</h3>
        <p>Designed and built a functional cereal dispenser entirely from cardboard — an early hands-on engineering project.</p>
      </div>
    </div>
  </div>
</section>

<section id="experience">
  <div class="container reveal">
    <p class="section-label">Experience</p>
    <h2>Ventures & involvement</h2>
    <div class="item">
      <div class="item-head">
        <span class="item-title">Snack Resale Ventures</span>
        <span class="item-meta">Grades 7–8</span>
      </div>
      <div class="item-role">Founder & Operator</div>
      <ul>
        <li>Bought snacks (Takis, Lunchly) in bulk and resold them at school, generating consistent profit.</li>
        <li>Managed inventory, pricing, and customer demand independently across multiple terms.</li>
      </ul>
    </div>
    <div class="item">
      <div class="item-head">
        <span class="item-title">Peer Tutoring Service</span>
        <span class="item-meta">Grade 7</span>
      </div>
      <div class="item-role">Co-Founder</div>
      <ul>
        <li>Launched a tutoring venture with classmates; gained early experience in marketing and outreach.</li>
      </ul>
    </div>
    <div class="item">
      <div class="item-head">
        <span class="item-title">KAUST Robotics Club — FIRST Tech Challenge (FTC)</span>
        <span class="item-meta">Nov 2025 – Present</span>
      </div>
      <div class="item-role">Member · in collaboration with ITKAAN HQ, Dallas, Texas</div>
      <ul>
        <li>Designs, builds, and programs robots for FTC competition.</li>
      </ul>
    </div>
    <div class="item">
      <div class="item-head">
        <span class="item-title">ITKAAN Robotics Team — San Jose</span>
        <span class="item-meta">June 2025 – Present</span>
      </div>
      <ul>
        <li>Develops robotics skills and C programming while building and testing robots.</li>
      </ul>
    </div>
    <div class="item">
      <div class="item-head">
        <span class="item-title">Soccer — Falcons Club & TKS School Teams</span>
        <span class="item-meta">2020 – Present</span>
      </div>
      <div class="item-role">Goalkeeper</div>
      <ul>
        <li>Plays club soccer for the Falcons and represents TKS school teams (first-semester seasons).</li>
        <li>🥈 2nd Place — Red Sea Activity Conference (RSAC) regional tournament (Grade 8).</li>
        <li>🥇 1st Place — Falcons club tournament (May 8, 2025).</li>
      </ul>
    </div>
  </div>
</section>

<section id="skills">
  <div class="container reveal">
    <p class="section-label">Skills</p>
    <h2>What I bring</h2>
    <div class="skills-row">
      <div class="label">Languages</div>
      <div class="tags">
        <span class="tag">Arabic (fluent)</span>
        <span class="tag">English (fluent)</span>
        <span class="tag">Spanish (conversational)</span>
      </div>
    </div>
    <div class="skills-row">
      <div class="label">Technical</div>
      <div class="tags">
        <span class="tag">Robotics (VEX, FTC)</span>
        <span class="tag">C programming</span>
        <span class="tag">Autonomous systems</span>
        <span class="tag">Presentation & editing</span>
      </div>
    </div>
    <div class="skills-row">
      <div class="label">Strengths</div>
      <div class="tags">
        <span class="tag">Entrepreneurship</span>
        <span class="tag">Teamwork</span>
        <span class="tag">Problem-solving</span>
        <span class="tag">Time management</span>
        <span class="tag">Initiative</span>
      </div>
    </div>
  </div>
</section>

<section id="contact" style="border-bottom:none;">
  <div class="container reveal">
    <p class="section-label" style="text-align:center;">Contact</p>
    <h2 style="text-align:center;">Let's connect</h2>
    <div class="contact-box">
      <p>Feel free to reach out — I'm always open to new opportunities and ideas.</p>
      <a class="btn" href="mailto:adam.m.elhoseiny@gmail.com">Get in touch</a>
    </div>
  </div>
</section>

<footer>
  © <span id="year"></span> Adam Elhoseiny · Built with care.
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();

  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.12 });
  reveals.forEach(r => observer.observe(r));
</script>

</body>
</html>
