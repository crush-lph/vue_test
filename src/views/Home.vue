<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <nav>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Nav from '../components/Nav.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Nav
  }
}
</script>
