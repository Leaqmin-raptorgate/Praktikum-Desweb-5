<script setup>
  import {RouterView} from 'vue-router'
  import Navbar from '../components/Navbar.vue'
  import Footer from '../components/Footer.vue'
  import HeroContact from '../components/Hero_Contact.vue'
    import InfoMaps from '../components/InfoMaps.vue'
</script>

<template>
  <Navbar />

  <HeroContact />

  <InfoMaps />

  <main>
    <RouterView />
  </main>

  <Footer />
</template>