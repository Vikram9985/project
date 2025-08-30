<template>
  <section class="w-full bg-white py-12 flex flex-col items-center">
    <div class="max-w-5xl w-full px-4">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-8 text-gray-900">
        Words That Define<br />Our Capabilities
      </h2>
      <div class="flex justify-end mb-4 gap-2">
        <button class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200 transition">
          <svg width="18" height="18" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24"><path d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200 transition">
          <svg width="18" height="18" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24"><path d="M9 5l7 7-7 7"/></svg>
        </button>
      </div>
      <div class="flex gap-6 justify-center flex-wrap">
        <!-- Card 1 -->
        <div class="bg-gray-50 rounded-xl shadow border border-gray-200 w-[370px] p-6 flex flex-col md:flex-row items-center mb-6">
          <div class="flex-1">
            <img src="~/assets/easy.png" alt="EasyMerch" class="h-8 mb-2" />
            <div class="font-bold text-gray-800 text-lg mb-1">Professional. Reliable. Impactful.</div>
            <div class="text-gray-600 text-sm mb-4">Working with BizPartner360 has been a game-changer for our business. Their team is incredibly responsive, detail-oriented, and committed to delivering high-quality work. From strategy to execution, they handle everything with professionalism and care. We now have a digital presence we’re truly proud of — and we’re already seeing results.</div>
            <div class="font-semibold text-gray-700 text-sm">Sarah M.</div>
            <div class="text-xs text-gray-500">Marketing Director<br />EasyMerch</div>
          </div>
          <div class="flex-shrink-0 ml-6 flex flex-col items-center">
            <div class="relative">
              <img src="~/assets/women.jpg" alt="Sarah M." class="w-24 h-24 object-cover rounded-lg" />
              <button class="absolute inset-0 flex items-center justify-center">
                <svg width="40" height="40" viewBox="0 0 40 40" fill="none"><circle cx="20" cy="20" r="20" fill="#2ee59d"/><polygon points="16,13 28,20 16,27" fill="#fff"/></svg>
              </button>
            </div>
          </div>
        </div>
        <!-- Card 2 -->
        <div class="bg-gray-50 rounded-xl shadow border border-gray-200 w-[370px] p-6 flex flex-col md:flex-row items-center mb-6">
          <div class="flex-1">
            <img src="~/assets/privet.png" alt="Privatesix" class="h-8 mb-2" />
            <div class="font-bold text-gray-800 text-lg mb-1">Professional. Reliable. Impactful.</div>
            <div class="text-gray-600 text-sm mb-4">Working with BizPartner360 has been a game-changer for our business. Their team is incredibly responsive, detail-oriented, and committed to delivering high-quality work. From strategy to execution, they handle everything with professionalism and care. We now have a digital presence we’re truly proud of — and we’re already seeing results.</div>
            <div class="font-semibold text-gray-700 text-sm">Sarah M.</div>
            <div class="text-xs text-gray-500">Marketing Director<br />EasyMerch</div>
          </div>
          <div class="flex-shrink-0 ml-6 flex flex-col items-center">
            <div class="relative">
              <img src="~/assets/men.jpg" alt="Sarah M." class="w-24 h-24 object-cover rounded-lg" />
              <button class="absolute inset-0 flex items-center justify-center">
                <svg width="40" height="40" viewBox="0 0 40 40" fill="none"><circle cx="20" cy="20" r="20" fill="#2ee59d"/><polygon points="16,13 28,20 16,27" fill="#fff"/></svg>
              </button>
            </div>
          </div>
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
