<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Second msg="hello vue"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Second from './components/Second'

export default {
  name: 'App',
  components: {
    Second
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
