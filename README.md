<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sandro's Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/3.3.2/tailwind.min.css"> <!-- Link to Tailwind CSS CDN -->
  <style>
    .bg-primary {
      background-color: #1D4ED8; /* Tailwind Blue 700 */
    }
    .bg-secondary {
      background-color: #4B5563; /* Tailwind Gray 700 */
    }
    .text-primary {
      color: #1D4ED8; /* Tailwind Blue 700 */
    }
    .text-accent {
      color: #F59E0B; /* Tailwind Yellow 500 */
    }
    .custom-heading {
      border-bottom: 2px solid #1D4ED8; /* Tailwind Blue 700 */
      display: inline-block;
      padding-bottom: 0.5rem;
    }
    .card-shadow {
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Header -->
  <header class="bg-primary text-white p-6">
    <h1 class="text-4xl font-bold text-center">Sandro Abreu</h1>
    <p class="text-center text-lg mt-2">Web Developer | Full Stack Developer</p>
  </header>

  <!-- About Me Section -->
  <section id="about" class="p-8 text-center">
    <h2 class="text-3xl font-semibold mb-4 custom-heading">About Me</h2>
    <p class="max-w-3xl mx-auto text-lg">I am a web developer specializing in building dynamic and responsive web applications. I use modern tools like ASP.NET Core MVC, Tailwind CSS, JavaScript, and MySQL to deliver clean and efficient code.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="p-8 bg-gray-100">
    <h2 class="text-3xl font-semibold text-center mb-8">Projects</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
      <!-- Project Card -->
      <div class="bg-white p-6 rounded-lg shadow-lg card-shadow">
        <h3 class="text-xl font-bold">E-Commerce Website</h3>
        <p class="mt-2">Developed an e-commerce platform using ASP.NET Core MVC and MySQL.</p>
        <a href="#" class="text-primary mt-4 inline-block hover:underline">View Project</a>
      </div>
      <!-- Repeat for more projects -->
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="p-8 text-center bg-secondary text-white">
    <h2 class="text-3xl font-semibold mb-4">Get In Touch</h2>
    <p class="mb-6">Feel free to reach out to me for any web development opportunities or collaborations.</p>
    <a href="mailto:pt09san@outlook.com" class="bg-accent text-black py-2 px-6 rounded-full hover:bg-yellow-400">Email Me</a>
  </section>

  <!-- Footer -->
  <footer class="bg-primary text-white text-center p-4">
    <p>&copy; 2024 Sandro Abreu</p>
  </footer>

</body>
</html>
