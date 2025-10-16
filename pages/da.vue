<template>
  <div
    class="min-h-screen bg-gray-100 flex flex-col items-center justify-center py-14 relative"
  >
    <!-- Grid container -->
    <div
      class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-2 gap-x-12 gap-y-10 justify-center w-full max-w-7xl px-6"
    >
      <!-- Card 1 -->
      <div
        data-aos="fade-up"
        class="flex flex-col sm:flex-row bg-white rounded-2xl shadow-md overflow-hidden w-full sm:w-[600px]"
      >
        <!-- Kiri -->
        <div
          class="sm:w-[220px] bg-[#261a6b] text-white p-6 flex flex-col justify-center rounded-t-2xl sm:rounded-l-2xl sm:rounded-tr-none"
        >
          <h4 class="text-[11px] tracking-widest text-[#ccc] uppercase">
            Data Analis
          </h4>
          <h1 class="text-[22px] font-semibold leading-[25px] pt-3">
            PT. Trust Recruit Indonesia
          </h1>
        </div>

        <!-- Kanan -->
        <div class="flex-1 p-6 text-gray-700 text-[15px] leading-relaxed">
          <h1 class="font-semibold text-gray-800 text-[17px] mb-3">
            📍 Jakarta
          </h1>
          <p>
            <span class="font-semibold text-gray-900">💡 Skill:</span>
            Deep learning, tensorflow, pytorch, dan generate AI
          </p>
          <p>
            <span class="font-semibold text-gray-900">⏰ Waktu Kerja:</span>
            Full Time
          </p>
          <p>
            <span class="font-semibold text-gray-900">🎓 Pendidikan:</span
            >Sarjana atau magister
          </p>
          <p>
            <span class="font-semibold text-gray-900">💰 Gaji:</span> Rp
            7.500.000 - Rp 11.500.000
          </p>
        </div>
      </div>

      <!-- Card 2 -->
      <div
        data-aos="fade-up"
        data-aos-delay="150"
        class="flex flex-col sm:flex-row bg-white rounded-2xl shadow-md overflow-hidden w-full sm:w-[600px]"
      >
        <div
          class="sm:w-[220px] bg-[#261a6b] text-white p-6 flex flex-col justify-center rounded-t-2xl sm:rounded-l-2xl sm:rounded-tr-none"
        >
          <h4 class="text-[11px] tracking-widest text-[#ccc] uppercase">
            Data Analis
          </h4>
          <h1 class="text-[22px] font-semibold leading-[25px] pt-3">
            PT.Ihsan Informatika(bandung)
          </h1>
        </div>

        <div class="flex-1 p-6 text-gray-700 text-[15px] leading-relaxed">
          <h1 class="font-semibold text-gray-800 text-[17px] mb-3">
            📍 Bandung
          </h1>
          <p>
            <span class="font-semibold text-gray-900">💡 Skill:</span>HTML,CSS,
            ETL:ODI, data stage, talend
          </p>
          <p>
            <span class="font-semibold text-gray-900">⏰ Waktu Kerja:</span>
            FULL TIME
          </p>
          <p>
            <span class="font-semibold text-gray-900">🎓 Pendidikan:</span>D3
          </p>
          <p>
            <span class="font-semibold text-gray-900">💰 Gaji:</span> Rp
            7.000.000 - Rp 10.000.000
          </p>
        </div>
      </div>

      <!-- Card 3 -->
      <div
        data-aos="fade-up"
        data-aos-delay="300"
        class="flex flex-col sm:flex-row bg-white rounded-2xl shadow-md overflow-hidden w-full sm:w-[600px] md:col-span-2 justify-self-center"
      >
        <div
          class="sm:w-[220px] bg-[#261a6b] text-white p-6 flex flex-col justify-center rounded-t-2xl sm:rounded-l-2xl sm:rounded-tr-none"
        >
          <h4 class="text-[11px] tracking-widest text-[#ccc] uppercase">
            Data Analis
          </h4>
          <h1 class="text-[22px] font-semibold leading-[25px] pt-3">
            PT.Delta Sukses Teknologi
          </h1>
        </div>

        <div class="flex-1 p-6 text-gray-700 text-[15px] leading-relaxed">
          <h1 class="font-semibold text-gray-800 text-[17px] mb-3">
            📍 Jakarta
          </h1>
          <p>
            <span class="font-semibold text-gray-900">💡 Skill:</span> Microsoft
            visio
          </p>
          <p>
            <span class="font-semibold text-gray-900">⏰ Waktu Kerja:</span>
            FULL TIME
          </p>
          <p>
            <span class="font-semibold text-gray-900">🎓 Pendidikan:</span>s1
          </p>
          <p>
            <span class="font-semibold text-gray-900">💰 Gaji:</span> Rp
            10.000.000 - Rp 15.000.000
          </p>
        </div>
      </div>
    </div>

    <!-- Tombol kembali -->
    <NuxtLink
      to="/"
      class="fixed bottom-8 right-10 bg-[#261a6b] text-white px-6 py-2 rounded-full font-medium shadow-md"
    >
      ← Kembali ke Menu
    </NuxtLink>
  </div>
</template>
