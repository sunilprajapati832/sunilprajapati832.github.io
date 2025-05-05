<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sunil Prajapati | Portfolio</title>
  <style>
    :root {
      --primary: #6a11cb;
      --secondary: #2575fc;
      --light: #f4f4f4;
      --dark: #333;
      --text-light: #ffffff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: var(--light);
      color: var(--dark);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: var(--text-light);
      padding: 3rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
    }

    nav {
      background: #fff;
      padding: 0.8rem;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: var(--primary);
      font-weight: bold;
    }

    section {
      padding: 2rem 1rem;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      color: var(--primary);
      margin-bottom: 1rem;
      font-size: 1.8rem;
    }

    .projects a {
      display: inline-block;
      background: var(--secondary);
      color: #fff;
      padding: 1rem 2rem;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }

    .projects a:hover {
      background: var(--primary);
    }

    .contact p {
      margin: 0.5rem 0;
    }

    footer {
      background: var(--dark);
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      section {
        padding: 1.5rem 1rem;
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
    <p>
      Proficient in Python, MySQL, Image Processing, and Machine Learning. Dynamic professional with experience as an Operational Director at Education Development Unit, skilled in strategic planning and resource optimization. Proven ability in public relations and event management, showcasing leadership and negotiation skills.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>Explore my GitHub repositories and projects:</p>
    <div class="projects">
      <a href="https://github.com/sunilprajapati832" target="_blank">View My GitHub Projects</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="contact">
      <p><strong>Email:</strong> <a href="mailto:sunilp832@gmail.com">sunilp832@gmail.com</a></p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/sunil-prajapati832" target="_blank">www.linkedin.com/in/sunil-prajapati832</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Sunil Prajapati. All rights reserved.</p>
  </footer>

</body>
</html>
