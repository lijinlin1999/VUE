<template>
  <div id="app" style="background-color: green;width: 100%;height: 100%;position: absolute">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Home/>
  </div>
</template>

<script>
import Home from './views/Home.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    Home, HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #FFFF00;
  margin-top: 60px;
}
</style>
