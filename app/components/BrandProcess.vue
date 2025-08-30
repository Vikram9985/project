<template>
  <section class="w-full bg-white py-12 flex flex-col items-center" id="process">
    <div class="max-w-5xl w-full px-4">
      <h2 class="text-2xl md:text-3xl font-bold text-gray-900 mb-2">Come Behind the Scenes of Our Brand Design Process</h2>
      <p class="text-gray-600 mb-4">Effective branding is a process — not a one-time task. Every step matters.</p>
      <button class="bg-blue-100 text-blue-700 px-4 py-2 rounded-lg font-semibold mb-8 flex items-center gap-2 hover:bg-blue-200 transition">
        See Details
        <svg width="16" height="16" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
      </button>
      <div class="flex gap-2 justify-center flex-wrap">
        <!-- Step 1 -->
        <div class="bg-gray-50 rounded-xl shadow border border-gray-200 w-80 p-6 flex flex-col items-center mb-6">
          <img src="~/assets/per1.png" alt="Step 1" class="w-20 h-20 object-contain mb-4" />
          <span class="bg-blue-100 text-blue-700 px-3 py-1 rounded-full text-xs font-semibold mb-2">Step 1</span>
          <div class="font-bold text-gray-800 text-lg mb-1 text-center">Identifying Your Target Audience</div>
          <div class="text-gray-600 text-sm text-center">We identify the target customers for your brand through research on demographics, behaviors, and preferences.</div>
        </div>
        <!-- Step 2 -->
        <div class="bg-gray-50 rounded-xl shadow border border-gray-200 w-80 p-6 flex flex-col items-center mb-6">
          <img src="~/assets/per2.png" alt="Step 2" class="w-20 h-20 object-contain mb-4" />
          <span class="bg-blue-100 text-blue-700 px-3 py-1 rounded-full text-xs font-semibold mb-2">Step 2</span>
          <div class="font-bold text-gray-800 text-lg mb-1 text-center">Competitor Analysis & User Research</div>
          <div class="text-gray-600 text-sm text-center">We gather insights into the company industry, competitors, and market trends through extensive research.</div>
        </div>
        <!-- Step 3 -->
        <div class="bg-gray-50 rounded-xl shadow border border-gray-200 w-80 p-6 flex flex-col items-center mb-6">
          <img src="~/assets/per3.png" alt="Step 3" class="w-20 h-20 object-contain mb-4" />
          <span class="bg-blue-100 text-blue-700 px-3 py-1 rounded-full text-xs font-semibold mb-2">Step 3</span>
          <div class="font-bold text-gray-800 text-lg mb-1 text-center">Brand Positioning and Strategy</div>
          <div class="text-gray-600 text-sm text-center">Our team develops your brand positioning and branding strategy based on research and insights.</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// No script needed for static layout
</script>

<style scoped>
section {
  min-height: 400px;
}
</style>
