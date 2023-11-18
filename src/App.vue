<template>
  <div class="Cart m-0 p-0">
    <HomePage/>
  </div>
  
</template>

<script>
import HomePage from './components/HomePage.vue'


export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
#app {
  font-family: "Montserrat";
  font-style: normal;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
