<template>
  <div class="min-h-screen bg-gray-100 flex justify-center items-center py-10">
    <div
      data-aos="zoom-in"
      class="bg-white rounded-3xl shadow-2xl p-10 max-w-6xl w-full"
    >
      <h1
        data-aos="zoom-in"
        class="text-3xl font-bold text-center text-gray-800 mb-10"
      >
        INFO LOKER
      </h1>

      <!-- Grid container -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 justify-items-center">
        
        <!-- Card 1 -->
        <div class="relative flex flex-col rounded-xl bg-white text-gray-700 shadow-md w-80 hover:shadow-xl transition-all" data-aos="fade-up">
          <div class="aspect-video overflow-hidden rounded-t-xl">
            <img src="/assets/img/uiux.jpeg" alt="UI/UX Designer" class="w-full h-full object-cover hover:scale-110 transition-transform duration-500" />
          </div>
          <div class="p-6 text-center">
            <h5 class="mb-2 text-xl font-semibold text-blue-gray-900">UI/UX Designer</h5>
          </div>
          <div class="p-6 pt-0">
            <NuxtLink
              to="/uiux"
              class="block w-full rounded-lg bg-blue-500 py-3 px-6 text-xs font-bold uppercase text-white text-center shadow-md transition-all hover:bg-blue-600 focus:outline-none"
            >
              Info Lebih Lanjut
            </NuxtLink>
          </div>
        </div>

        <!-- Card 2 -->
        <div class="relative flex flex-col rounded-xl bg-white text-gray-700 shadow-md w-80 hover:shadow-xl transition-all" data-aos="fade-up" data-aos-delay="100">
          <div class="aspect-video overflow-hidden rounded-t-xl">
            <img src="/assets/img/fe.jpg" alt="Front End Developer" class="w-full h-full object-cover hover:scale-110 transition-transform duration-500" />
          </div>
          <div class="p-6 text-center">
            <h5 class="mb-2 text-xl font-semibold text-blue-gray-900">Front End Developer</h5>
          </div>
          <div class="p-6 pt-0">
            <NuxtLink
              to="/fe"
              class="block w-full rounded-lg bg-blue-500 py-3 px-6 text-xs font-bold uppercase text-white text-center shadow-md transition-all hover:bg-blue-600 focus:outline-none"
            >
              Info Lebih Lanjut
            </NuxtLink>
          </div>
        </div>

        <!-- Card 3 -->
        <div class="relative flex flex-col rounded-xl bg-white text-gray-700 shadow-md w-80 hover:shadow-xl transition-all" data-aos="fade-up" data-aos-delay="200">
          <div class="aspect-video overflow-hidden rounded-t-xl">
            <img src="/assets/img/be.jpeg" alt="Back End Developer" class="w-full h-full object-cover hover:scale-110 transition-transform duration-500" />
          </div>
          <div class="p-6 text-center">
            <h5 class="mb-2 text-xl font-semibold text-blue-gray-900">Back End Developer</h5>
          </div>
          <div class="p-6 pt-0">
            <NuxtLink
              to="/be"
              class="block w-full rounded-lg bg-blue-500 py-3 px-6 text-xs font-bold uppercase text-white text-center shadow-md transition-all hover:bg-blue-600 focus:outline-none"
            >
              Info Lebih Lanjut
            </NuxtLink>
          </div>
        </div>

        <!-- Card 4 -->
        <div class="relative flex flex-col rounded-xl bg-white text-gray-700 shadow-md w-80 hover:shadow-xl transition-all" data-aos="fade-up" data-aos-delay="300">
          <div class="aspect-video overflow-hidden rounded-t-xl">
            <img src="/assets/img/full.jpg" alt="Full Stack Developer" class="w-full h-full object-cover hover:scale-110 transition-transform duration-500" />
          </div>
          <div class="p-6 text-center">
            <h5 class="mb-2 text-xl font-semibold text-blue-gray-900">Full Stack Developer</h5>
          </div>
          <div class="p-6 pt-0">
            <NuxtLink
              to="/full"
              class="block w-full rounded-lg bg-blue-500 py-3 px-6 text-xs font-bold uppercase text-white text-center shadow-md transition-all hover:bg-blue-600 focus:outline-none"
            >
              Info Lebih Lanjut
            </NuxtLink>
          </div>
        </div>

        <!-- Card 5 -->
        <div class="relative flex flex-col rounded-xl bg-white text-gray-700 shadow-md w-80 hover:shadow-xl transition-all" data-aos="fade-up" data-aos-delay="400">
          <div class="aspect-video overflow-hidden rounded-t-xl">
            <img src="/assets/img/ml.jpeg" alt="Mobile Developer" class="w-full h-full object-cover hover:scale-110 transition-transform duration-500" />
          </div>
          <div class="p-6 text-center">
            <h5 class="mb-2 text-xl font-semibold text-blue-gray-900">Mobile Developer</h5>
          </div>
          <div class="p-6 pt-0">
            <NuxtLink
              to="/ml"
              class="block w-full rounded-lg bg-blue-500 py-3 px-6 text-xs font-bold uppercase text-white text-center shadow-md transition-all hover:bg-blue-600 focus:outline-none"
            >
              Info Lebih Lanjut
            </NuxtLink>
          </div>
        </div>

        <!-- Card 6 -->
        <div class="relative flex flex-col rounded-xl bg-white text-gray-700 shadow-md w-80 hover:shadow-xl transition-all" data-aos="fade-up" data-aos-delay="500">
          <div class="aspect-video overflow-hidden rounded-t-xl">
            <img src="/assets/img/da.jpg" alt="Data Analyst" class="w-full h-full object-cover hover:scale-110 transition-transform duration-500" />
          </div>
          <div class="p-6 text-center">
            <h5 class="mb-2 text-xl font-semibold text-blue-gray-900">Data Analyst</h5>
          </div>
          <div class="p-6 pt-0">
            <NuxtLink
              to="/da"
              class="block w-full rounded-lg bg-blue-500 py-3 px-6 text-xs font-bold uppercase text-white text-center shadow-md transition-all hover:bg-blue-600 focus:outline-none"
            >
              Info Lebih Lanjut
            </NuxtLink>
          </div>
        </div>

        <!-- Card 7 -->
        <div class="relative flex flex-col rounded-xl bg-white text-gray-700 shadow-md w-80 hover:shadow-xl transition-all" data-aos="fade-up" data-aos-delay="600">
          <div class="aspect-video overflow-hidden rounded-t-xl">
            <img src="/assets/img/cs.webp" alt="Cyber Security" class="w-full h-full object-cover hover:scale-110 transition-transform duration-500" />
          </div>
          <div class="p-6 text-center">
            <h5 class="mb-2 text-xl font-semibold text-blue-gray-900">Cyber Security</h5>
          </div>
          <div class="p-6 pt-0">
            <NuxtLink
              to="/cs"
              class="block w-full rounded-lg bg-blue-500 py-3 px-6 text-xs font-bold uppercase text-white text-center shadow-md transition-all hover:bg-blue-600 focus:outline-none"
            >
              Info Lebih Lanjut
            </NuxtLink>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>
