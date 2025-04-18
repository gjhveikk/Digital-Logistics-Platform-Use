<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Digital Logistics - Smart Logistics</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow-md fixed w-full z-10">
    <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
      <div class="flex items-center">
        <img src="logo.png" alt="Digital Logistics Logo" class="h-8 w-8 mr-2" />
        <span class="font-bold text-xl">Digital Logistics</span>
      </div>
      <nav class="hidden md:flex space-x-6">
        <a href="#features" class="hover:text-blue-600">Features</a>
        <a href="#why" class="hover:text-blue-600">Why</a>
        <a href="#mission" class="hover:text-blue-600">Mission</a>
        <a href="#signup" class="hover:text-blue-600">Sign Up</a>
        <a href="#login" class="bg-blue-600 text-white px-4 py-1 rounded">Login</a>
      </nav>
      <button class="md:hidden" id="menu-btn">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </div>
  </header>

  <!-- Mobile Menu -->
  <div class="md:hidden bg-white shadow-md hidden" id="mobile-menu">
    <a href="#features" class="block px-4 py-2 border-b">Features</a>
    <a href="#why" class="block px-4 py-2 border-b">Why</a>
    <a href="#mission" class="block px-4 py-2 border-b">Mission</a>
    <a href="#signup" class="block px-4 py-2 border-b">Sign Up</a>
    <a href="#login" class="block px-4 py-2">Login</a>
  </div>

  <!-- Hero Section -->
  <section class="pt-24 pb-16 text-center bg-gradient-to-r from-blue-500 to-green-400 text-white">
    <div class="max-w-3xl mx-auto px-4">
      <h1 class="text-4xl md:text-5xl font-bold mb-4">Smart Logistics for Every Corner of the World</h1>
      <p class="mb-6">Simplify delivery, inventory, and transport — accessible on any device, anywhere.</p>
      <a href="#signup" class="bg-white text-blue-600 px-6 py-3 rounded shadow-lg font-semibold">Get Started</a>
    </div>
  </section>

  <!-- Why Digital Logistics -->
  <section id="why" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-4">Why Digital Logistics?</h2>
      <p class="mb-6">Digital Logistics brings modern tools to traditional challenges. With real-time tracking, modular features, and full supply chain visibility, businesses stay connected, responsive, and efficient — no matter the environment.</p>
    </div>
  </section>

  <!-- Mission, Vision, Values -->
  <section id="mission" class="py-16 bg-gray-100">
    <div class="max-w-6xl mx-auto px-4 grid grid-cols-1 md:grid-cols-3 gap-8">
      <div>
        <h3 class="text-xl font-bold mb-2">Mission</h3>
        <p>To simplify and strengthen logistics management for businesses and organizations globally through a mobile-first, user-centered platform.</p>
      </div>
      <div>
        <h3 class="text-xl font-bold mb-2">Vision</h3>
        <p>To be the most trusted logistics platform empowering every team, from local entrepreneurs to global NGOs, to operate with intelligence and ease.</p>
      </div>
      <div>
        <h3 class="text-xl font-bold mb-2">Core Values</h3>
        <ul class="list-disc list-inside">
          <li>Accessibility</li>
          <li>Flexibility</li>
          <li>Simplicity</li>
          <li>Scalability</li>
          <li>Inclusivity</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Features -->
  <section id="features" class="py-16">
    <div class="max-w-6xl mx-auto px-4 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
      <div class="bg-white rounded-lg shadow p-6">
        <h3 class="font-semibold text-xl mb-2">Delivery Requests</h3>
        <p>Request pickup, track status, and confirm delivery in real time.</p>
      </div>
      <div class="bg-white rounded-lg shadow p-6">
        <h3 class="font-semibold text-xl mb-2">Inventory Management</h3>
        <p>Monitor stock levels across warehouses with simple tools.</p>
      </div>
      <div class="bg-white rounded-lg shadow p-6">
        <h3 class="font-semibold text-xl mb-2">Warehouse Oversight</h3>
        <p>Manage locations, capacities, and movements seamlessly.</p>
      </div>
      <div class="bg-white rounded-lg shadow p-6">
        <h3 class="font-semibold text-xl mb-2">Transport Coordination</h3>
        <p>Assign drivers and vehicles, optimize routes, and track fleets.</p>
      </div>
      <div class="bg-white rounded-lg shadow p-6">
        <h3 class="font-semibold text-xl mb-2">Security & Logs</h3>
        <p>Record security events and ensure safe handling of goods.</p>
      </div>
      <div class="bg-white rounded-lg shadow p-6">
        <h3 class="font-semibold text-xl mb-2">Supply Chain Visibility</h3>
        <p>Gain a full overview of operations, from order placement to delivery.</p>
      </div>
    </div>
  </section>

  <!-- FAQ Section -->
  <section id="faq" class="py-16 bg-gray-100">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-4">Frequently Asked Questions</h2>
      <div class="space-y-6">
        <div class="bg-white p-6 rounded-lg shadow">
          <h3 class="font-semibold text-xl mb-2">What is Digital Logistics?</h3>
          <p>Digital Logistics is a smart logistics platform designed to simplify supply chain management, focusing on real-time tracking, modular features, and full visibility.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <h3 class="font-semibold text-xl mb-2">Who can use Digital Logistics?</h3>
          <p>Our platform is ideal for businesses of all sizes, from local entrepreneurs to large global organizations seeking smarter logistics solutions.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <h3 class="font-semibold text-xl mb-2">How do I get started?</h3>
          <p>You can easily sign up by filling out our registration form and start exploring all the features available to you!</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-4">What Our Users Say</h2>
      <div class="space-y-6">
        <div class="bg-gray-100 p-6 rounded-lg shadow">
          <p class="italic">"Digital Logistics has transformed the way we handle our deliveries. We can track every shipment in real time, making our operations more efficient than ever!"</p>
          <p class="font-semibold mt-4">John Doe</p>
          <p>CEO, Tech Innovations</p>
        </div>
        <div class="bg-gray-100 p-6 rounded-lg shadow">
          <p class="italic">"The ease of use and the scalability of the platform allowed us to grow our logistics department without added stress. Highly recommend it!"</p>
          <p class="font-semibold mt-4">Jane Smith</p>
          <p>Logistics Manager, Global Goods</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Sign Up Section -->
  <section id="signup" class="py-16 bg-gradient-to-r from-blue-500 to-green-400 text-white text-center">
    <div class="max-w-3xl mx-auto px-4">
      <h2 class="text-3xl font-bold mb-4">Join Us Today!</h2>
      <p class="mb-6">Start using Digital Logistics to streamline your operations. Sign up now to get started.</p>
      <a href="#signup-form" class="bg-white text-blue-600 px-6 py-3 rounded shadow-lg font-semibold">Sign Up</a>
    </div>
  </section>

  <!-- Login Section -->
  <section id="login" class="py-16 bg-gray-100 text-center">
    <div class="max-w-3xl mx-auto px-4">
      <h2 class="text-3xl font-bold mb-4">Already a User? Login</h2>
      <p class="mb-6">Log in to your account and get back to managing your logistics operations.</p>
      <a href="#login-form" class="bg-blue-600 text-white px-6 py-3 rounded shadow-lg font-semibold">Login</a>
    </div>
  </section>

  <script>
    const menuBtn = document.getElementById("menu-btn");
    const mobileMenu = document.getElementById("mobile-menu");
    
    menuBtn.addEventListener("click", () => {
      mobileMenu.classList.toggle("hidden");
    });
  </script>
</body>
</html>
