<template>
  <h1>hello</h1>
  <img alt="Vue logo" src="./assets/logo.png" />
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Kittisaks />
  <Sakon />
  <Pichayut />
  <Tanatorn />
  <Napat />
  <Piyawat />
  <Hatairut />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Kittisaks from "./components/6106021611142_Kittisak.vue";
import Sakon from "./components/6106021611169_Sakon.vue";
import Pichayut from "./components/6106021612165_Pichayut.vue";
import Tanatorn from "./components/6106021621041_tanatorn";
import Napat from "./components/6106021622039_Napat.vue";
import Piyawat from "./components/6106021622080_Piyawat";

import Hatairut from "./components/6106021610154_hatairut.vue" ;
export default {
  name: "App",
  components: {
    // HelloWorld,
    Kittisaks,
    Sakon,
    Pichayut,
    Tanatorn,
    Napat,
    Piyawat,
    Hatairut,
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
