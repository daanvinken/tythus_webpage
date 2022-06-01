<template>
  <img alt="Tythus Logo" src="./assets/tythus_logo.png" width="300" height="100">
  <HomePage msg="Welkom bij About!"/>
</template>

<script>
import HomePage from './components/HelloWorld.vue'

export default {
  name: 'AboutPage',
  components: {
    HomePage
  }
}
</script>

<style>
#about {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
