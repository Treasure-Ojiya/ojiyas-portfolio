<script setup lang="ts">
import Navbar from './components/AppNavbar.vue'
import Hero from './components/AppHero.vue'
import Footer from './components/AppFooter.vue'
</script>

<template>
  <div class="">
    <!-- Navbar -->
    <Navbar />

    <div class="fixed inset-0 bg-striped opacity-40 pointer-events-none z-0"></div>
    <div class="relative z-10">
      <Hero />

      <!-- content -->
      <router-view />
    </div>
  </div>
  <Footer />

  <!-- <h1>You did it!</h1>
  <p>
    Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
    documentation
  </p> -->
</template>

<style scoped></style>
