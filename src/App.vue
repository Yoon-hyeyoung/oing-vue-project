<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorlds msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorlds from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorlds
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
</style>
