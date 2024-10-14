<template>
  <div class="creations">
    <TheCreations />
  </div>
</template>

<script setup lang="ts">
import TheCreations from '../components/TheCreations.vue'
</script>

<style>
@media (min-width: 1024px) {
  .creations {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
