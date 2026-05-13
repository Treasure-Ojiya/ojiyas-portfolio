<template>
  <nav
    class="relative px-12 md:px-24 py-5 flex justify-between items-center border-b border-white/10"
  >
    <h1 class="text-2xl tracking-wider font-bold text-brand-400">OJIYA</h1>

    <div class="flex items-center">
      <ul class="flex gap-8 text-dark-300 font-medium mr-10">
        <li><a href="#" class="hover:text-brand-400 transition">Home</a></li>
        <li><a href="#" class="hover:text-brand-400 transition">Projects</a></li>
        <li><a href="#" class="hover:text-brand-400 transition">Contact</a></li>
      </ul>

      <button
        class="bg-brand-500 hover:bg-brand-400 text-white text-sm py-2 px-4 rounded-lg transition"
      >
        Download CV
      </button>
    </div>
  </nav>
</template>

<script lang="ts">
export default {
  name: 'AppNavbar',

  setup() {
    return {}
  },
}
</script>

<style lang="scss" scoped></style>
