<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sandro's Portfolio</title>
  <link rel="stylesheet" href="./dist/styles.css"> <!-- Link to the generated CSS -->
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f3f4f6; /* Light gray background */
      color: #333; /* Dark gray text */
    }

    header {
      background-color: #1d4ed8; /* Blue color */
      color: white;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin: 0;
    }

    header p {
      font-size: 1.25rem;
      margin-top: 0.5rem;
    }

    section {
      padding: 2rem;
    }

    .section-title {
      font-size: 2rem;
      margin-bottom: 1rem;
      border-bottom: 2px solid #1d4ed8;
      display: inline-block;
      padding-bottom: 0.5rem;
    }

    .about, .contact {
      text-align: center;
    }

    .about p {
      max-width: 800px;
      margin: 0 auto;
      font-size: 1.125rem;
    }

    .projects {
      background-color: #f9fafb; /* Slightly darker gray */
    }

    .project-card {
      background-color: white;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      margin-bottom: 1.5rem;
      text-align: center;
    }

    .project-card h3 {
      font-size: 1.5rem;
      margin: 0;
    }

    .project-card p {
      margin: 0.5rem 0;
    }

    .project-card a {
      color: #1d4ed8; /* Blue color */
      text-decoration: none;
      font-weight: bold;
    }

    .project-card a:hover {
      text-decoration: underline;
    }

    .contact {
      background-color: #4b5563; /* Dark gray */
      color: white;
    }

    .contact a {
      background-color: #f59e0b; /* Yellow color */
      color: black;
      padding: 0.5rem 1.5rem;
      border-radius: 9999px; /* Fully rounded */
      text-decoration: none;
      font-weight: bold;
    }

    .contact a:hover {
      background-color: #fbbf24; /* Slightly lighter yellow */
    }

    footer {
      background-color: #1d4ed8; /* Blue color */
      color: white;
      text-align: center;
      padding: 1rem;
    }

    @media (max-width: 768px) {
      .projects {
        padding: 1rem;
      }

      .project-card {
        margin-bottom: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Sandro Abreu</h1>
    <p>Web Developer | Full Stack Developer</p>
  </header>

  <!-- About Me Section -->
  <section class="about">
    <h2 class="section-title">About Me</h2>
    <p>I am a web developer specializing in building dynamic and responsive web applications. I use modern tools like ASP.NET Core MVC, Tailwind CSS, JavaScript, and MySQL to deliver clean and efficient code.</p>
  </section>

  <!-- Projects Section -->
  <section class="projects">
    <h2 class="section-title">Projects</h2>
    <div class="project-card">
      <h3>E-Commerce Website</h3>
      <p>Developed an e-commerce platform using ASP.NET Core MVC and MySQL.</p>
      <a href="#">View Project</a>
    </div>
    <!-- Repeat for more projects -->
  </section>

  <!-- Contact Section -->
  <section class="contact">
    <h2 class="section-title">Get In Touch</h2>
    <p>Feel free to reach out to me for any web development opportunities or collaborations.</p>
    <a href="mailto:pt09san@outlook.com">Email Me</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Sandro Abreu</p>
  </footer>

</body>
</html>
