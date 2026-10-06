<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>College Event Invitation</title>

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-slate-100 text-slate-800">

  <!-- Hero Section -->
  <section class="min-h-screen flex items-center justify-center bg-gradient-to-br from-indigo-700 via-purple-700 to-pink-600 px-6 py-16">

    <div class="max-w-5xl w-full text-center text-white">

      <!-- College Name -->
      <p class="uppercase tracking-[0.3em] text-sm font-semibold text-indigo-200 mb-4">
        ABC College of Engineering
      </p>

      <!-- Event Title -->
      <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight mb-6">
        TechFest 2026
      </h1>

      <p class="max-w-2xl mx-auto text-lg md:text-xl text-purple-100 leading-relaxed mb-10">
        You are cordially invited to our annual college technology festival
        featuring innovation, creativity, competitions, and inspiring speakers.
      </p>

      <!-- Event Date -->
      <div class="inline-block bg-white/10 backdrop-blur-md border border-white/30 rounded-2xl px-8 py-5 mb-10 shadow-xl">
        <p class="text-sm uppercase tracking-widest text-purple-200">
          Save the Date
        </p>

        <p class="text-2xl md:text-3xl font-bold mt-2">
          20 – 22 November 2026
        </p>

        <p class="text-purple-100 mt-1">
          College Auditorium, ABC College
        </p>
      </div>

      <!-- Buttons -->
      <div class="flex flex-col sm:flex-row justify-center gap-4">

        <a
          href="#register"
          class="bg-white text-indigo-700 font-bold px-8 py-3 rounded-full shadow-lg
                 hover:bg-indigo-50 hover:scale-105 transition duration-300"
        >
          Register Now
        </a>

        <a
          href="#details"
          class="border-2 border-white text-white font-semibold px-8 py-3 rounded-full
                 hover:bg-white hover:text-indigo-700 transition duration-300"
        >
          View Details
        </a>

      </div>
    </div>
  </section>


  <!-- Event Details -->
  <section id="details" class="py-20 px-6 bg-white">

    <div class="max-w-6xl mx-auto">

      <div class="text-center mb-12">
        <p class="text-indigo-600 font-semibold uppercase tracking-widest">
          What's Happening
        </p>

        <h2 class="text-4xl font-bold text-slate-900 mt-2">
          Event Highlights
        </h2>

        <p class="text-slate-500 mt-4 max-w-2xl mx-auto">
          Experience three exciting days filled with technology, learning,
          entertainment, and unforgettable college memories.
        </p>
      </div>


      <!-- Highlight Cards -->
      <div class="grid md:grid-cols-3 gap-8">

        <div class="p-8 bg-slate-50 border border-slate-200 rounded-2xl
                    hover:-translate-y-2 hover:shadow-xl transition duration-300">

          <div class="w-14 h-14 flex items-center justify-center
                      rounded-xl bg-indigo-100 text-2xl mb-5">
            💻
          </div>

          <h3 class="text-xl font-bold mb-3">
            Coding Competition
          </h3>

          <p class="text-slate-600 leading-relaxed">
            Test your programming skills and compete with talented students
            from different colleges.
          </p>
        </div>


        <div class="p-8 bg-slate-50 border border-slate-200 rounded-2xl
                    hover:-translate-y-2 hover:shadow-xl transition duration-300">

          <div class="w-14 h-14 flex items-center justify-center
                      rounded-xl bg-purple-100 text-2xl mb-5">
            🚀
          </div>

          <h3 class="text-xl font-bold mb-3">
            Innovation Expo
          </h3>

          <p class="text-slate-600 leading-relaxed">
            Explore creative student projects, innovative ideas, and
            emerging technologies.
          </p>
        </div>


        <div class="p-8 bg-slate-50 border border-slate-200 rounded-2xl
                    hover:-translate-y-2 hover:shadow-xl transition duration-300">

          <div class="w-14 h-14 flex items-center justify-center
                      rounded-xl bg-pink-100 text-2xl mb-5">
            🎤
          </div>

          <h3 class="text-xl font-bold mb-3">
            Guest Speakers
          </h3>

          <p class="text-slate-600 leading-relaxed">
            Learn from industry experts and successful professionals through
            inspiring talks and interactive sessions.
          </p>
        </div>

      </div>
    </div>
  </section>


  <!-- Schedule -->
  <section class="py-20 px-6 bg-slate-100">

    <div class="max-w-4xl mx-auto">

      <div class="text-center mb-12">
        <p class="text-indigo-600 font-semibold uppercase tracking-widest">
          Event Schedule
        </p>

        <h2 class="text-4xl font-bold text-slate-900 mt-2">
          Three Days of Excitement
        </h2>
      </div>


      <div class="space-y-6">

        <!-- Day 1 -->
        <div class="bg-white border-l-4 border-indigo-600
                    rounded-xl p-6 shadow-sm">

          <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-4">

            <div>
              <p class="text-indigo-600 font-bold">
                Day 01 • 20 November
              </p>

              <h3 class="text-xl font-bold mt-1">
                Opening Ceremony & Coding Challenge
              </h3>
            </div>

            <span class="bg-indigo-100 text-indigo-700
                         px-4 py-2 rounded-full font-semibold">
              10:00 AM
            </span>

          </div>
        </div>


        <!-- Day 2 -->
        <div class="bg-white border-l-4 border-purple-600
                    rounded-xl p-6 shadow-sm">

          <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-4">

            <div>
              <p class="text-purple-600 font-bold">
                Day 02 • 21 November
              </p>

              <h3 class="text-xl font-bold mt-1">
                Innovation Expo & Guest Lectures
              </h3>
            </div>

            <span class="bg-purple-100 text-purple-700
                         px-4 py-2 rounded-full font-semibold">
              11:00 AM
            </span>

          </div>
        </div>


        <!-- Day 3 -->
        <div class="bg-white border-l-4 border-pink-600
                    rounded-xl p-6 shadow-sm">

          <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-4">

            <div>
              <p class="text-pink-600 font-bold">
                Day 03 • 22 November
              </p>

              <h3 class="text-xl font-bold mt-1">
                Cultural Night & Prize Distribution
              </h3>
            </div>

            <span class="bg-pink-100 text-pink-700
                         px-4 py-2 rounded-full font-semibold">
              5:00 PM
            </span>

          </div>
        </div>

      </div>
    </div>
  </section>


  <!-- Invitation / Registration -->
  <section id="register"
           class="py-20 px-6 bg-gradient-to-r from-indigo-700 to-purple-700">

    <div class="max-w-3xl mx-auto text-center text-white">

      <p class="uppercase tracking-[0.25em] text-indigo-200 font-semibold">
        You're Invited
      </p>

      <h2 class="text-4xl md:text-5xl font-extrabold mt-3 mb-6">
        Be Part of the Experience!
      </h2>

      <p class="text-lg text-indigo-100 leading-relaxed mb-8">
        Gather your friends, showcase your talent, learn something new,
        and make memories that will last a lifetime.
      </p>

      <a
        href="#"
        class="inline-block bg-white text-indigo-700
               font-bold px-10 py-4 rounded-full
               shadow-xl hover:bg-indigo-50
               hover:scale-105 transition duration-300"
      >
        🎟 Register for TechFest
      </a>

    </div>
  </section>


  <!-- Footer -->
  <footer class="bg-slate-950 text-slate-400 py-8 px-6 text-center">

    <h3 class="text-white font-bold text-lg">
      ABC College of Engineering
    </h3>

    <p class="mt-2 text-sm">
      Department of Computer Science & Engineering
    </p>

    <p class="mt-4 text-sm">
      © 2026 TechFest. All Rights Reserved.
    </p>

  </footer>

</body>
</html>
