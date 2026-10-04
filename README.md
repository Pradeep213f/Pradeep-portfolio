# Pradeep-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pradeep Singh Danu | IT Portfolio</title>
<meta name="description" content="Portfolio and resume of Pradeep Singh Danu, BCA graduate and technology professional.">
<style>
:root{
  --bg:#f7f8fa; --card:#ffffff; --text:#18212b; --muted:#667085;
  --primary:#173b5f; --line:#e4e7ec; --accent:#2f6f9f;
  --soft:#eef4f8;
}
*{box-sizing:border-box;scroll-behavior:smooth}
body{margin:0;font-family:Inter,Arial,sans-serif;background:var(--bg);color:var(--text);line-height:1.6}
a{text-decoration:none;color:inherit}
.container{width:min(1080px,92%);margin:auto}
nav{position:sticky;top:0;z-index:20;background:rgba(255,255,255,.94);backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
.navbar{height:70px;display:flex;align-items:center;justify-content:space-between}
.logo{font-size:21px;font-weight:800;color:var(--primary)}
.navlinks{display:flex;gap:24px;font-size:14px;font-weight:600;color:#475467}
.navlinks a:hover{color:var(--accent)}
.hero{padding:90px 0 75px;background:linear-gradient(135deg,#eef4f8,#fff)}
.hero-grid{display:grid;grid-template-columns:1.45fr .75fr;gap:55px;align-items:center}
.badge{display:inline-block;background:#e5eef5;color:var(--primary);padding:7px 13px;border-radius:20px;font-size:13px;font-weight:700}
h1{font-size:52px;line-height:1.08;margin:18px 0 15px;color:var(--primary)}
.hero p{font-size:18px;color:var(--muted);max-width:700px}
.buttons{display:flex;gap:12px;margin-top:28px;flex-wrap:wrap}
.btn{padding:12px 19px;border-radius:7px;font-weight:700;font-size:14px;border:1px solid var(--primary);cursor:pointer}
.btn.primary{background:var(--primary);color:#fff}
.btn.secondary{background:#fff;color:var(--primary)}
.profile-card{background:#fff;border:1px solid var(--line);padding:28px;border-radius:16px;box-shadow:0 15px 40px #173b5f12}
.profile-card .initials{width:90px;height:90px;border-radius:50%;display:grid;place-items:center;background:var(--primary);color:#fff;font-size:30px;font-weight:800;margin-bottom:20px}
section{padding:72px 0}
.section-title{font-size:30px;color:var(--primary);margin:0 0 8px}
.section-subtitle{color:var(--muted);margin:0 0 30px}
.grid-2{display:grid;grid-template-columns:1fr 1fr;gap:22px}
.grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.card{background:var(--card);border:1px solid var(--line);border-radius:13px;padding:25px}
.card h3{margin-top:0;color:var(--primary)}
.skills{display:flex;flex-wrap:wrap;gap:10px}
.skill{background:#eef3f7;border:1px solid #dce6ed;padding:8px 12px;border-radius:7px;font-size:13px;font-weight:700;color:#29465f}
.skill-group{margin-bottom:20px}
.skill-group:last-child{margin-bottom:0}
.skill-group strong{display:block;margin-bottom:10px;color:var(--primary)}
.timeline{border-left:2px solid #d6e0e7;padding-left:25px}
.timeline-item{position:relative;margin-bottom:34px}
.timeline-item:last-child{margin-bottom:0}
.timeline-item:before{content:"";position:absolute;width:10px;height:10px;border-radius:50%;background:var(--accent);left:-31px;top:7px}
.date{font-size:13px;color:var(--muted)}
ul{padding-left:20px}
li{margin-bottom:7px}
.project{display:flex;flex-direction:column;height:100%}
.project .tech{font-size:13px;color:var(--accent);font-weight:700;margin-top:auto;padding-top:15px}
.project-date{font-size:13px;color:var(--muted);font-weight:600}
.contact-box{background:var(--primary);color:#fff;border-radius:16px;padding:35px}
.contact-box h2{margin-top:0}
.contact-box p{color:#d9e5ef}
.contact-links{display:flex;flex-wrap:wrap;gap:12px;margin-top:20px}
.contact-link{display:inline-block;background:#fff;color:var(--primary);padding:9px 13px;border-radius:7px;font-weight:700;font-size:13px}
footer{text-align:center;padding:28px;color:var(--muted);font-size:13px;border-top:1px solid var(--line)}
@media(max-width:800px){
  .navlinks{display:none}.hero-grid,.grid-2,.grid-3{grid-template-columns:1fr}
  h1{font-size:40px}.hero{padding-top:65px}
}
@media print{
  nav,.buttons,footer{display:none!important}
  body{background:#fff}.hero{padding:25px 0}section{padding:25px 0}.container{width:95%}
}
</style>
</head>
<body>

<nav>
  <div class="container navbar">
    <a class="logo" href="#home">Pradeep.</a>
    <div class="navlinks">
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#experience">Experience</a>
      <a href="#education">Education</a>
      <a href="#contact">Contact</a>
    </div>
  </div>
</nav>

<header class="hero" id="home">
  <div class="container hero-grid">
    <div>
      <span class="badge">BCA Graduate • Technology Professional</span>
      <h1>Pradeep Singh Danu</h1>
      <p>
        Dedicated technology professional with a BCA background and experience in Decathlon
        retail operations. Interested in software development, SAP, cloud technologies and
        business automation.
      </p>
      <div class="buttons">
        <a class="btn primary" href="#projects">View Projects</a>
        <a class="btn secondary" href="#contact">Contact Me</a>
        <button class="btn secondary" onclick="window.print()">Download / Print Resume</button>
      </div>
    </div>

    <div class="profile-card">
      <div class="initials">PS</div>
      <h3>IT Career Profile</h3>
      <p><b>Education:</b> Bachelor of Computer Applications</p>
      <p><b>Current Role:</b> Sports Advisor / OSA — Decathlon India</p>
      <p><b>Focus:</b> Python • Java • SQL • Web Development • SAP</p>
      <p><b>Location:</b> Lucknow, India</p>
    </div>
  </div>
</header>

<section id="about">
  <div class="container">
    <h2 class="section-title">Professional Summary</h2>
    <p class="section-subtitle">Technology, operations and practical problem solving.</p>
    <div class="card">
      <p>
        Dedicated technology professional with a BCA background and experience in Decathlon
        retail operations. Skilled in Python, SQL, Excel, and software development fundamentals,
        with an interest in SAP, cloud technologies, and business automation.
      </p>
      <p>
        Experienced in understanding operational requirements, solving problems, and collaborating
        with teams to improve processes.
      </p>
    </div>
  </div>
</section>

<section id="skills">
  <div class="container">
    <h2 class="section-title">Technical Skills</h2>
    <p class="section-subtitle">Technologies and professional strengths from my resume.</p>

    <div class="grid-2">
      <div class="card">
        <div class="skill-group">
          <strong>Programming</strong>
          <div class="skills">
            <span class="skill">Python</span>
            <span class="skill">Java</span>
            <span class="skill">C++</span>
          </div>
        </div>

        <div class="skill-group">
          <strong>Web Technologies</strong>
          <div class="skills">
            <span class="skill">HTML</span>
            <span class="skill">CSS</span>
            <span class="skill">JavaScript</span>
            <span class="skill">React.js</span>
            <span class="skill">Node.js</span>
            <span class="skill">Express.js</span>
          </div>
        </div>

        <div class="skill-group">
          <strong>Databases</strong>
          <div class="skills">
            <span class="skill">MySQL</span>
            <span class="skill">MongoDB</span>
          </div>
        </div>
      </div>

      <div class="card">
        <div class="skill-group">
          <strong>Core Computer Science</strong>
          <div class="skills">
            <span class="skill">DBMS</span>
            <span class="skill">Operating Systems</span>
            <span class="skill">Computer Networks</span>
          </div>
        </div>

        <div class="skill-group">
          <strong>Professional Skills</strong>
          <div class="skills">
            <span class="skill">Communication</span>
            <span class="skill">Teamwork</span>
            <span class="skill">Analytical Ability</span>
            <span class="skill">Organization</span>
          </div>
        </div>

        <div class="skill-group">
          <strong>Additional Tools / Interests</strong>
          <div class="skills">
            <span class="skill">Excel</span>
            <span class="skill">SAP</span>
            <span class="skill">Cloud Technologies</span>
            <span class="skill">Business Automation</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="experience">
  <div class="container">
    <h2 class="section-title">Professional Experience</h2>
    <p class="section-subtitle">Professional experience and internship work.</p>

    <div class="timeline">
      <div class="timeline-item">
        <h3>Decathlon India — Sports Advisor / OSA</h3>
        <div class="date">Lucknow, India • 2026 – Present</div>
        <ul>
          <li>Support customers by understanding requirements, recommending suitable products, and resolving queries in a fast-paced retail environment.</li>
          <li>Collaborate with team members on daily operations, department activities, customer service, and store processes.</li>
          <li>Handle responsibilities requiring communication, organization, problem-solving, and attention to operational details.</li>
          <li>Develop practical understanding of business operations and customer-facing processes, supporting a transition toward business technology and IT roles.</li>
        </ul>
      </div>

      <div class="timeline-item">
        <h3>Bharat Intern — Web Development Intern</h3>
        <div class="date">September 2024 – October 2024</div>
        <ul>
          <li>Developed a responsive Netflix-style web interface using HTML, CSS and JavaScript.</li>
          <li>Implemented a dynamic user interface while focusing on clean and maintainable code.</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="projects">
  <div class="container">
    <h2 class="section-title">Projects</h2>
    <p class="section-subtitle">Software projects demonstrating full-stack and real-time application development.</p>

    <div class="grid-2">
      <div class="card project">
        <div class="project-date">July 2024</div>
        <h3>MyChat — Real-Time Chat Application</h3>
        <ul>
          <li>Developed a real-time chat application with WebSocket and Firebase, including user authentication.</li>
          <li>Implemented document sharing through the chat interface.</li>
        </ul>
        <div class="tech">MERN Stack • WebSocket • Firebase</div>
      </div>

      <div class="card project">
        <div class="project-date">October 2024</div>
        <h3>LetsGoShow — Full-Stack Ticket Booking Application</h3>
        <ul>
          <li>Built a full-stack ticket booking application for browsing, booking, and managing movie tickets.</li>
          <li>Implemented secure user login and signup functionality.</li>
          <li>Integrated a payment gateway and real-time ticket booking functionality.</li>
        </ul>
        <div class="tech">React.js • Express.js • MongoDB • Node.js • MERN Stack</div>
      </div>
    </div>
  </div>
</section>

<section id="education">
  <div class="container">
    <h2 class="section-title">Education</h2>
    <p class="section-subtitle">Academic background.</p>

    <div class="grid-2">
      <div class="card">
        <h3>Graphic Era Hill University, Dehradun, India</h3>
        <div class="date">2022 – 2025</div>
        <p><b>BCA — Bachelor of Computer Applications</b></p>
        <p>GPA: 6.8 (aggregate)</p>
      </div>

      <div class="card">
        <h3>Army Public School, S.P. Marg, Lucknow Cantt</h3>
        <div class="date">2021 – 2022</div>
        <p><b>CBSE Class XII</b> — Humanities with Entrepreneurship</p>
        <p>80%</p>
      </div>

      <div class="card">
        <h3>Army Public School, S.P. Marg, Lucknow Cantt</h3>
        <div class="date">2019 – 2020</div>
        <p><b>CBSE Class X</b></p>
        <p>90%</p>
      </div>
    </div>
  </div>
</section>

<section id="certifications">
  <div class="container">
    <h2 class="section-title">Certifications & Achievements</h2>

    <div class="grid-2">
      <div class="card">
        <h3>Certifications</h3>
        <ul>
          <li>Python Coding Certificate — IIT Bombay</li>
          <li>Web Development — Gymnasium</li>
        </ul>
      </div>

      <div class="card">
        <h3>Leadership & Achievements</h3>
        <ul>
          <li><b>Sports Captain, Army Public School</b> — Led the student council, organized events, and coordinated between students and administration.</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="contact">
  <div class="container">
    <div class="contact-box">
      <h2>Let's Connect</h2>
      <p>I'm interested in opportunities where I can apply my technical skills, business understanding and problem-solving abilities.</p>

      <p><b>Email:</b> pradeepdanu911@gmail.com</p>
      <p><b>Phone:</b> +91-7860523751</p>

      <div class="contact-links">
        <!-- Add your actual profile URLs to the href values below -->
        <a class="contact-link" href="#" aria-label="LinkedIn profile">LinkedIn</a>
        <a class="contact-link" href="#" aria-label="GitHub profile">GitHub</a>
      </div>
    </div>
  </div>
</section>

<footer>
  © 2026 Pradeep Singh Danu • Built with HTML & CSS
</footer>

</body>
</html>
