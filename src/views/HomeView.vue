<script setup>
import TheWelcome from '@/components/TheWelcome.vue'
</script>

<template>
  <div class="home">
    <!-- <TheWelcome /> -->
    <h1>My Recipies</h1>
  </div>
  
</template>

<style>
@media (min-width: 1024px) {
  .home {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }

  .h1{
    color: red;
  }
}
</style>
