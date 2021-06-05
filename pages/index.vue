<template>
  <div class="flex flex-col items-center justify-center min-h-screen text-center">
    <h1 class="block text-3xl title md:text-5xl xl:text-6xl">Quantum Computing Initiative</h1>
    <h3 class="block pt-5 text-xl title md:text-2xl">A 3-week introduction for high school students</h3>
    <div class="flex justify-between pt-10">
      <nuxt-link class="px-8 py-2 mx-2 text-gray-800 border-2 border-gray-500 rounded hover:bg-gray-100" to="/details">Details</nuxt-link>
      <a class="px-8 py-2 mx-2 text-gray-800 border-2 border-gray-500 rounded hover:bg-gray-100" href="https://forms.gle/cSNSKn4v5odrHpRz9" target="_blank">Register</a>
    </div>
    <div class="flex justify-between pt-10">
      <a class="px-2 pt-10 text-gray-800 border-b-2 border-gray-500 hover:border-gray-400 hover:text-gray-500" href="https://tanaybiradar.com" target="_blank">Tanay Biradar</a>
      <a class="px-2 pt-10 mx-2 text-gray-800 border-b-2 border-gray-500 hover:border-gray-400 hover:text-gray-500" href="https://github.com/quantum-computing-initiative" target="_blank">GitHub</a>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  color: #35495e;
}
</style>
