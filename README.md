<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AACE INTERIORS</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800 font-sans">

  <!-- Navbar -->
  <header class="bg-black text-white p-4 shadow-md sticky top-0 z-50">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">AACE INTERIORS</h1>
      <nav class="space-x-4">
        <a href="#about" class="hover:text-gray-400">About</a>
        <a href="#services" class="hover:text-gray-400">Services</a>
        <a href="#projects" class="hover:text-gray-400">Projects</a>
        <a href="#contact" class="hover:text-gray-400">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-gray-100 text-center py-20 px-4">
    <h2 class="text-4xl font-bold mb-4">Designing Spaces that Inspire</h2>
    <p class="text-lg mb-8">Transforming interiors with creativity and purpose.</p>
    <a href="#contact" class="bg-black text-white px-6 py-3 rounded hover:bg-gray-800">Get in Touch</a>
  </section>

  <!-- About Us -->
  <section id="about" class="py-16 px-4 bg-white">
    <div class="container mx-auto max-w-4xl">
      <h3 class="text-3xl font-bold mb-4">About AACE INTERIORS</h3>
      <p class="text-lg text-gray-700">
        AACE INTERIORS is a premier interior design firm delivering stunning, functional environments for residential and commercial clients. We blend creativity, precision, and craftsmanship to transform your vision into a unique space.
      </p>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="bg-gray-50 py-16 px-4">
    <div class="container mx-auto max-w-6xl">
      <h3 class="text-3xl font-bold mb-10 text-center">Our Services</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded shadow">
          <h4 class="font-semibold text-xl mb-2">Residential Design</h4>
          <p>Create beautiful and personalized living spaces that reflect your lifestyle.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="font-semibold text-xl mb-2">Commercial Design</h4>
          <p>Enhancing business environments with functional and attractive interiors.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="font-semibold text-xl mb-2">Renovation & Remodeling</h4>
          <p>Reimagine existing spaces with innovative layouts and modern finishes.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-16 px-4 bg-white">
    <div class="container mx-auto max-w-6xl">
      <h3 class="text-3xl font-bold mb-10 text-center">Our Projects</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-gray-100 h-48 rounded-lg flex items-center justify-center">Project 1</div>
        <div class="bg-gray-100 h-48 rounded-lg flex items-center justify-center">Project 2</div>
        <div class="bg-gray-100 h-48 rounded-lg flex items-center justify-center">Project 3</div>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="bg-gray-50 py-16 px-4">
    <div class="container mx-auto max-w-4xl text-center">
      <h3 class="text-3xl font-bold mb-8">What Our Clients Say</h3>
      <blockquote class="italic text-lg text-gray-600">"AACE Interiors completely transformed our home. Their attention to detail and design expertise were unmatched!" – Jane D.</blockquote>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-4 bg-white">
    <div class="container mx-auto max-w-4xl">
      <h3 class="text-3xl font-bold mb-6">Contact Us</h3>
      <form class="grid gap-4">
        <input type="text" placeholder="Your Name" class="p-3 border rounded w-full"/>
        <input type="email" placeholder="Your Email" class="p-3 border rounded w-full"/>
        <textarea placeholder="Your Message" class="p-3 border rounded w-full rows-4"></textarea>
        <button type="submit" class="bg-black text-white px-6 py-3 rounded hover:bg-gray-800">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-black text-white text-center py-4">
    <p>&copy; 2025 AACE INTERIORS. All rights reserved.</p>
  </footer>

</body>
</html>
