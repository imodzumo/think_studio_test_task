<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'

const counter = useCounterStore()
</script>

<template>
  <div class="bg-white rounded-xl shadow-lg p-8 w-80 text-center">
    <h2 class="text-xl font-semibold text-blue-600 mb-4">Counter</h2>
    <p class="text-3xl font-bold text-gray-700 mb-6">{{ counter.count }}</p>
    <div class="flex justify-center gap-4">
      <button
        @click="counter.increment"
        class="bg-green-500 hover:bg-green-600 text-white font-bold py-2 px-4 rounded transition"
      >
        +
      </button>
      <button
        @click="counter.decrement"
        class="bg-red-500 hover:bg-red-600 text-white font-bold py-2 px-4 rounded transition"
      >
        -
      </button>
    </div>
  </div>
</template>


