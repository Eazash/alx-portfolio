<script setup lang="ts">
  import NavBar from './components/NavBar.vue';
  import MainSection from './components/MainSection.vue'
  import BioSection from './components/BioSection.vue'
  import PitchSection from './components/PitchSection.vue'
  import PortfolioSection from './components/PortfolioSection.vue'
</script>

<template>
  <NavBar />
  <main>
    <MainSection />
    <BioSection />
    <PitchSection />
    <PortfolioSection />
  </main>
</template>