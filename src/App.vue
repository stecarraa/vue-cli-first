<template>
  <div id="app">
    <MyTitle/>
    <JumbotronHero/>
  </div>
</template>

<script>
import MyTitle from './components/Title.vue'
import JumbotronHero from './components/Hero.vue'
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap/dist/js/bootstrap.min.js'




export default {
  name: 'App',
  components: {
    MyTitle,
    JumbotronHero,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

@import'~bootstrap/dist/css/bootstrap.css'



</style>
