<script setup>

import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue";
</script>

<template>
  <header>
    <Header />


  </header>

  <div class="px-4">
    <RouterView />
  </div>
  <Footer/>
</template>

