<template>
  <div id="app">
    <navigation></navigation>
    <router-view/>
  </div>
</template>

<script>
import '../node_modules/bootstrap/dist/js/bootstrap.min.js'
import Navigation from './components/template/Navigation.vue'
export default {
  name: 'app',
  components:{ Navigation }
}
</script>

<style>
@import url('../node_modules/bootstrap/dist/css/bootstrap.min.css');
body, html {
    height: 100%;
    margin: 0;
    overflow-y: auto;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.breadcrumb{
  background-color: transparent !important
}
</style>
