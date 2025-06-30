<script setup lang="ts">
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import MusicSection from './components/MusicSection.vue';
import ShowsSection from './components/ShowsSection.vue';
import MerchSection from './components/MerchSection.vue';
import EmailSignup from './components/EmailSignup.vue';
</script>

<template>
  <Header />
  <main>
    <Hero />
    <MusicSection />
    <ShowsSection />
    <MerchSection />
    <EmailSignup />
  </main>
</template>

<style scoped>
main {
  max-width: 1280px;
  margin: 0 auto;
}
</style>
