<template>
  <TheCreations />
  <!-- <div class="LesCreations">
    <h2 class="Title">Mes Créations</h2>
    <div class="wrapper--Creation">
      <TheCreations v-for="(Creation, index) in 3" :key="index" />
    </div>
  </div> -->
</template>

<script>
import TheCreations from './TheCreations.vue'
export default {
  name: 'LesCreations',
  components: {
    TheCreations
  }
}
</script>

<style>
.wrapper--Creation {
  display: flex;
  align-items: center;
  justify-content: center;
}
.LesCreations .Title {
  height: 50px;
  text-align: center;
  align-content: center;
  background-color: #f1f1f1;
}
</style>
