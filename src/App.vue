<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <AppTitle />
    <HeroTron />
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue'
import HeroTron from './components/HeroTron.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    HeroTron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #2c3e50;
  height: 100vh;
}
body{
  margin: 0 0;
  padding:  0 0;
  box-sizing: border-box;
}
</style>
