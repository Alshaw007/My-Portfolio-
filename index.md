---
#  Alfred M. Nyeswa  –  3-D Portfolio
#  Built with nothing but Markdown + CSS
#  Host on GitHub Pages → Settings → Pages → Source: main / root
---

<style>
/* ---------- 3-D UI ---------- */
:root{
  --accent:#00f2ff;
  --dark:#0a0a0a;
  --light:#ffffff;
}
*{margin:0;padding:0;box-sizing:border-box}
body{
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,sans-serif;
  background:var(--dark);
  color:var(--light);
  scroll-behavior:smooth;
  perspective:1000px;          /* 3-D space */
}
section{
  transform-style:preserve-3d;
  padding:10vh 5vw;
  min-height:100vh;
  display:flex;
  flex-direction:column;
  justify-content:center;
}
h1,h2,h3{line-height:1.2;margin-bottom:.5em}
h1{font-size:clamp(2.5rem,5vw,4rem)}
h2{font-size:clamp(1.8rem,4vw,2.8rem)}
p,li{line-height:1.6;font-size:1.05rem}
a{color:var(--accent);text-decoration:none}
a:hover{text-decoration:underline}

/* glass cards */
.card{
  background:rgba(255,255,255,.05);
  backdrop-filter:blur(10px);
  border:1px solid rgba(255,255,255,.1);
  border-radius:12px;
  padding:2rem;
  margin:1rem 0;
  transform:rotateX(10deg) rotateY(-5deg);
  transition:transform .4s;
}
.card:hover{transform:rotateX(0) rotateY(0) scale(1.03)}
.grid{display:grid;gap:2rem;grid-template-columns:repeat(auto-fit,minmax(280px,1fr))}

/* subtle float animation */
@keyframes float{
  0%,100%{transform:translateY(0)}
  50%{transform:translateY(-8px)}
}
.float{animation:float 4s ease-in-out infinite}
</style>

<!-- ==========================================================
HERO – INTRO
========================================================== -->
<section id="home">
<div class="card float" style="max-width:720px;margin:auto;text-align:center">
<h1>Alfred M. Nyeswa</h1>
<p>Enthusiastic Technologist  <wbr> |  AI & Robotics Engineer  <wbr> |  Co-Founder <a href="https://facebook.com/ekaninternational" target="_blank">EKAN International</a>
<br>
Monrovia, Liberia · <a href="mailto:alshaw007@gmail.com">alshaw007@gmail.com</a> · <a href="https://linkedin.com/in/alfred-nyeswa-bb980b19b" target="_blank">LinkedIn</a>
</p>
</div>
</section>

<!-- ==========================================================
ABOUT
========================================================== -->
<section id="about">
<h2>About Me</h2>
<div class="card">
<p>Associate of Science, Computer & Information Sciences – BlueCrest University College (2024)<br>
Associate of Arts, Chinese Language & Literature – Confucius Institute, University of Liberia (2018)</p>

<p>Software / Robotics Engineer at <strong>OpenSource Team-Liberia</strong> (Apr 2023 – present, 2 yrs 7 mos on-site, Monrovia).</p>

<p>I build AI-first, open-source hardware & software that tackle real problems: safe water, mobility for the blind, smarter farming, and inclusive STEM education.</p>
</div>
</section>

<!-- ==========================================================
PROJECTS
========================================================== -->
<section id="projects">
<h2>Featured Projects</h2>

<div class="grid">
<div class="card">
<h3>VisionAid</h3>
<p>Smart attachable cane system for the visually impaired. Uses advanced sensors for obstacle detection & real-time feedback.</p>
<b>Outcome:</b> 1<sup>st</sup> Place – TME Arduino Robotics Hackathon (Mar 2025)<br>
<b>Stack:</b> Arduino, sensors, 3-D printed housing
</div>

<div class="card">
<h3>AquaGuard</h3>
<p>Innovative water-testing & treatment solution created during Orange Liberia “Tech4Impact” Summer Challenge (15 Nov 2024).</p>
<b>Status:</b> Pilot deployed in Paynesville community
</div>

<div class="card">
<h3>AI Agri-Assistant</h3>
<p>WhatsApp-based agronomy bot that gives Liberian small-holders instant, localised advice.</p>
<b>Stage:</b> MVP live → <a href="https://wa.me/231770914292?text=Hi" target="_blank">try it</a>
</div>

<div class="card">
<h3>Face-Recognition AI</h3>
<p>Light-weight KYC & attendance model (PyTorch → ONNX) running on edge devices.</p>
<b>Accuracy:</b> 97.3 % | <b>Inference:</b> &lt;200 ms on RPi 4
</div>
</div>
</section>

<!-- ==========================================================
CERTIFICATIONS
========================================================== -->
<section id="certs">
<h2>Licenses & Certifications</h2>
<div class="card">
<ul>
<li>Machine Learning Specialization – Stanford Online (Oct 2025)</li>
<li>Supervised ML: Regression & Classification – Stanford Online (Sep 2025)</li>
<li>Python for Everybody Specialization – University of Michigan (Aug 2025)</li>
<li>Using Python to Access Web Data – University of Michigan (Aug 2025)</li>
<li>Capstone: Retrieving & Visualising Data with Python – University of Michigan (Aug 2025)</li>
<li>Agile with Atlassian Jira – Atlassian (Oct 2025)</li>
<li>LinkedIn “Ethical Hacking: Introduction” – LinkedIn Learning (Nov 2023)</li>
<li>Introduction to Artificial Intelligence – Simplilearn (Jul 2022)</li>
<li>HP LIFE badges: Digital Business Skills, Setting Prices, Social Entrepreneurship, Starting a Small Business, Success Mindset, Unique Value Proposition, Basics of Finance, Design Thinking, Effective Leadership, Finding Funding (all Oct 2025)</li>
</ul>
</div>
</section>

<!-- ==========================================================
SKILLS
========================================================== -->
<section id="skills">
<h2>Technical Skills</h2>
<div class="card">
<b>Languages:</b> Python, JavaScript, C/C++, SQL, Dart, Chinese (CEFR B1 spoken)<br>
<b>AI / ML:</b> PyTorch, TensorFlow, OpenCV, Scikit-learn, NumPy, Pandas<br>
<b>Cloud & DevOps:</b> AWS, Firebase, Docker, GitHub Actions<br>
<b>Hardware:</b> Arduino, ESP32, Raspberry Pi, KiCad, 3-D printing<br>
<b>Mobile / Web:</b> Flutter, React, Node, FastAPI<br>
<b>Soft:</b> Cross-functional team leadership, product management, grant writing, public speaking
</div>
</section>

<!-- ==========================================================
CONNECT
========================================================== -->
<section id="connect">
<h2>Let’s Connect</h2>
<div class="card" style="text-align:center">
<p>Open for freelance software & product contracts, research collaboration, and impact-focused partnerships.</p>
<a href="mailto:alshaw007@gmail.com">Email</a> |
<a href="https://linkedin.com/in/alfred-nyeswa-bb980b19b" target="_blank">LinkedIn</a> |
<a href="https://wa.me/231770914292" target="_blank">WhatsApp</a> |
<a href="https://facebook.com/ekaninternational" target="_blank">EKAN on Facebook</a>
</div>
</section>

<!-- ---------- tiny scroll-spy ---------- -->
<script>
/* highlight nav link on scroll - optional 6-lines */
const sections=document.querySelectorAll('section');
window.addEventListener('scroll',()=>{
  let cur='';sections.forEach(s=>{if(pageYOffset>=s.offsetTop-60)cur=s.id});
  document.querySelectorAll('a[href^="#"]').forEach(a=>a.classList.toggle('active',a.hash.slice(1)===cur));
});
</script>
