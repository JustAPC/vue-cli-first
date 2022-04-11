<template>
  <div id="app">
    <div class="container">
      <hero-bg></hero-bg>
      <title-one></title-one>
    </div>
  </div>
</template>

<script>

import TitleOne from './components/TitleOne.vue'
import HeroBg from './components/HeroBg.vue'

export default {
  name: 'App',
  components: {
    TitleOne,
    HeroBg
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
