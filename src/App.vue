<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyTitle/>
  </div>
</template>

<script>
import MyTitle from './components/Title.vue'

export default {
  name: 'App',
  components: {
    MyTitle
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
  margin-top: 60px;
}
</style>
