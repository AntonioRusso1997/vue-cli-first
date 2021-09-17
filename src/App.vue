<template>
  <div id="app">
    <Title />
  </div>
</template>

<script>
import Title from './components/Title.vue'

export default {
  name: 'App',
  components: {
    Title
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
