<script setup>
  // Import Navbar and Footer components
  import Navbar from '~/layouts/Navbar.vue'
  import Footer from '~/layouts/FooterSection.vue'
</script>

<template>
  <div>
    <!-- Navbar at the top -->
    <Navbar />

    <!-- Main Content Area -->
   <main>
     <NuxtPage></NuxtPage>
    </main>

    <Footer />
  </div>
</template>

<style scoped>
/* Scoped styles for layout */
</style>
