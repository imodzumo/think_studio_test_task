<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'

const counter = useCounterStore()
</script>

<template>
  <div class="display">
    <h2>Display</h2>
    <p>Current Count: {{ counter.count }}</p>
  </div>
</template>
