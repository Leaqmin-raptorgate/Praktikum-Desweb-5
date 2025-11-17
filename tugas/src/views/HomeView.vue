<script setup>
  import {RouterView} from 'vue-router'
  import Navbar from '../components/Navbar.vue'
  import Footer from '../components/Footer.vue'
  import Hero from '../components/Hero.vue'
  import CTA from '../components/CTA.vue'

</script>

<template>
  <Navbar />

  <Hero />

  <CTA />

  <InfoMaps />
  <main>
    <RouterView />
  </main>

  <Footer />
</template>