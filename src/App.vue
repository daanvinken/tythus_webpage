<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/projects">Projects</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  font-size: 1.6rem;
  font-family: "Open Sans", sans-serif;
  color: #2c3e50;
  margin: 0;
  padding: 0;
  background-color: lightgray;
  background-image: -webkit-linear-gradient(-30deg, lightslategray 49.99%, #fff 50%);
  min-height: 100vh;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: dodgerblue;
}
</style>
