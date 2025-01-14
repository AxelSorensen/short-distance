<template>
  <div class="w-screen grid grid-rows-[auto,1fr,auto] h-screen justify-center items-center">
    <div class="p-4 bg-green-200 text-green-900 w-screen text-center">Short Distance</div>
    <div class="p-4  h-full">
      <h2 class="text-xl mb-4">Apps</h2>
      <div class="grid gap-4 grid-cols-2 sm:grid-cols-3 w-full flex-wrap ">
        <div class=" bg-gray-100 p-2 rounded-md" v-for="app in apps">
          <p>{{ app.name }}</p>
          <div class="p-8">
            <img :src="app.icon" alt="">
          </div>
        </div>
        <div class="text-gray-500 border-2 rounded-md border-dashed flex items-center justify-center w-full h-full">
          More to come...
        </div>
      </div>

    </div>
    <div class="bg-gray-100 p-8">Test</div>

  </div>
  <!-- <PWABadge /> -->
</template>

<script setup>
import imageUrl from '/frog.png'


import PWABadge from './components/PWABadge.vue'
import { ref } from 'vue'
const apps = ref([{ name: 'The Wide Mouthed Frog', url: '', icon: imageUrl }])
// Changed small thing
</script>
