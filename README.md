# haseeb-portfolio-website

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio Website </title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <a href="#home">Home</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <img src="HASEEB (2).jpeg" alt="Profile" />
    <h1>Haseeb Mumraiz</h1>
    <p>Front-End Developer • Software Engineer</p>
  </section>
  <section>
    <h2>About Me</h2>
    <p>
      I am a passionate front-end developer with experience in creating dynamic and responsive web applications. I love coding and continuously learning new technologies to enhance my skills.
    </p>
    background in software engineering and a keen eye for design, I strive to build user-friendly and visually appealing websites.
  </section>

  <section>
    <h2>Education</h2>
    <ul>
      <li>Bachelor's in software enjeering - SMI University (2022- 2025)</li>
      <li>aptech learning</li>
    </ul>
  </section>
  </section>

  <section class="section" id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div>HTML</div>
      <div>CSS</div>
      <div>JavaScript</div>
      <div>React Basics</div>
      <div>C++</div>
      <div>Git</div>
    </div>
  </section>

  <section class="section" id="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <img src="project1.jpg" alt="Project 1" />
      <h3>Project 1</h3>
      <p>Designed & developed a responsive personal portfolio website using HTML, CSS & JavaScript. Includes project showcase, navigation, and contact form</p>
    </div>
    <div class="project-card">
      <img src="project2.jpg" alt="Project 2" />
      <h3>Project 2</h3>
    <div>
        <p>
        Designed & built a clean, responsive Weather App interface using HTML, CSS & JavaScript. Displays temperature, humidity & conditions dynamically
        </p>
    </div>
      <p>Project 2:
Designed & built a clean, responsive Weather App interface using HTML, CSS & JavaScript. Displays temperature, humidity & conditions dynamically</p>
    </div>
  </section>
<section class="section" id="projects">
  <h2>Projects</h2>
</section>

  <section class="section" id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="PORTFOLIO WEBSITE " placeholder="HASEEB MUMRAIZ" required />
      <input type="email" placeholder="QURESHIHASEEB421@GMAIL.COM" required />
      <textarea placeholder="Message" rows="5" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    © 2025 HASEEB PORTFOLIO WEBSITE
  </footer>
</body>
 css language 
 
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: url('background.jpg') no-repeat center center/cover;
  color: #fff;
}

header {
  background: rgba(0,0,0,0.6);
  padding: 1rem;
  position: fixed;
  width: 100%;
}

nav {
  display: flex;
  justify-content: center;
  gap: 1.5rem;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 120px 20px;
  background-color: bluergba(0,0,0,0.5);
  background-image: -moz-radial-gradient();
}

.hero img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #fff;
}

.section {
  background: rgba(0,0,0,0.6);
  margin: 20px;
  padding: 20px;
  border-radius: 10px;
}

.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.project-card {
  margin: 10px 0;
}

form input, form textarea, form button {
  width: 100%;
  margin: 10px 0;
  padding: 10px;
  border: none;
  border-radius: 5px;
}

footer {
  text-align: center;
  padding: 20px;
  background: rgba(0,0,0,0.6);
}
.section h2 {
  border-bottom: 1px
   solid #000000;
  padding-bottom: 10px;
  column-rule-color: rgb(22, 2, 2)2, 2, 2);
}
.about mwedia {
  max-width: 600px;
  margin: 0 auto;
  line-height: 1.6;
}
/* PROJECT CARDS */
.project-container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
  margin-top: 20px;
}

.project-card {
  width: 280px;
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(6px);
  padding: 15px;
  border-radius: 12px;
  text-align: center;
  transition: 0.3s;
}

.project-card:hover {
  transform: translateY(-8px);
}

.project-card img {
  width: 100%;
  height: 160px;
  border-radius: 10px;
  object-fit: cover;
}

.project-card h3 {
  margin-top: 10px;
  font-size: 20px;
}

.project-card p {
  font-size: 14px;
  opacity: 0.8;
  margin: 10px 0;
}

.btn {
  display: inline-block;
  padding: 8px 15px;
  border-radius: 8px;
  background: #fff;
  color: #000;
  text-decoration: none;
  font-weight: bold;
  transition: 0.3s;
}

.btn:hover {
  background: #ddd;
}
/* Full background theme */
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;

  /* ✅ Background Image */
  background: url("b.g\ img.avif") no-repeat center center fixed;

  /* ✅ Full-screen auto scale */
  background-size: cover;

  Text color
  color: #fff;
}
.background{
    background-position: 1px;
}: url("images/background.jpg") no-repeat center center fixed;
