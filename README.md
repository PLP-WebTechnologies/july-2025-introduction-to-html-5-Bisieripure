<!DOCTYPE html>
<html lang="en">
<head>
  <!-- SEO Essentials -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Personal portfolio website of [Your Name], showcasing skills, projects, and contact information. Built with HTML5 semantic tags, accessibility, and SEO best practices.">
  <meta name="author" content="[Your Name]">
  <title>[Your Name] | Portfolio</title>
</head>
<body>
  <!-- Page Header -->
  <header role="banner">
    <h1>[Your Name]</h1>
    <p>Aspiring Web Developer | HTML5 Enthusiast | Lifelong Learner</p>
  </header>

  <!-- Navigation -->
  <nav aria-label="Main navigation">
    <ul>
      <li><a href="#about" aria-current="page">About Me</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Main Content -->
  <main id="main-content">
    <!-- About Section -->
    <section id="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About Me</h2>
      <p>
        Hello! I’m <strong>[Your Name]</strong>, currently learning web technologies. 
        This page demonstrates my understanding of <em>HTML5 semantic structure</em>, 
        accessibility best practices, and beginner-friendly SEO techniques.
      </p>
    </section>

    <!-- Projects Section -->
    <section id="projects" aria-labelledby="projects-heading">
      <h2 id="projects-heading">Projects</h2>

      <article aria-labelledby="project1-title">
        <header>
          <h3 id="project1-title">HTML5 Semantic Webpage</h3>
          <p><time datetime="2025-08-28">August 28, 2025</time></p>
        </header>
        <p>
          A simple project built entirely with HTML5 semantic elements. 
          It demonstrates accessibility landmarks, heading hierarchy, and SEO-friendly structure.
        </p>
      </article>

      <article aria-labelledby="project2-title">
        <header>
          <h3 id="project2-title">Portfolio Prototype</h3>
          <p><time datetime="2025-08-20">August 20, 2025</time></p>
        </header>
        <p>
          A prototype personal portfolio site that introduces me, 
          showcases my early projects, and provides easy ways to connect.
        </p>
      </article>
    </section>

    <!-- Contact Section -->
    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact Me</h2>
      <address>
        <p>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
        <p>Phone: <a href="tel:+1234567890">+1 234 567 890</a></p>
      </address>
    </section>
  </main>

  <!-- Footer -->
  <footer role="contentinfo">
    <p>&copy; 2025 [Your Name]. All rights reserved.</p>
    <nav aria-label="Footer navigation">
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </footer>
</body>
</html>
