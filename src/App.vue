<template>
  <div id="app">
    <Navbar></Navbar>
    <router-view/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  name: 'navbar',
  components: {
    Navbar
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>
