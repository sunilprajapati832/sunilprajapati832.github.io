<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Quantum Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Orbitron', sans-serif;
      background: url('https://images.unsplash.com/photo-1600267165989-98f36b1267c9?auto=format&fit=crop&w=1500&q=80') no-repeat center center fixed;
      background-size: cover;
      color: white;
      overflow-x: hidden;
    }
    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.85);
      z-index: -1;
    }
    header {
      text-align: center;
      padding: 50px 20px;
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 3px solid #00ffcc;
    }
    header h1 {
      font-size: 3rem;
      color: #00ffcc;
    }
    header h2 {
      margin-top: 10px;
      font-size: 1.2rem;
      color: #aaa;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section h3 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #00ccff;
    }
    .about, .projects, .contact {
      background: #111;
      margin-bottom: 20px;
      border-left: 5px solid #00ffcc;
      padding: 20px;
      border-radius: 8px;
    }
    .about p, .projects p, .contact p {
      line-height: 1.8;
      color: #ddd;
    }
    .projects a, .contact a {
      color: #00ccff;
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 30px;
      font-size: 0.9rem;
      color: #666;
      background: #0f0f0f;
    }
    .spark {
      position: fixed;
      width: 2px;
      height: 2px;
      background: #ffffff;
      animation: spark 2s infinite;
    }
    @keyframes spark {
      0% { opacity: 0; transform: translateY(0) scale(1); }
      50% { opacity: 1; transform: translateY(-10px) scale(1.5); }
      100% { opacity: 0; transform: translateY(-20px) scale(0); }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://avatars.githubusercontent.com/u/104108589?v=4" alt="Sunil Prajapati Avatar">
    <h1>Sunil Prajapati</h1>
    <h2>Research Student | Data Analytics | Python Developer</h2>
  </header>

  <section class="about">
    <h3>About Me</h3>
    <p>
      Proficient in Python, MySQL, Image Processing & Machine Learning. Dynamic professional with experience as an Operational Director at Education Development Unit, skilled in strategic planning and resource optimization. Proven ability in public relations and event management, showcasing leadership and negotiation skills.
    </p>
  </section>

  <section class="projects">
    <h3>Projects</h3>
    <p>
      Explore my projects on GitHub: <a href="https://github.com/sunilprajapati832" target="_blank">github.com/sunilprajapati832</a>
    </p>
  </section>

  <section class="contact">
    <h3>Contact</h3>
    <p>Email: <a href="mailto:sunilp832@gmail.com">sunilp832@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/sunil-prajapati832" target="_blank">linkedin.com/in/sunil-prajapati832</a></p>
  </section>

  <footer>
    &copy; 2025 Sunil Prajapati | All rights reserved.
  </footer>

  <script>
    for (let i = 0; i < 60; i++) {
      const spark = document.createElement('div');
      spark.className = 'spark';
      spark.style.left = Math.random() * 100 + 'vw';
      spark.style.top = Math.random() * 100 + 'vh';
      spark.style.animationDelay = Math.random() * 5 + 's';
      document.body.appendChild(spark);
    }
  </script>
</body>
</html>
