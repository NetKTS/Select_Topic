<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Kittisak />
  <Sakon />
  
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Kittisak from './components/6106021611142_Kittisak.vue'
import Sakon from './components/6106021611169_Sakon.vue';
export default {
  name: 'App',
  components: {
    // HelloWorld,
    Kittisak,
    Sakon

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
