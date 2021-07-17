<template>
  <div id="app">
    <helloworld/>
  </div>
</template>

<script>
import helloworld from './components/helloworld.vue'

export default {
  name: 'App',
  components: {
    helloworld
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
