<template>
  <div id="app">
    <PrimaApp />
  </div>
</template>

<script>
import PrimaApp from './components/PrimaApp.vue'

export default {
  name: 'App',
  components: {
    PrimaApp
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Courier New', Courier, monospace;
  text-align: center;
  color: #2c3e50;
  margin-top: 50px;
}
</style>
