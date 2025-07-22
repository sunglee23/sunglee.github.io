<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sung Lee | UX Content Strategist & Federal Systems Analyst</title>
  <meta name="description" content="Sung Lee - Business Analyst and Technical Writer for Federal UX transformation programs (IRS, DoD). Explore resume, projects, and contact details.">
  <meta property="og:title" content="Sung Lee | UX Content Strategist" />
  <meta property="og:description" content="Digital strategy meets federal IT. Explore Sung’s portfolio and federal work experience." />
  <meta property="og:image" content="https://sunglee23.github.io/og-image.jpg" />
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/alpinejs" defer></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
    .glass {
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(10px);
    }
    .typing::after {
      content: "|";
      animation: blink 1s step-end infinite;
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans" onload="AOS.init();">

  <!-- Navbar -->
  <nav class="fixed w-full z-30 glass shadow-lg">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Sung Lee</h1>
      <div class="space-x-4">
        <a href="#about" class="hover:text-blue-400">About</a>
        <a href="#projects" class="hover:text-blue-400">Projects</a>
        <a href="#resume" class="hover:text-blue-400">Resume</a>
        <a href="#contact" class="hover:text-blue-400">Contact</a>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="h-screen flex items-center justify-center text-center bg-gradient-to-br from-gray-800 to-black pt-24">
    <div>
      <h2 class="text-4xl sm:text-6xl font-extrabold">
        Hi, I’m <span class="text-blue-400">Sung Lee</span>
      </h2>
      <p class="text-xl text-gray-300 mt-4 typing">UX Strategy. Agile Delivery. Federal Systems.</p>
      <div class="mt-6 space-x-4">
        <a href="/Sung_Lee_Resume_BA_TECH_7-2025.pdf" target="_blank" class="bg-blue-500 px-5 py-2 rounded-lg font-semibold hover:bg-blue-600">View Resume</a>
        <a href="mailto:sung.m.lee23@gmail.com" class="bg-gray-700 px-5 py-2 rounded-lg font-semibold hover:bg-gray-600">Email Me</a>
        <a href="https://www.linkedin.com/in/sungmlee" target="_blank" class="bg-white text-black px-5 py-2 rounded-lg font-semibold hover:bg-gray-300">LinkedIn</a>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20 px-8 max-w-4xl mx-auto" data-aos="fade-up">
    <h2 class="text-3xl font-bold text-blue-400 mb-4">About Me</h2>
    <p class="text-lg text-gray-300 leading-relaxed">
      I'm a clearance-ready Technical Writer and Business Analyst with 5+ years driving digital modernization for federal clients including the IRS and DoD. I specialize in translating mission needs into human-centered experiences through Agile delivery, 508 compliance, and Power Platform solutions.
    </p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="py-20 px-8 bg-gray-800" data-aos="fade-up">
    <h2 class="text-3xl font-bold text-blue-400 mb-10 text-center">Featured Projects</h2>
    <div class="grid md:grid-cols-2 gap-8">
      <div class="bg-gray-700 p-6 rounded-2xl shadow-xl transform hover:scale-105 transition-all">
        <h3 class="text-xl font-semibold mb-2">IRS Power Apps Manual</h3>
        <p class="text-gray-300 mb-4">End-to-end training manual for the IRS Enterprise Front Door, with 508-compliant visuals and user flows.</p>
        <a href="#" class="text-blue-300 underline">View Project</a>
      </div>
      <div class="bg-gray-700 p-6 rounded-2xl shadow-xl transform hover:scale-105 transition-all">
        <h3 class="text-xl font-semibold mb-2">Proposal Content System</h3>
        <p class="text-gray-300 mb-4">Created a standardized content system for federal proposals across multiple agencies, improving win rates and clarity.</p>
        <a href="#" class="text-blue-300 underline">View Project</a>
      </div>
    </div>
  </section>

  <!-- Resume Section -->
  <section id="resume" class="py-20 px-8 max-w-5xl mx-auto" data-aos="fade-up">
    <h2 class="text-3xl font-bold text-blue-400 mb-6">Resume Snapshot</h2>
    <div class="grid sm:grid-cols-2 gap-6 text-gray-300">
      <div>
        <p><strong>📊 Business Analysis</strong>: Agile, process mapping, requirements lifecycle</p>
        <p><strong>✍️ Technical Writing</strong>: SOPs, release notes, training manuals</p>
        <p><strong>🧭 UX Strategy</strong>: Content models, IA, 508 alignment</p>
      </div>
      <div>
        <iframe src="/Sung_Lee_Resume_BA_TECH_7-2025.pdf" width="100%" height="300px" class="rounded-xl shadow-lg"></iframe>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 px-8 bg-gray-800" data-aos="fade-up">
    <h2 class="text-3xl font-bold text-blue-400 mb-6">Let’s Connect</h2>
    <p class="text-gray-300 mb-2">📧 Email: <a href="mailto:sung.m.lee23@gmail.com" class="underline">sung.m.lee23@gmail.com</a></p>
    <p class="text-gray-300 mb-2">📱 Phone: <a href="tel:+14103652179" class="underline">(410) 365-2179</a></p>
    <p class="text-gray-300">🔗 LinkedIn: <a href="https://www.linkedin.com/in/sungmlee" target="_blank" class="underline">linkedin.com/in/sungmlee</a></p>
  </section>

  <!-- Footer -->
  <footer class="text-center text-gray-500 py-6 text-sm">
    © 2025 Sung Lee. Built with 💙, TailwindCSS, and AOS.js.
  </footer>

  <script>
    AOS.init();
  </script>
</body>
</html>
