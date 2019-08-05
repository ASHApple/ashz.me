<template>
  <div id="app">
    <top/>
    <links/>
  </div>
</template>

<script>
import top from './components/top.vue'
import links from './components/links.vue'

export default {
  name: 'app',
  components: {
    top,
    links
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
