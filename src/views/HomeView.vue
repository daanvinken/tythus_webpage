<template>
  <div class="home">
      <img alt="Tythus Logo" src="@/assets/tythus_logo.png" width="300" height="100">
      <HelloWorld msg="Welkom to Tythus Software Solutions!"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
