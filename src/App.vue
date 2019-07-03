<template>
  <div id="app">
    <AppNavbar />
    <Home />
  </div>
</template>

<script>
import AppNavbar from './components/AppNavbar.vue'
import Home from './components/Home.vue'
export default {
  name: 'app',
  components: {
    Home,
    AppNavbar
  }
}
</script>

<style>
#app {
  height: 100%;
  }
</style>
