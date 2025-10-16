<template>
  <div class="min-h-screen bg-gray-100 flex justify-center items-center py-10">
    <div
      class="relative w-full max-w-6xl overflow-hidden rounded-3xl shadow-2xl bg-white mx-4 p-6 sm:p-10"
    >
      <!-- Wrapper -->
      <div
        class="flex transition-transform duration-700 ease-in-out"
        :style="{ transform: `translateX(-${index * 100}%)` }"
      >
        <!-- Slide 1 -->
        <div data-aos="zoom-in" class="w-full flex-shrink-0 flex justify-center p-6 sm:p-10">
          <div
            class="bg-gray-50 shadow-inner rounded-2xl p-6 sm:p-10 w-full sm:w-[32rem] min-h-[24rem] sm:min-h-[26rem]"
          >
            <div
              class="flex items-start space-x-3 sm:space-x-4 text-gray-800 text-xl sm:text-2xl font-semibold mb-4"
            >
              <h2 class="flex-shrink-0">1.</h2>
              <h2 class="leading-snug text-base sm:text-lg">
                Login ke website resmi Unper
              </h2>
            </div>
            <p class="text-gray-600 mb-6 text-base sm:text-lg break-all">
              https://pmb.unper.ac.id/login
            </p>
            <NuxtLink to="https://pmb.unper.ac.id/login" target="_blank">
              <button
                class="px-6 py-3 bg-blue-600 text-white rounded-lg hover:bg-blue-700 text-base sm:text-lg w-full"
              >
                Lihat Detail
              </button>
            </NuxtLink>
          </div>
        </div>

        <!-- Slide 2 -->
        <div class="w-full flex-shrink-0 flex justify-center p-6 sm:p-10">
          <div
            class="bg-gray-50 shadow-inner rounded-2xl p-6 sm:p-10 w-full sm:w-[32rem] min-h-[24rem] sm:min-h-[26rem]"
          >
            <div
              class="flex items-start space-x-3 sm:space-x-4 text-gray-800 text-xl sm:text-2xl font-semibold mb-4"
            >
              <h2 class="flex-shrink-0">2.</h2>
              <h2 class="leading-snug text-base sm:text-lg">
                Setelah login lalu pilih Menu KEUANGAN
              </h2>
            </div>
            <p class="text-gray-600 mb-6 text-base sm:text-lg">
              lalu ke HISTORY PEMBAYARAN, kemudian pilih Tahun Akademik dan klik
              tombol CARI warna BIRU.
            </p>
          </div>
        </div>

        <!-- Slide 3 -->
        <div class="w-full flex-shrink-0 flex justify-center p-6 sm:p-10">
          <div
            class="bg-gray-50 shadow-inner rounded-2xl p-6 sm:p-10 w-full sm:w-[32rem] min-h-[24rem] sm:min-h-[26rem]"
          >
            <div
              class="flex items-start space-x-3 sm:space-x-4 text-gray-800 text-xl sm:text-2xl font-semibold mb-4"
            >
              <h2 class="flex-shrink-0">3.</h2>
              <h2 class="leading-snug text-base sm:text-lg">
                Setelah itu akan muncul data sejarah pembayaran mahasiswa
              </h2>
            </div>
            <p class="text-gray-600 mb-6 text-base sm:text-lg">
              Untuk melakukan pembayaran silahkan klik kotak kecil di bawah
              tulisan PILIH BIAYA, lalu klik tombol warna MERAH PROSES BIAYA KE
              BANK.
            </p>
          </div>
        </div>

        <!-- Slide 4 -->
        <div class="w-full flex-shrink-0 flex justify-center p-6 sm:p-10">
          <div
            class="bg-gray-50 shadow-inner rounded-2xl p-6 sm:p-10 w-full sm:w-[32rem] min-h-[24rem] sm:min-h-[26rem]"
          >
            <div
              class="flex items-start space-x-3 sm:space-x-4 text-gray-800 text-xl sm:text-2xl font-semibold mb-4"
            >
              <h2 class="flex-shrink-0">4.</h2>
              <h2 class="leading-snug text-base sm:text-lg">
                Setelah klik proses biaya ke bank
              </h2>
            </div>
            <p class="text-gray-600 mb-6 text-base sm:text-lg">
              Setelah klik, sistem akan memunculkan total biaya yang harus
              dibayar. Pastikan data sesuai sebelum melanjutkan ke pembayaran.
            </p>
          </div>
        </div>

        <!-- Slide 5 -->
        <div class="w-full flex-shrink-0 flex justify-center p-6 sm:p-10">
          <div
            class="bg-gray-50 shadow-inner rounded-2xl p-6 sm:p-10 w-full sm:w-[32rem] min-h-[24rem] sm:min-h-[26rem]"
          >
            <div
              class="flex items-start space-x-3 sm:space-x-4 text-gray-800 text-xl sm:text-2xl font-semibold mb-4"
            >
              <h2 class="flex-shrink-0">5.</h2>
              <h2 class="leading-snug text-base sm:text-lg">
                Silahkan lakukan transaksi pembayaran
              </h2>
            </div>
            <p class="text-gray-600 mb-6 text-base sm:text-lg">
              Transaksi pembayaran dapat dilakukan melalui Teller, ATM, atau
              Mobile Banking menggunakan Virtual Account BNI yang tertera.
            </p>
          </div>
        </div>
      </div>

      <!-- Indicators -->
      <div
        class="absolute bottom-24 left-1/2 transform -translate-x-1/2 flex space-x-2"
      >
        <button
          v-for="(slide, i) in total"
          :key="i"
          @click="showSlide(i)"
          class="w-3 h-3 sm:w-4 sm:h-4 rounded-full"
          :class="i === index ? 'bg-gray-800' : 'bg-gray-400 hover:bg-gray-600'"
        ></button>
      </div>

      <!-- Controls -->
      <button
        v-if="index > 0"
        class="absolute top-1/2 left-3 sm:left-6 transform -translate-y-1/2 bg-gray-800/70 hover:bg-gray-800 text-white rounded-full p-2 sm:p-3"
        @click="prev"
      >
        &#10094;
      </button>

      <button
        v-if="index < total - 1"
        class="absolute top-1/2 right-3 sm:right-6 transform -translate-y-1/2 bg-gray-800/70 hover:bg-gray-800 text-white rounded-full p-2 sm:p-3"
        @click="next"
      >
        &#10095;
      </button>

      <!-- Tombol Fixed di bawah -->
      <div
        class="fixed left-1/2 transform -translate-x-1/2 bottom-8 flex space-x-4 bg-white/80 backdrop-blur-md px-6 py-4 rounded-2xl shadow-lg"
      >
        <NuxtLink to="/">
          <button
            class="px-6 py-3 bg-green-600 text-white rounded-lg hover:bg-green-700 text-base sm:text-lg"
          >
            KEMBALI
          </button>
        </NuxtLink>

        <NuxtLink to="/krs">
          <button
            class="px-6 py-3 bg-green-600 text-white rounded-lg hover:bg-green-700 text-base sm:text-lg"
          >
            KONTRAK KRS
          </button>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
import { useRouter } from "vue-router";

const index = ref(0);
const total = 5;
const router = useRouter();

function showSlide(i) {
  if (i >= 0 && i < total) index.value = i;
}
function next() {
  if (index.value < total - 1) index.value++;
}
function prev() {
  if (index.value > 0) index.value--;
}
function goBack() {
  router.back();
}
</script>
