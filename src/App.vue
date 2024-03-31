<script setup>
import TheHeader from './components/Header/TheHeader.vue'
import TheBanner from './components/Header/TheBanner.vue'
import TheCounter from './components/Main/TheCounter.vue'
import TheProjects from './components/Main/TheProjects.vue'
import AboutCompany from './components/Main/AboutCompany.vue'
import FinalWork from './components/Main/FinalWork.vue'
</script>

<template>
  <TheHeader />
  <TheBanner />
  <TheCounter />
  <TheProjects />
  <AboutCompany />
  <FinalWork />
</template>

<style>
@import url('@/assets/main.css');
</style>
