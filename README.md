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

  <!-- Signup Section -->
  <section id="signup" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4 grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
      <div>
        <h2 class="text-3xl font-bold mb-4">Start Your First Delivery</h2>
        <form class="space-y-4">
          <div>
            <label for="email" class="block mb-1 font-medium">Email</label>
            <input type="email" id="email" class="w-full border rounded px-3 py-2" placeholder="you@example.com" />
          </div>
          <div>
            <label for="phone" class="block mb-1 font-medium">Phone</label>
            <input type="tel" id="phone" class="w-full border rounded px-3 py-2" placeholder="+227 88 47 09 07" />
          </div>
          <button class="bg-blue-600 text-white px-5 py-3 rounded w-full font-semibold">Sign Up</button>
        </form>
      </div>
      <img src="delivery-illustration.png" alt="Delivery Illustration" class="w-full h-auto hidden md:block" />
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-gray-200 py-6">
    <div class="max-w-6xl mx-auto px-4 flex flex-col md:flex-row justify-between items-center">
      <p>&copy; 2025 Digital Logistics. All rights reserved.</p>
      <div class="space-x-4 mt-4 md:mt-0">
        <a href="#" class="hover:underline">Privacy</a>
        <a href="#" class="hover:underline">Terms</a>
        <a href="#" class="hover:underline">Contact</a>
      </div>
    </div>
  </footer>

  <!-- JavaScript -->
  <script>
    document.addEventListener('DOMContentLoaded', () => {
      const btn = document.getElementById('menu-btn');
      const menu = document.getElementById('mobile-menu');
      btn.addEventListener('click', () => {
        menu.classList.toggle('hidden');
      });
    });
  </script>
</body>
</html>
