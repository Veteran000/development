<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <buyt msg="welcome to use elment"/>
  </div>
</template> 

<script>
import HelloWorld from './components/HelloWorld.vue'
import buyt from './components/buyt.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    buyt
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
