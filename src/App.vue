<script setup lang="ts">
import footer from './components/btmNav.vue'
import playerFilter from './components/playerFilter.vue'
import players from './components/players.vue'
import topNav from './components/topNav.vue'
import btmNav from './components/btmNav.vue';
</script>

<template>
  <div class="flex flex-col h-screen">
    <header class="flex justify-between px-10 py-2">
      <topNav />
    </header>

    <section class="flex-1 justify-center px-10 py-3">
      <playerFilter />

      <players />
    </section>

    <footer>
      <btmNav />
    </footer>
  </div>
</template>

<style>
#app {
  font-family: SourceSansProRegular, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

html {
  background-color: #98202a;
}
</style>
