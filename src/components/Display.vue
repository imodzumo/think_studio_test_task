<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'

const counter = useCounterStore()
</script>

<template>
  <div class="bg-white rounded-xl shadow-lg p-8 w-80 text-center">
    <h2 class="text-xl font-semibold text-purple-600 mb-4">Display</h2>
    <p class="text-3xl font-bold text-gray-700">
      {{ counter.count }}
    </p>
  </div>
</template>

