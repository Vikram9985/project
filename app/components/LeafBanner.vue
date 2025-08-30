<template>
  <section class="relative w-full bg-[#18182F] py-12 flex flex-col items-center">
    <!-- Leaf Image Banner -->
    <div class="w-full max-w-5xl flex justify-center bg-[#18182F]">
      <img 
        src="~/assets/leafe.jpg" 
        alt="Leaf Banner" 
        class="rounded-lg shadow-lg object-cover w-full h-[329px]" 
      />
    </div>

    <!-- Service Section -->
    <div class="w-full max-w-5xl mt-12 px-4 md:px-0 flex flex-col md:flex-row items-center justify-between">
      <div class="text-white text-3xl md:text-4xl font-bold leading-tight mb-6 md:mb-0">
        The Service We<br />Provide For You!
      </div>
      <button class="bg-transparent border border-white text-white px-6 py-2 rounded-lg flex items-center gap-2 hover:bg-white hover:text-[#18182F] transition">
        All Services
        <svg width="18" height="18" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
      </button>
    </div>
  </section>
</template>

<script setup>
// No script needed
</script>

<style scoped>
section {
  min-height: 500px;
}
</style>
