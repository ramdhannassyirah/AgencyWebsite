<script setup>
// import { RouterLink } from 'vue-router'
import CardP from '@/components/CardP.vue'
import CardH from '@/components/CardH.vue'
import CardPr from '@/components/CardProduct.vue'
import CardTesti from '@/components/CardTesti.vue'
</script>

<template>
  <div class="container mx-auto text-white">
    <header class="pt-10 bg-[url('@/assets/img/hero.jpg')] h-[700px] mx-auto">
      <nav class="flex justify-between mx-10">
        <div class="">
          <h1>Logo</h1>
        </div>
        <div class="hidden sm:block">
          <div class="space-x-2">
            <a href="">About</a>
            <a href="">Services</a>
            <a href="">Portfolio</a>
            <a href="">Contact Us</a>
          </div>
        </div>
        <div class="">
          <a class="px-4 py-2 font-semibold border rounded-full"> Get Start </a>
        </div>
      </nav>
      <div class="flex flex-col items-center my-[60px] space-y-5 mt-[100px]">
        <div class="flex space-x-4">
          <font-awesome-icon icon="fa-brands fa-instagram" size="xl" />
          <font-awesome-icon icon="fa-brands fa-twitter" size="xl" />
          <font-awesome-icon icon="fa-brands fa-linkedin-in" size="xl" />
          <font-awesome-icon icon="fa-brands fa-whatsapp" size="xl" />
        </div>
        <div class="space-y-3">
          <h1 class="text-3xl font-semibold text-center sm:text-6xl">
            Amazing website creation with agency
          </h1>
          <p class="text-sm text-center">
            help you to build website company that is modern, user friendly, good CEO, and Clean
            design
          </p>
        </div>
        <div class="">
          <button
            class="flex justify-around px-6 py-1 font-semibold text-black bg-white rounded-full sm:px-6 btn"
          >
            Get Start
            <span class="pl-2">
              <font-awesome-icon icon="fa-solid fa-arrow-right" />
            </span>
          </button>
        </div>
        <!-- <img class="absolute" src="@/assets/img/hero.jpg" alt="" /> -->
      </div>
    </header>
    <section class="px-2 sm:px-10 sm:mt-[140px] mt-[40px]">
      <div class="flex flex-col justify-center sm:space-y-8">
        <h1 class="text-3xl sm:text-6xl">
          Companies that can help you in
          <span
            class="px-4 py-1 text-base font-semibold text-center text-black bg-white rounded-full sm:py-2 sm:px-6 btn"
            >Know More
            <span class="pl-2"> <font-awesome-icon icon="fa-solid fa-arrow-right" /> </span></span
          ><br />
          developing your company for the future
        </h1>
        <p class="mt-3 text-xs sm:text-xl">
          Work in the IT field includes Web Design, UI/UX Design, Branding <br />
          and Shopify Development
        </p>
      </div>
    </section>
    <section class="sm:mt-[140px] mt-10 sm:px-10 px-2">
      <div class="flex flex-wrap items-end justify-between space-y-3">
        <div class="flex flex-col justify-center space-y-2">
          <h1 class="text-3xl sm:text-6xl">Let’s work together with our us</h1>
          <p class="text-xs sm:text-xl">
            help you to build website company that is modern, user friendly, good CEO, <br />
            and Clean design
          </p>
        </div>
        <div class="">
          <button class="px-4 py-1 font-semibold text-black bg-white rounded-full btn">
            Get Start
            <span class="pl-2">
              <font-awesome-icon icon="fa-solid fa-arrow-right" />
            </span>
          </button>
        </div>
      </div>
      <div class="flex flex-col items-center mx-auto my-[40px] space-y-3 card">
        <div class="flex flex-wrap space-y-3 sm:space-y-0 sm:space-x-3">
          <CardP class="bg-[#854CFF]" />
          <CardH />
        </div>
        <div class="flex flex-wrap space-y-3 sm:space-y-0 sm:space-x-3">
          <CardH />
          <CardP class="bg-[#504CFF]" />
        </div>
      </div>
    </section>

    <div class="my-10 bg-slate-500">
      <div
        class="h-[100px] bg-[#504CFF] rotate-0 sm:rotate-2 flex justify-around flex-wrap items-center overflow"
      >
        <font-awesome-icon icon="fa-brands fa-instagram" size="2xl" />
        <font-awesome-icon icon="fa-brands fa-google" size="2xl" />
        <font-awesome-icon icon="fa-brands fa-instagram" size="2xl" />

        <font-awesome-icon icon="fa-brands fa-google" size="2xl" />
        <font-awesome-icon icon="fa-brands fa-instagram" size="2xl" />
        <font-awesome-icon icon="fa-brands fa-google" size="2xl" />
      </div>
    </div>

    <section class="px-2 my-10 sm:px-10">
      <div class="flex flex-wrap items-end justify-between space-y-3">
        <div class="space-y-3">
          <h1 class="text-3xl sm:text-6xl">Our Product</h1>
          <p class="text-xs sm:text-xl">
            help you to build website company that is modern, user friendly, good CEO, and Clean
            design
          </p>
        </div>
        <div class="">
          <button class="px-4 py-1 font-semibold text-black bg-white rounded-full btn">
            Get Start
            <span class="pl-2">
              <font-awesome-icon icon="fa-solid fa-arrow-right" />
            </span>
          </button>
        </div>
      </div>
    </section>
    <section class="px-2 my-10 space-y-6 sm:px-10">
      <div class="flex space-x-2">
        <CardPr />

        <CardPr />
      </div>
      <div class="flex space-x-2">
        <CardPr />

        <CardPr />
      </div>
    </section>
    <section class="px-2 my-10 sm:px-10">
      <div class="space-y-3">
        <div class="space-y-3">
          <h1 class="text-3xl sm:text-6xl">What they say about us</h1>
          <p class="text-xs sm:text-xl">
            Work in the IT field includes Web Design, UI/UX Design, Branding <br />
            and Shopify Development
          </p>
        </div>
        <div class="flex flex-wrap space-y-3 sm:gap-3 sm:space-y-0">
          <CardTesti />
          <CardTesti />
          <CardTesti />
          <CardTesti />
          <CardTesti />
          <CardTesti />
        </div>
      </div>
    </section>

    <footer class="px-10 text-white bg-black border-t bg-opacity-40 backdrop-blur-sm">
      <div class="flex flex-wrap items-center justify-between pt-10 space-y-3">
        <div class="space-y-3">
          <h1 class="text-3xl sm:text-6xl">Let’s work with Us</h1>
          <p class="text-xs sm:text-xl">
            help you to build website company that is modern, user friendly, good CEO, and Clean
            design
          </p>
        </div>
        <div class="">
          <button class="px-4 py-1 font-semibold text-black bg-white rounded-full btn">
            Know More
            <span class="pl-2">
              <font-awesome-icon icon="fa-solid fa-arrow-right" />
            </span>
          </button>
        </div>
      </div>
      <div class="">
        <div class="flex flex-wrap justify-between gap-6 mt-10">
          <div>
            <h3 class="mb-2 text-lg font-semibold">Tentang Kami</h3>
            <p>Deskripsi tentang perusahaan atau situs Anda.</p>
          </div>
          <div>
            <h3 class="mb-2 text-lg font-semibold">Navigasi</h3>
            <ul>
              <li><a href="#">Beranda</a></li>
              <li><a href="#">Produk</a></li>
              <li><a href="#">Kontak</a></li>
            </ul>
          </div>
          <div>
            <h3 class="mb-2 text-lg font-semibold">Kontak</h3>
            <p>Alamat: Jalan Contoh No. 123</p>
            <p>Email: info@contoh.com</p>
            <p>Telepon: (123) 456-7890</p>
          </div>
          <div>
            <h3 class="mb-2 text-lg font-semibold">Sosial Media</h3>
            <ul>
              <li><a href="#" class="text-blue-300 hover:text-blue-500">Facebook</a></li>
              <li><a href="#" class="text-blue-300 hover:text-blue-500">Twitter</a></li>
              <li><a href="#" class="text-blue-300 hover:text-blue-500">Instagram</a></li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
