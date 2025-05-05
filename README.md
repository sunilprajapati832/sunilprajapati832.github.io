<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Name | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f5f5f5;
    }
    header {
      background: #333;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
    }
    nav {
      background: #444;
      text-align: center;
      padding: 0.5rem 0;
    }
    nav a {
      color: #fff;
      margin: 0 1rem;
      text-decoration: none;
    }
    section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .card {
      background: white;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #222;
      color: #fff;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <p>Web Developer | Designer | Student</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm a passionate web developer learning front-end and back-end technologies. I love building responsive websites and exploring new tools in tech.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>A responsive portfolio built with HTML and CSS, hosted on GitHub Pages.</p>
      </div>
      <div class="card">
        <h3>To-Do App</h3>
        <p>A simple JavaScript to-do list app with add/remove functionality and local storage.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: your.email@example.com</p>
    <p>GitHub: <a href="https://github.com/yourusername" target="_blank">yourusername</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">yourprofile</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>
