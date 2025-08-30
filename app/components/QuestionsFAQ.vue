<template>
  <section class="w-full bg-white py-12 flex flex-col items-center" id="faq">
    <div class="max-w-5xl w-full px-4">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-8 text-gray-900">
        Have <span class="underline">Questions?</span>
      </h2>
      <div class="flex flex-col md:flex-row gap-8 items-start justify-center">
        <!-- Left Side: Call to Action Card -->
        <div class="bg-gradient-to-br from-[#1a237e] via-[#283593] to-[#7c4dff] rounded-xl shadow-lg p-6 w-full md:w-80 flex flex-col justify-between min-h-[220px]">
          <img src="~/assets/bgima.png" alt="Find the right solution" class="absolute top-0 left-0 w-full h-full object-cover rounded-xl opacity-30 pointer-events-none" style="z-index:0;" />
          <div class="relative z-10">
            <div class="flex items-center gap-2 mb-3">
              <img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-8 h-8 rounded-full border-2 border-white" />
              <img src="https://randomuser.me/api/portraits/women/44.jpg" class="w-8 h-8 rounded-full border-2 border-white" />
              <img src="https://randomuser.me/api/portraits/men/65.jpg" class="w-8 h-8 rounded-full border-2 border-white" />
            </div>
            <div class="text-white font-semibold text-lg mb-2">Find the right solution for you now</div>
            <button class="bg-[#2ee59d] text-[#18182F] font-bold px-4 py-2 rounded-lg shadow hover:bg-[#26c48c] transition">Book a Quick Call</button>
          </div>
        </div>
        <!-- Right Side: FAQ Accordion -->
        <div class="flex-1 w-full">
          <div class="space-y-4">
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">What services does BizPartner360 provide?</div>
                <span class="text-2xl font-bold">-</span>
              </div>
              <div class="mt-2 text-gray-700 text-sm">
                Working with BizPartner360 has been a game-changer for our business. Their team is incredibly responsive, detail-oriented, and committed to delivering high-quality work. From strategy to execution, they handled everything with professionalism and care. We now have a digital presence we’re truly proud of — and we’re already seeing results.
              </div>
            </div>
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">How is BizPartner360 different from freelancers or traditional agencies?</div>
                <span class="text-2xl font-bold">+</span>
              </div>
            </div>
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">Do you offer ongoing support after project completion?</div>
                <span class="text-2xl font-bold">+</span>
              </div>
            </div>
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">What if I need revisions during the project?</div>
                <span class="text-2xl font-bold">+</span>
              </div>
            </div>
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">How long does a typical website or product design project take?</div>
                <span class="text-2xl font-bold">+</span>
              </div>
            </div>
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">Do I need to have a clear idea before starting a project?</div>
                <span class="text-2xl font-bold">+</span>
              </div>
            </div>
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">What tools do you use for design and development?</div>
                <span class="text-2xl font-bold">+</span>
              </div>
            </div>
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">Can I hire you for just design or just development?</div>
                <span class="text-2xl font-bold">+</span>
              </div>
            </div>
            <div class="border-b pb-4">
              <div class="flex justify-between items-center cursor-pointer">
                <div class="font-semibold text-gray-900">What are your focus areas as a UI/UX agency?</div>
                <span class="text-2xl font-bold">+</span>
              </div>
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
