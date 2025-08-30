<template>
  <section class="bg-gray-50 py-16">
    <div class="max-w-6xl mx-auto px-6 text-center">
      
      <!-- Ratings Section -->
      <div class="flex flex-col md:flex-row items-center justify-center gap-16 mb-12">
        <!-- Trust Boxes -->
    <div class="relative z-10 flex flex-col sm:flex-row gap-4 sm:gap-8 mt-8 sm:mt-12 justify-center items-center px-4">
      <!-- Trustpilot Box -->
      <div class="border-2 border-dashed border-[#2ea97a] bg-white p-4 rounded-lg w-full sm:w-60 text-center">
        <div class="flex items-center justify-center gap-2 mb-2">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="#2ea97a"><path d="M12 2l3.09 6.26L22 9.27l-5 4.87L18.18 22 12 18.56 5.82 22 7 14.14l-5-4.87 6.91-1.01L12 2z"/></svg>
          <span class="font-bold text-[#2ea97a] text-lg">Trustpilot</span>
        </div>
        <div class="flex justify-center gap-1 mb-1">
          <template v-for="i in 5" :key="'tp'+i">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="#2ea97a"><path d="M12 2l3.09 6.26L22 9.27l-5 4.87L18.18 22 12 18.56 5.82 22 7 14.14l-5-4.87 6.91-1.01L12 2z"/></svg>
          </template>
        </div>
        <p class="text-sm text-gray-800">Trust Score 4.9 | 55 reviews</p>
      </div>

      <!-- Clutch Box -->
      <div class="border-2 border-dashed border-[#e74c3c] bg-white p-4 rounded-lg w-full sm:w-60 text-center">
        <div class="flex items-center justify-center gap-2 mb-2">
          <span class="font-bold text-gray-800 text-lg">Clutch</span>
        </div>
        <div class="flex justify-center gap-1 mb-1">
          <template v-for="i in 5" :key="'cl'+i">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="#e74c3c"><path d="M12 2l3.09 6.26L22 9.27l-5 4.87L18.18 22 12 18.56 5.82 22 7 14.14l-5-4.87 6.91-1.01L12 2z"/></svg>
          </template>
        </div>
        <p class="text-sm text-gray-800">Clutch Score 5.0 | 1 review</p>
      </div>
    </div>
      </div>

      <!-- Heading -->
      <h2 class="text-lg md:text-xl font-semibold text-gray-800 mb-8">
        Trusted by 200+ Global Brands
      </h2>

      <!-- Logos Section -->
      <!-- <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-6 items-center justify-center">
        <img src="/brands/simonelli.png" alt="Simonelli" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/delonghi.png" alt="Delonghi" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/oxford.png" alt="Oxford" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/bbc.png" alt="BBC" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/easymerch.png" alt="EasyMerch" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/dynamic.png" alt="Dynamic" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/dtlc.png" alt="DTLC" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/bobby24.png" alt="Bobby24" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/gopi.png" alt="Gopi" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/practical.png" alt="Practical" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/sporthify.png" alt="Sporthify" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
        <img src="/brands/private.png" alt="Private" class="h-10 mx-auto grayscale hover:grayscale-0 transition" />
      </div> -->

    </div>
  </section>
</template>

<script setup>
// No script required
</script>
