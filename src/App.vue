<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MainTitle/>
    <HeroImage/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MainTitle from './components/MainTitle.vue'
import HeroImage from './components/HeroImage.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MainTitle,
    HeroImage
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
