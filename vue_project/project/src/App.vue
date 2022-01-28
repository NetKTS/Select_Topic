<template>
  <h1>hello</h1>
  <img alt="Vue logo" src="./assets/logo.png" />
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Kittisak />
  <Sakon />
  <Pichayut />
  <Tanatorn />
  <Chitsanupong />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Kittisak from "./components/6106021611142_Kittisak.vue";
import Sakon from "./components/6106021611169_Sakon.vue";
import Pichayut from "./components/6106021612165_Pichayut.vue";
import Tanatorn from "./components/6106021621041_tanatorn";
import Chitsanupong from "./components//6106021610081_Chitsanupong.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    Kittisak,
    Sakon,
    Pichayut,
    Tanatorn,
    Chitsanupong,
  },
};
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
