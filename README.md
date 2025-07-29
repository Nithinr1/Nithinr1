<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio | BCA Student</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f7fa;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #4e73df, #2c3e50);
      color: white;
      padding: 60px 20px;
      text-align: center;
      animation: fadeIn 1s ease-in;
    }

    header h1 {
      margin-bottom: 10px;
      font-size: 2.8em;
    }

    nav {
      text-align: center;
      background: #35469c;
      padding: 12px 0;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: 500;
      font-size: 1.1em;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffea00;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      animation: fadeIn 1s ease-in;
    }

    h2 {
      font-size: 2em;
      margin-bottom: 20px;
      color: #2c3e50;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .box {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .box:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    .contact {
      background: #e2e8f0;
      border-radius: 10px;
      padding: 25px;
    }

    .contact a {
      color: #35469c;
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #2c3e50;
      color: white;
      font-size: 0.9em;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
      }

      nav a {
        margin: 0 10px;
        font-size: 1em;
      }
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(30px); }
      100% { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <header>
    <h1>Hi, I'm Nithin</h1>
    <p>BCA Student | Web Developer |</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a hre="#resume">Resume</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm a Bachelor of Computer Applications student passionate about coding and technology.
      I enjoy building web apps, exploring new tools, and solving real-world problems using software.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="box">HTML5, CSS3</div>
      <div class="box">Python, Java</div>
      <div class="box">MySQL, Database</div>
      <div class="box"> GitHub,C</div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="box">
        <h3>Student Management System</h3>
        <p>A CRUD-based web app for managing student records using PHP and MySQL.</p>
      </div>
      <div class="box">
        <h3>Portfolio Website</h3>
        <p>A personal portfolio website built using HTML, CSS, and JavaScript.</p>
      </div>
      <div class="box">
        <h3>Text-to-Speech Translator (Python)</h3>
        <p>A Python application that converts input text to speech using the gTTS library, useful for accessibility and language learning.</p>
      </div>
    </div>
  </section>
  <section id="resume">
  <h2>Resume</h2>
  <p>You can download or view my resume using the button below:</p>
  <a href="C:\Users\JEEVITHA S L\Downloads\New folder" download target="_blank" style="
    display: inline-block;
    margin-top: 15px;
    padding: 12px 24px;
    background-color: #4e73df;
    color: white;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
    transition: background 0.3s;">
    📄 Download Resume
  </a>
</section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="contact">
      <p>Email: nithinr439340@gmail.com</p>
      <p>Phone: +91 8904590644</p>
      <p>GitHub: <a href="https://github.com/nithin" target="_blank">github.com/nithin</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/nithin" target="_blank">linkedin.com/in/nithin</a></p>
    </div>
  </section>

  <footer>
    © 2025 Nithin | BCA Portfolio
  </footer>
  

</body>
</html>
