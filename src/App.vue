<template>
  <NavBar/>
  <img alt="Rise logo" src="./assets/rise_logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <h2 class="text-3xl text-3lg text-center text-blue-500">This site is currently under construction  </h2>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    NavBar
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
