<template>
  <section class="w-full bg-[#18182F] py-12 flex flex-col items-center" id="blog">
    <div class="max-w-5xl w-full px-4">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-2" style="color:#2ee59d;">
        BizPartner360's Alternative?<br>
        <span class="text-white">Think One More Time!</span>
      </h2>
      <div class="overflow-x-auto mt-8">
        <table class="w-full text-left border-separate border-spacing-y-6">
          <thead>
            <tr class="text-white text-lg">
              <th class="pl-4">Platform</th>
              <th>Speed</th>
              <th>Flexibility</th>
              <th>Quality</th>
              <th>Scalability</th>
              <th>Affordability</th>
            </tr>
          </thead>
          <tbody>
            <!-- BizPartner360 Row -->
            <tr class="bg-gradient-to-r from-[#2ee59d] via-[#18182F] to-[#18182F] rounded-xl shadow-lg">
              <td class="flex items-center gap-3 py-4 pl-4 rounded-xl">
                <img src="~/assets/users.png" alt="BizPartner360" class="w-10 h-10 rounded-full bg-white p-1" />
                <div>
                  <div class="font-bold text-white">BizPartner360</div>
                  <div class="text-xs text-gray-200">Driven by experts, committed to excellence. Experience high-quality results and full support—no need to hire in-house.</div>
                </div>
              </td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">✔️</td>
            </tr>
            <!-- In House Team -->
            <tr class="bg-[#18182F] border-t border-gray-700">
              <td class="flex items-center gap-3 py-4 pl-4">
                <img src="~/assets/users.png" alt="In House Team" class="w-10 h-10 rounded-full bg-white p-1" />
                <div>
                  <div class="font-bold text-white">In House Team</div>
                  <div class="text-xs text-gray-400">Expert-driven & committed to higher quality. Get effective result & full support without hiring in-house employees.</div>
                </div>
              </td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">❌</td>
            </tr>
            <!-- Creative Agencies -->
            <tr class="bg-[#18182F] border-t border-gray-700">
              <td class="flex items-center gap-3 py-4 pl-4">
                <img src="~/assets/users.png" alt="Creative Agencies" class="w-10 h-10 rounded-full bg-white p-1" />
                <div>
                  <div class="font-bold text-white">Creative Agencies</div>
                  <div class="text-xs text-gray-400">Agencies provide structured processes, but often come with high costs, rigid timelines, and limited flexibility.</div>
                </div>
              </td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">❌</td>
            </tr>
            <!-- Freelancers -->
            <tr class="bg-[#18182F] border-t border-gray-700">
              <td class="flex items-center gap-3 py-4 pl-4">
                <img src="~/assets/users.png" alt="Freelancers" class="w-10 h-10 rounded-full bg-white p-1" />
                <div>
                  <div class="font-bold text-white">Freelancers</div>
                  <div class="text-xs text-gray-400">Freelancers are cost-effective, but often unreliable and inconsistent—especially when collaboration matters.</div>
                </div>
              </td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">✔️</td>
            </tr>
            <!-- Self-Service Tools -->
            <tr class="bg-[#18182F] border-t border-gray-700">
              <td class="flex items-center gap-3 py-4 pl-4">
                <img src="~/assets/users.png" alt="Self-Service Tools" class="w-10 h-10 rounded-full bg-white p-1" />
                <div>
                  <div class="font-bold text-white">Self-Service Tools</div>
                  <div class="text-xs text-gray-400">Website builders are affordable — but don’t expect creative strategy or a uniquely branded digital design.</div>
                </div>
              </td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">✔️</td>
              <td class="text-center text-white text-xl">❌</td>
              <td class="text-center text-white text-xl">✔️</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </section>
</template>

<script setup>
// No script needed for static layout
</script>

<style scoped>
table {
  border-radius: 16px;
  overflow: hidden;
}
th, td {
  padding: 0.75rem 0.5rem;
}
tr {
  border-radius: 16px;
}
</style>
