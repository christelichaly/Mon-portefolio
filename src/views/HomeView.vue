<template>
  <!-- <Contenu /> -->
  <div>
    <Profile />
    <section id="creations"><LesCreations /></section>
    <section id="apropos"><AboutView /></section>
    <section id="contact"><ContactView /></section>
  </div>
  <!-- <TheWelcome /> -->
</template>

<script setup lang="ts">
// les imports
// import DDC from '../DDC'
//les components
// import ontenu from '../components/Contenu.vue'
// import TheWelcome from '../components/TheWelcome.vue'

import Profile from '../components/ProfileCompo.vue'
import LesCreations from '../components/LesCreations.vue'
import AboutView from './AboutView.vue'
import ContactView from './ContactView.vue'
</script>
<style scoped>
/* #apropos {
  margin-top: 500px;
} */
</style>
