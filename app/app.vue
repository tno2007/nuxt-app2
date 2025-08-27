<template>
  <div
    class="min-h-screen flex flex-col items-center justify-center bg-zinc-900 text-white"
  >
    <div class="flex gap-8 mb-8">
      <a href="https://vuejs.org/" target="_blank">
        <img
          src="https://vuejs.org/images/logo.png"
          class="h-24 p-6 transition-filter duration-300 hover:drop-shadow-[0_0_2em_#42b883aa]"
          alt="Vue logo"
        />
      </a>
    </div>
    <h1 class="text-4xl font-bold mb-6">Vite + Vue</h1>
    <div class="p-8 rounded-lg bg-zinc-800 mb-8 text-center shadow-lg">
      <button
        @click="count++"
        class="rounded-lg border border-transparent px-4 py-2 text-lg font-medium bg-indigo-500 hover:bg-indigo-400 transition-colors mb-4"
      >
        Count is {{ count }}
      </button>
      <p class="mt-2 text-zinc-300">
        Edit <code class="bg-zinc-700 px-1 py-0.5 rounded">app/app.vue</code> to
        test HMR
      </p>
    </div>
    <p class="text-zinc-400">Click on the Vite and Vue logos to learn more</p>
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";
const count = ref(0);
</script>
