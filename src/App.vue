<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/Andrea.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Carousel></Carousel>
    <Firework :boxHeight="'50%'" :boxWidth="'100%'"/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Carousel from './components/Carousel.vue'
import Firework from './components/Fireworks.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    Carousel,
    Firework
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
