# Portfolio---Santosh
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Santosh Singh | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }
    body {
      background-color: #ffffff;
      color: #333;
      line-height: 1.6;
    }
    header, section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h1, h2 {
      color: #222;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background: #f4f4f4;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding-top: 80px;
    }
    .skills-list, .projects-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .card {
      padding: 20px;
      background: #f9f9f9;
      border: 1px solid #ddd;
      border-radius: 10px;
      text-align: center;
    }
    .contact {
      background: #f0f0f0;
      padding: 40px 20px;
      text-align: center;
    }
    .btn {
      display: inline-block;
      padding: 10px 20px;
      background: #007bff;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <nav>
    <div><strong>Santosh Singh</strong></div>
    <div>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>  <header class="hero">
    <h1>Hi, I'm Santosh Singh</h1>
    <p>Full Stack Developer | Content Creator | Language Enthusiast</p>
    <a class="btn" href="#contact">Hire Me</a>
  </header>  <section id="about">
    <h2>About Me</h2>
    <p>I’m a passionate full stack web developer and content creator. I’ve built educational channels that offer free learning to students, and I’m fluent in multiple languages including Russian, German, Japanese, Chinese, French, English, Sanskrit, and Hindi. I’ve read over 500 books and enjoy writing too—currently working on my own book!</p>
  </section>  <section id="skills">
    <h2>Skills</h2>
    <div class="skills-list">
      <div class="card">HTML</div>
      <div class="card">CSS</div>
      <div class="card">JavaScript</div>
      <div class="card">Python</div>
      <div class="card">C++</div>
      <div class="card">Frontend Dev</div>
      <div class="card">Backend Dev</div>
      <div class="card">Content Writing</div>
      <div class="card">Critical Thinking</div>
      <div class="card">Language Fluency</div>
    </div>
  </section>  <section id="projects">
    <h2>Projects</h2>
    <div class="projects-list">
      <div class="card">Educational YouTube Channel 1</div>
      <div class="card">Educational YouTube Channel 2</div>
      <div class="card">Portfolio Website</div>
      <div class="card">Web Apps (To-do, Blog, etc.)</div>
    </div>
  </section>  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: tg701198@gmail.com</p>
    <a class="btn" href="resume.pdf" download>Download Resume</a>
  </section>
</body>
</html>
