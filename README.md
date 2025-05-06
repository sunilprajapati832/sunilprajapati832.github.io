<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title> h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      color: var(--accent);
      margin-bottom: 1rem;
    } Portfolio </title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0e0e0e;
      --text: #ffffff;
      --glass: rgba(255, 255, 255, 0.05);
      --accent: #ffffff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background: var(--bg);
      color: var(--text);
      overflow-x: hidden;
      position: relative;
    }

    /* Sparkle Background */
    body::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(white 1px, transparent 1px);
      background-size: 40px 40px;
      opacity: 0.05;
      z-index: 0;
    }

    header {
      text-align: center;
      padding: 5rem 1rem 3rem;
      background: #000;
      z-index: 1;
      position: relative;
    }

    header h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      color: var(--accent);
      margin-bottom: 1rem;
    }

    header p {
      font-size: 1.2rem;
      color: #aaa;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      background: rgba(255, 255, 255, 0.02);
      backdrop-filter: blur(8px);
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      color: var(--text);
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ccc;
    }

    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
      z-index: 1;
      position: relative;
    }

    h2 {
      font-size: 2rem;
      text-align: center;
      margin-bottom: 1rem;
      color: var(--accent);
    }

    .card {
      background: var(--glass);
      padding: 2rem;
      margin: 2rem auto;
      border-radius: 15px;
      backdrop-filter: blur(12px);
      border: 1px solid rgba(255,255,255,0.1);
      box-shadow: 0 0 20px rgba(255,255,255,0.05);
    }

    .card p, .card a {
      color: #ddd;
    }

    .projects a {
      color: var(--accent);
      font-weight: bold;
      text-decoration: none;
    }

    .projects a:hover {
      text-decoration: underline;
    }

    .contact a {
      color: var(--accent);
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 2rem;
      color: #999;
      background: #111;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Sunil Prajapati</h1>
    <p>Research Student | Data Analytics | Python Developer</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <div class="card">
      <p>
        Proficient in Python, MySQL, Image Processing & Machine Learning. Dynamic professional with experience as an Operational Director at Education Development Unit, skilled in strategic planning and resource optimization. Proven ability in public relations and event management, showcasing leadership and negotiation skills.
      </p>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="card projects">
      <p>Explore my GitHub repositories for work in AI, ML, and data analytics:</p>
      <a href="https://github.com/sunilprajapati832" target="_blank">→ View My GitHub</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="card contact">
      <p>Email: <a href="mailto:sunilp832@gmail.com">sunilp832@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/sunil-prajapati832" target="_blank">linkedin.com/in/sunil-prajapati832</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Sunil Prajapati | Portfolio</p>
  </footer>

</body>
</html>
