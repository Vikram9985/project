<script setup>
  // Import components for the homepage
  import HeroSection from '~/components/HeroSection.vue'
  import ServiceCards from '~/components/ServiceCards.vue'
    import PlatformComparison from '~/components/PlatformComparison.vue'
import Trusted from '~/components/Trusted.vue';
import LeafBanner from '~/components/LeafBanner.vue'
    import CapabilitiesWords from '~/components/CapabilitiesWords.vue'
    import QuestionsFAQ from '~/components/QuestionsFAQ.vue'
    import BrandProcess from '~/components/BrandProcess.vue'
</script>

<template>
  <div>
    <!-- You can pass custom content to the layout slot if needed -->
    <HeroSection />
    <Trusted/>
   <LeafBanner/>

    <ServiceCards />
    <BrandProcess/>
    <PlatformComparison/>
   
    <CapabilitiesWords/>
    
    
    <QuestionsFAQ/>
  </div>
</template>

<style scoped>
/* Scoped styles for index page */
</style>
