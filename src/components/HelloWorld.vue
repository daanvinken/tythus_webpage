<template>
  <div class="container introduction">
    <div
        :style="{
        'background-image': `url(${require('@/assets/tythus_logo.png')})`,
        width: '100px',
        height: '100px',
      }"
    ></div>
    <h1>{{ msg }}</h1>
    <p>
      Please take a look around here!
    </p>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
