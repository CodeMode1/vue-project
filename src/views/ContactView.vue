<script setup lang="ts">
import Contact from '../components/Contact.vue'
</script>

<template>
  <div class="contact">
    <h1>This is a contact page</h1>
    <!-- embedded comp -->
    <Contact/>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .contact {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
