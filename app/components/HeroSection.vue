<script setup>
import heroVideo from '~/assets/1184996199_Horizontal_Abstract_1920x1080.mp4'
import heroImage from '~/assets/a9f515d6d6df5a651d9980bc99c6a10505ec6af4.png'
</script>

<template>
  <section class="relative w-full h-screen mt-16" id="home">
    <!-- Background Video -->
    <video autoplay muted loop playsinline class="absolute inset-0 w-full h-full object-cover">
      <source :src="heroVideo" type="video/mp4" />
    </video>

    <!-- Overlay -->
    <div class="absolute inset-0 bg-black/40"></div>

    <!-- Content Over Video -->
    <div class="relative z-10 flex flex-col md:flex-row items-center justify-between h-full px-4 sm:px-6 md:px-12">
      
      <!-- Text on Left -->
      <div class="text-center md:text-left max-w-xl">
        <h1 class="text-white text-2xl sm:text-3xl md:text-5xl font-bold leading-tight">
          Partnering with You to Build 
          <span class="text-blue-300">Smarter Digital Solutions</span>
        </h1>
      </div>

      <!-- Image on Right -->
      <div class="mt-6 md:mt-0 md:ml-12 flex justify-center">
        <img :src="heroImage" alt="Hero Image" class="w-40 h-40 sm:w-56  md:w-64 md:h-64 object-contain" />
      </div>
    </div>

    
  </section>
</template>
