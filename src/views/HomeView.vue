<script setup lang="ts">
import Counter from '@/components/Counter.vue'
import Display from '@/components/Display.vue'

</script>

<template>
  <main>
    <div class="min-h-screen bg-gradient-to-br from-blue-100 to-purple-200 flex flex-col items-center justify-center p-8">
      <h1 class="text-4xl font-bold mb-10 text-purple-900">🏆 Counter App</h1>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
        <Counter />
        <Display />
      </div>
    </div>
  </main>
</template>
