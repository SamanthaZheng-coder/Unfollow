<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Samantha Zheng's Portfolio - Web Developer">
  <title>Samantha Zheng</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Source+Code+Pro&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>

<body>

  <!-- Navigation -->
  <nav class="navbar">
    <div class="container">
      <a id="logo-container" href="#top" class="brand-logo">samantha zheng</a>
      <ul class="nav-list">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <div class="home-content">
      <h1 class="text_h center header cd-headline letters type">
        <span>I am </span>
        <span class="jstext">Sa</span><span class="typed-cursor">|</span>
      </h1>
      <p class="intro-text">A web developer with a passion for creating impactful user experiences.</p>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <div class="container">
      <h2 class="center header text_h2" id="about-header"> Hi there, I'm <span class="span_h2"> Samantha Zheng</span>! I am a recent graduate from General Assembly's <span class="span_h2"> Web Development Immersive </span> program and a web developer based in <span class="span_h2"> New York </span>.</h2>
      <p class="bio-text">I specialize in front-end web development with a strong focus on building responsive and interactive websites. My passion for coding comes from a desire to continuously learn and innovate. I believe in writing clean and maintainable code while always keeping the user experience in mind.</p>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <div class="container">
      <h2 class="header text_h2">My Projects</h2>
      <div class="project-grid">
        <!-- Example Project 1 -->
        <div class="project-item">
          <h3 class="project-title">Project 1</h3>
          <p class="project-description">This is a description of Project 1. It uses HTML, CSS, and JavaScript to create an interactive experience.</p>
          <a href="#" class="project-link">View Project</a>
        </div>
        <!-- Example Project 2 -->
        <div class="project-item">
          <h3 class="project-title">Project 2</h3>
          <p class="project-description">This is a description of Project 2. It is built with React and Node.js to handle complex data interactions.</p>
          <a href="#" class="project-link">View Project</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="container">
      <h2 class="header text_h2">Get In Touch</h2>
      <p class="contact-info">If you'd like to collaborate on a project or just say hello, feel free to reach out!</p>
      <ul class="social-icons">
        <li><a class="github-link" href="https://github.com/samantha-zheng"><i class="fa fa-github fa-2x tooltipped" data-position="top" data-delay="50" data-tooltip="Github"></i></a></li>
        <li><a class="linkedin-link" href="https://www.linkedin.com/in/samzheng99"><i class="fa fa-linkedin fa-2x tooltipped" data-position="top" data-delay="50" data-tooltip="LinkedIn"></i></a></li>
        <li><a class="instagram-link" href="https://www.instagram.com/samzheng99/?hl=en"><i class="fa fa-instagram fa-2x tooltipped" data-position="top" data-delay="50" data-tooltip="Instagram"></i></a></li>
        <li><a class="resume-link" href="./images/samantha_zheng_resume.pdf"><i class="fa fa-user fa-2x tooltipped" data-position="top" data-delay="50" data-tooltip="Resume"></i></a></li>
        <li><a class="email-link" href="mailto:zhengsaman@email.com"><i class="fa fa-envelope fa-2x tooltipped" data-position="top" data-delay="50" data-tooltip="E-mail me!"></i></a></li>
      </ul>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2025 Samantha Zheng. All Rights Reserved.</p>
    </div>
  </footer>

  <!-- Scripts -->
  <script src="scripts.js"></script>
</body>

</html>
