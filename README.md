<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Aaditya Acharya | Web Developer Portfolio</title>

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap"
    rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0f172a;
      color: white;
      overflow-x: hidden;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Navbar */

    .navbar {
      width: 100%;
      padding: 25px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: fixed;
      top: 0;
      left: 0;
      background: rgba(15, 23, 42, 0.9);
      backdrop-filter: blur(10px);
      z-index: 1000;
    }

    .logo {
      font-size: 28px;
      font-weight: 700;
      color: #38bdf8;
    }

    .nav-links {
      display: flex;
      gap: 30px;
      list-style: none;
    }

    .nav-links a {
      font-size: 16px;
      transition: 0.3s;
    }

    .nav-links a:hover {
      color: #38bdf8;
    }

    /* Hero Section */

    .hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 120px 8%;
      gap: 60px;
    }

    .hero-content {
      flex: 1;
    }

    .greeting {
      color: #38bdf8;
      font-size: 20px;
      margin-bottom: 10px;
    }

    .hero-content h1 {
      font-size: 70px;
      line-height: 1.1;
      margin-bottom: 15px;
    }

    .hero-content h2 {
      font-size: 32px;
      color: #cbd5e1;
      margin-bottom: 25px;
      font-weight: 500;
    }

    .description {
      font-size: 17px;
      line-height: 1.8;
      color: #94a3b8;
      max-width: 600px;
      margin-bottom: 35px;
    }

    /* Buttons */

    .hero-buttons {
      display: flex;
      gap: 20px;
      margin-bottom: 35px;
    }

    .btn {
      padding: 14px 28px;
      border-radius: 10px;
      font-weight: 600;
      transition: 0.3s ease;
      display: inline-block;
    }

    .primary {
      background: #38bdf8;
      color: #0f172a;
    }

    .secondary {
      border: 2px solid #38bdf8;
      color: #38bdf8;
    }

    .btn:hover {
      transform: translateY(-4px);
    }

    /* Socials */

    .socials {
      display: flex;
      gap: 20px;
    }

    .socials a {
      color: #94a3b8;
      transition: 0.3s;
    }

    .socials a:hover {
      color: #38bdf8;
    }

    /* Image */

    .hero-image {
      flex: 1;
      display: flex;
      justify-content: center;
    }

    .hero-image img {
      width: 350px;
      height: 350px;
      object-fit: cover;
      border-radius: 50%;
      border: 5px solid #38bdf8;
      box-shadow: 0 0 40px rgba(56, 189, 248, 0.4);
    }

    /* About Section */

    .about-section {
      padding: 100px 8%;
      background: #111827;
    }

    .section-title {
      font-size: 42px;
      margin-bottom: 20px;
      color: #38bdf8;
    }

    .about-text {
      max-width: 800px;
      line-height: 1.9;
      color: #cbd5e1;
      font-size: 17px;
    }

    /* Skills */

    .skills {
      padding: 100px 8%;
    }

    .skills-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 40px;
    }

    .skill-card {
      background: #1e293b;
      padding: 18px 30px;
      border-radius: 12px;
      transition: 0.3s;
    }

    .skill-card:hover {
      transform: translateY(-5px);
      background: #38bdf8;
      color: #0f172a;
    }

    /* Footer */

    footer {
      padding: 30px;
      text-align: center;
      background: #020617;
      color: #94a3b8;
    }

    /* Responsive */

    @media(max-width: 900px) {

      .hero {
        flex-direction: column-reverse;
        text-align: center;
        padding-top: 150px;
      }

      .hero-content h1 {
        font-size: 50px;
      }

      .hero-content h2 {
        font-size: 24px;
      }

      .hero-buttons,
      .socials {
        justify-content: center;
      }

      .hero-image img {
        width: 260px;
        height: 260px;
      }

      .nav-links {
        display: none;
      }
    }
  </style>
</head>

<body>

  <!-- Navbar -->

  <header class="navbar">

    <div class="logo">Aadi.</div>

    <ul class="nav-links">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Skills</a></li>
      <li><a href="#">Projects</a></li>
      <li><a href="#">Contact</a></li>
    </ul>

  </header>

  <!-- Hero Section -->

  <main class="hero">

    <section class="hero-content">

      <p class="greeting">Hello, I'm</p>

      <h1>Aaditya Acharya</h1>

      <h2>Web Developer & Programmer</h2>

      <p class="description">
        Passionate web developer from Chitwan, Nepal.
        I create modern, responsive, and user-friendly
        websites with clean design and smooth user experiences.
      </p>

      <div class="hero-buttons">
        <a href="/cv.pdf" class="btn primary">Download CV</a>
        <a href="/contact.html" class="btn secondary">Contact Me</a>
      </div>

      <div class="socials">
        <a href="https://github.com/AadiAcharya" target="_blank">GitHub</a>

        <a href="https://linkedin.com" target="_blank">LinkedIn</a>

        <a href="https://twitter.com" target="_blank">Twitter</a>
      </div>

    </section>

    <section class="hero-image">
      <img src="me.jpg" alt="Aaditya Acharya">
    </section>

  </main>

  <!-- About Section -->

  <section class="about-section">

    <h2 class="section-title">About Me</h2>

    <p class="about-text">
      I'm a passionate and self-motivated developer who enjoys
      building modern web applications and continuously learning
      new technologies. I love turning ideas into real projects
      and creating clean, responsive, and interactive user interfaces.
      Apart from coding, I enjoy travelling and exploring new places.
    </p>

  </section>

  <!-- Skills -->

  <section class="skills">

    <h2 class="section-title">Skills</h2>

    <div class="skills-container">

      <div class="skill-card">HTML</div>

      <div class="skill-card">CSS</div>

      <div class="skill-card">JavaScript</div>

      <div class="skill-card">React</div>

      <div class="skill-card">Node.js</div>

      <div class="skill-card">Git & GitHub</div>

      <div class="skill-card">Responsive Design</div>

      <div class="skill-card">UI/UX</div>

    </div>

  </section>

  <!-- Footer -->

  <footer>
    © 2026 Aaditya Acharya. All Rights Reserved.
  </footer>

</body>

</html>
