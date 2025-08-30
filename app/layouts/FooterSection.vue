<script setup>
import Logo from '~/assets/Logo.svg'  
// You can also remove this if no imports are needed
</script>

<template>
  <footer class="w-full bg-[#18182F] text-white pt-10 pb-4" id="footer">
    <div class="max-w-7xl mx-auto px-4 flex flex-col md:flex-row justify-between gap-8">
      <!-- Logo & Address -->
      <div class="flex flex-col items-start min-w-[220px]">
        <div class="flex items-center">
          <NuxtLink to="/">
            <img :src="Logo" alt="Company Logo" class="h-10 w-auto" />
          </NuxtLink>
        </div>
        <div class="mb-2 text-sm">1603 Capitol Ave STE 310,<br />Cheyenne, WY 82001,<br />United States</div>
        <div class="flex gap-3 mt-2">
          <a href="#" aria-label="Facebook"><svg width="24" height="24" fill="#3b82f6"><circle cx="12" cy="12" r="12"/><text x="12" y="16" text-anchor="middle" font-size="14" fill="#fff">f</text></svg></a>
          <a href="#" aria-label="WhatsApp"><svg width="24" height="24" fill="#25d366"><circle cx="12" cy="12" r="12"/><text x="12" y="16" text-anchor="middle" font-size="14" fill="#fff">w</text></svg></a>
          <a href="#" aria-label="Telegram"><svg width="24" height="24" fill="#229ED9"><circle cx="12" cy="12" r="12"/><text x="12" y="16" text-anchor="middle" font-size="14" fill="#fff">t</text></svg></a>
          <a href="#" aria-label="YouTube"><svg width="24" height="24" fill="#ff0000"><circle cx="12" cy="12" r="12"/><text x="12" y="16" text-anchor="middle" font-size="14" fill="#fff">▶</text></svg></a>
        </div>
      </div>

      <!-- Important Links -->
      <div>
        <div class="font-bold mb-2">Important Links</div>
        <ul class="space-y-1 text-sm">
          <li><a href="#" class="hover:underline">Link 1</a></li>
          <li><a href="#" class="hover:underline">Link 2</a></li>
          <li><a href="#" class="hover:underline">Link 3</a></li>
          <li><a href="#" class="hover:underline">Link 4</a></li>
          <li><a href="#" class="hover:underline">Link 5</a></li>
          <li><a href="#" class="hover:underline">Link 6</a></li>
        </ul>
      </div>

      <!-- Services -->
      <div>
        <div class="font-bold mb-2">Services</div>
        <ul class="space-y-1 text-sm">
          <li>Item 1</li>
          <li>Item 2</li>
          <li>Item 3</li>
          <li>Item 4</li>
          <li>Item 5</li>
          <li>Item 6</li>
          <li>Item 7</li>
        </ul>
      </div>

      <!-- Specialized Industry -->
      <div>
        <div class="font-bold mb-2">Specialized industry</div>
        <ul class="space-y-1 text-sm list-disc list-inside">
          <li>Item 1</li>
          <li>Item 2</li>
          <li>Item 3</li>
          <li>Item 4</li>
          <li>Item 5</li>
          <li>Item 6</li>
        </ul>
      </div>
    </div>

    <!-- Review Logos -->
    <div class="max-w-4xl mx-auto flex flex-wrap justify-center gap-4 py-8">
      <div class="bg-white rounded-lg px-6 py-2 flex items-center gap-2">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="#2ea97a"><path d="M12 2l3.09 6.26L22 9.27l-5 4.87L18.18 22 12 18.56 5.82 22 7 14.14l-5-4.87 6.91-1.01L12 2z"/></svg>
        <span class="font-bold text-[#2ea97a]">Trustpilot</span>
      </div>
      <div class="bg-white rounded-lg px-6 py-2 flex items-center gap-2">
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Google_2015_logo.svg" alt="Google" class="h-5" />
        <span class="font-bold text-gray-700">Google</span>
      </div>
      <div class="bg-white rounded-lg px-6 py-2 flex items-center gap-2">
        <span class="font-bold text-[#2ea97a]">Clutch</span>
      </div>
      <div class="bg-white rounded-lg px-6 py-2 flex items-center gap-2">
        <span class="font-bold text-gray-700">Behance</span>
      </div>
      <div class="bg-white rounded-lg px-6 py-2 flex items-center gap-2">
        <img src="https://cdn.worldvectorlogo.com/logos/dribbble-icon-1.svg" alt="Dribbble" class="h-5" />
        <span class="font-bold text-pink-500">dribbble</span>
      </div>
      <div class="bg-white rounded-lg px-6 py-2 flex items-center gap-2">
        <span class="font-bold text-green-700">fiverr.</span>
      </div>
    </div>

    <!-- Bottom Bar -->
    <div class="border-t border-gray-700 pt-4 flex flex-col md:flex-row justify-between items-center text-xs text-gray-300 max-w-7xl mx-auto px-4">
      <div class="mb-2 md:mb-0">Terms & Conditions</div>
      <div class="mb-2 md:mb-0">© <a href="#" class="underline">BizPartner 360 LLC</a> all rights reserved 2025</div>
      <div>Privacy Policy</div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  font-family: 'Inter', Arial, sans-serif;
}
</style>
