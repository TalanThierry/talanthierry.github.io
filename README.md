# talanthierry.github.io
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Clean Water Project</title>
    <!-- Tailwind CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body class="font-sans text-gray-900">
    <!-- Hero Section -->
    <section class="relative bg-blue-600 text-white py-24 px-6 text-center">
      <h1 class="text-4xl md:text-6xl font-bold mb-6">
        Bringing Clean Water to Every Community
      </h1>
      <p class="text-lg md:text-xl max-w-2xl mx-auto mb-8">
        Together, we can transform lives through safe water, empower
        communities, and inspire the next generation of changemakers.
      </p>
      <a
        href="#donate"
        class="bg-white text-blue-600 font-semibold px-6 py-3 rounded-2xl shadow hover:bg-gray-100 transition"
      >
        Join the Mission
      </a>
    </section>

    <!-- Value Proposition Section -->
    <section class="py-16 px-6 max-w-6xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">
        Our Value Proposition
      </h2>
      <div class="grid md:grid-cols-3 gap-8">
        <!-- Card 1 -->
        <div
          class="bg-white rounded-2xl shadow-md overflow-hidden hover:shadow-xl transition"
        >
          <img
            src="https://placehold.co/400x250?text=Clean+Water"
            alt="Access to Clean Water"
            class="w-full h-48 object-cover"
          />
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Access to Clean Water</h3>
            <p class="text-gray-600">
              Every drop transforms health, education, and opportunity.
            </p>
          </div>
        </div>
        <!-- Card 2 -->
        <div
          class="bg-white rounded-2xl shadow-md overflow-hidden hover:shadow-xl transition"
        >
          <img
            src="https://placehold.co/400x250?text=Community"
            alt="Community Empowerment"
            class="w-full h-48 object-cover"
          />
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Community Empowerment</h3>
            <p class="text-gray-600">
              Your support builds lasting infrastructure and hope.
            </p>
          </div>
        </div>
        <!-- Card 3 -->
        <div
          class="bg-white rounded-2xl shadow-md overflow-hidden hover:shadow-xl transition"
        >
          <img
            src="https://placehold.co/400x250?text=Leaders"
            alt="Next Generation Leaders"
            class="w-full h-48 object-cover"
          />
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Next Generation Leaders</h3>
            <p class="text-gray-600">
              Inspiring young changemakers to carry the mission forward.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Call to Action -->
    <section
      id="donate"
      class="bg-yellow-400 py-20 px-6 text-center rounded-t-3xl"
    >
      <h2 class="text-3xl md:text-4xl font-bold mb-4 text-gray-900">
        Be the Change Today
      </h2>
      <p class="text-lg mb-6 max-w-2xl mx-auto text-gray-800">
        Your support brings hope, health, and opportunity. Donate now and create
        a ripple of change that lasts for generations.
      </p>
      <a
        href="#"
        class="bg-gray-900 text-white px-6 py-3 rounded-2xl shadow hover:bg-gray-800 transition"
      >
        Donate Now
      </a>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-300 py-8 px-6 text-center mt-12">
      <p class="mb-4">
        &copy; <span id="year"></span> Clean Water Project. All rights reserved.
      </p>
      <nav class="space-x-4">
        <a href="#about" class="hover:text-white">About</a>
        <a href="#projects" class="hover:text-white">Projects</a>
        <a href="#contact" class="hover:text-white">Contact</a>
      </nav>
    </footer>

    <script>
      // Auto-update year in footer
      document.getElementById("year").textContent = new Date().getFullYear();
    </script>
  </body>
</html>
