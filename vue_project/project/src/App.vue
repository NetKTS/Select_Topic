<template>
  <h1>hello</h1>
  <img alt="Vue logo" src="./assets/logo.png" />
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Kittisak />
  <Sakon />
  <Pichayut />
  <Tanatorn />
  <Tanapoom />
  <Natnapin />
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Kittisak from "./components/6106021611142_Kittisak.vue";
import Sakon from "./components/6106021611169_Sakon.vue";
import Pichayut from "./components/6106021612165_Pichayut.vue";
import Tanatorn from "./components/6106021621041_tanatorn";
import Tanapoom from "./components/6106021620141_Tanapoom.vue"
import Natnapin from "./components/6106021610073_Natnapin.vue"

export default {
  name: "App",
  components: {
    // HelloWorld,
    Kittisak,
    Sakon,
    Pichayut,
    Tanatorn,
    Tanapoom,
    Natnapin,
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
