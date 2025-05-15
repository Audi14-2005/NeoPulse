<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NeoPack - Smart Backpack</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Typing animation */
    .typing {
      border-right: 2px solid white;
      white-space: nowrap;
      overflow: hidden;
      animation: typing 3s steps(40, end), blink 0.75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      from, to { border-color: transparent }
      50% { border-color: white; }
    }

    .shimmer {
      background: linear-gradient(90deg, #f0f0f0 0%, #fafafa 50%, #f0f0f0 100%);
      background-size: 200% 100%;
      animation: shimmer 2s infinite;
    }

    @keyframes shimmer {
      0% { background-position: -200% 0; }
      100% { background-position: 200% 0; }
    }
  </style>
</head>
<body class="bg-gray-950 text-white font-sans tracking-wide leading-relaxed">
  <div class="container mx-auto px-6 py-10">

    <h1 class="text-4xl sm:text-5xl font-bold mb-6 typing text-cyan-400">🎒 NeoPack - IoT-Based Smart Backpack</h1>

    <!-- YouTube Embed -->
    <div class="mb-10">
      <iframe class="w-full h-64 sm:h-96 rounded-xl shadow-2xl" 
              src="https://www.youtube.com/embed/QEiaLV7WJts" 
              title="NeoPack Demo" 
              frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
              allowfullscreen>
      </iframe>
    </div>

    <!-- Abstract -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">🧠 Abstract</h2>
      <p class="mt-2 text-gray-300"> <span class="shimmer px-1">NeoPack</span> is a context-aware IoT Smart Backpack designed to enhance everyday efficiency and security. Whether it's forgetting a book, walking into a rainstorm, or carrying an overloaded bag, NeoPack proactively alerts you before problems arise. It integrates ESP32 microcontrollers, sensors, and mobile connectivity to provide real-time, intelligent feedback—making your backpack smarter than ever.</p>
    </section>

    <!-- Idea -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">💡 The Idea</h2>
      <p class="mt-2 text-gray-300">
        In an era of smart everything, the backpack remains dumb. NeoPack changes that.<br><br>
        This intelligent backpack uses <strong>ESP32-C3 modules mounted in books</strong>, activated via an <strong>EMI-triggered rail system</strong>. These modules broadcast signals verified by an ESP32-S3 in the bag. Combine that with weather forecasting, battery monitoring, and weight detection—and you have a personal assistant strapped to your shoulders.
      </p>
      <p class="mt-4 font-semibold text-cyan-200">NeoPack = Smart Alerts + Organized Packing + Real-Time Monitoring</p>
    </section>

    <!-- Objective -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">🎯 Objective</h2>
      <ul class="mt-2 list-disc list-inside text-gray-300 space-y-1">
        <li>Detect missing books via EMI-triggered ESP32-C3 modules</li>
        <li>Monitor battery levels of electronic devices</li>
        <li>Detect bag overweight conditions</li>
        <li>Provide real-time alerts via a custom mobile app</li>
        <li>Retrieve contextual weather updates</li>
      </ul>
    </section>

    <!-- Problems -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">🔍 Problems with Traditional Backpacks</h2>
      <ul class="mt-2 list-disc list-inside text-red-400 space-y-1">
        <li>No way to verify packed books or items</li>
        <li>Unaware of weather—no reminders to carry umbrella</li>
        <li>No alerts for low battery levels of devices</li>
        <li>Overweight bags without feedback</li>
        <li>No interaction or alerts via mobile</li>
      </ul>
    </section>

    <!-- Solution -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">✅ Our Solution – NeoPack</h2>
      <ul class="mt-2 list-disc list-inside text-green-300 space-y-1">
        <li>📚 EMI-triggered ESP32-C3 modules in books</li>
        <li>📡 Live weather updates with umbrella reminders</li>
        <li>🔋 Battery level tracking and alerts</li>
        <li>⚖️ Load detection with weight sensor</li>
        <li>📱 Mobile app integration for smart alerts</li>
      </ul>
    </section>

    <!-- Key Features -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">🔑 Key Features</h2>
      <div class="mt-2 text-gray-300 space-y-4">
        <p><strong>1. 📚 Smart Book Tracking</strong><br>No NFC! Each book has an ESP32-C3 activated via a custom EMI-trigger rail. ESP32-S3 inside the bag checks for missing books.</p>
        <p><strong>2. 🌧️ Weather-Based Alerts</strong><br>Real-time weather forecast alerts and umbrella reminders.</p>
        <p><strong>3. 🔋 Battery Monitoring</strong><br>Tracks charge of internal devices and sends mobile alerts.</p>
        <p><strong>4. ⚖️ Load Detection</strong><br>Load sensor monitors weight and prevents ergonomic issues.</p>
        <p><strong>5. 📲 NeoPulse App</strong><br>Real-time sync dashboard with alerts for books, weather, battery, and weight.</p>
      </div>
    </section>

    <!-- Hardware -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">🛠 Hardware Components</h2>
      <ul class="mt-2 list-disc list-inside text-gray-300 space-y-1">
        <li>ESP32-S3 microcontroller (main controller)</li>
        <li>ESP32-C3 modules (per book)</li>
        <li>EMI power rail</li>
        <li>Load sensor</li>
        <li>Battery monitor</li>
        <li>Haptic motors + LED indicators</li>
      </ul>
    </section>

    <!-- Software -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">💻 Software Components</h2>
      <ul class="mt-2 list-disc list-inside text-gray-300 space-y-1">
        <li>NeoPulse Mobile App (Dark/Light mode)</li>
        <li>Supabase for cloud sync & offline use</li>
        <li>REST APIs for ESP32 ↔ App communication</li>
        <li>Weather API integration</li>
        <li>SHA256-based secure communication</li>
      </ul>
    </section>

    <!-- App Screens -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">📱 NeoPulse App Screens</h2>
      <ul class="mt-2 list-disc list-inside text-gray-300 space-y-1">
        <li><strong>Home</strong>: System overview & alerts</li>
        <li><strong>Books</strong>: Track packed items in real time</li>
        <li><strong>Weather</strong>: Forecasts + umbrella reminders</li>
        <li><strong>Battery</strong>: Monitor connected device levels</li>
        <li><strong>Settings</strong>: Theme toggles + preferences</li>
      </ul>
    </section>

    <!-- Authors -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">👥 Authors</h2>
      <ul class="mt-2 list-disc list-inside text-gray-300 space-y-1">
        <li><strong>Manoharan K</strong> – 230701177</li>
        <li><strong>Monic Auditya A</strong> – 230701194</li>
        <li><strong>Monish D Y</strong> – 230701195</li>
      </ul>
    </section>

    <!-- License -->
    <section class="mb-10">
      <h2 class="text-2xl font-bold text-cyan-300">📌 License</h2>
      <p class="mt-2 text-gray-300">This project is for academic demonstration. Licensing will be defined for production versions.</p>
    </section>

    <blockquote class="italic text-lg text-purple-300 mt-10 border-l-4 border-purple-400 pl-4">
      "Not just smart. Context-aware. Mission-ready. That’s <strong>NeoPack</strong>."
    </blockquote>
  </div>
</body>
</html>
