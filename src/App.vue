<template>
  <div id="app">
    <search-bar></search-bar>
  </div>
</template>

<script>
import SearchBar from './components/search-bar'

export default {
  name: 'app',
  components: {
    SearchBar
  }
}
</script>

<style>
  @import "assets/styles/search.css";
  @import "assets/styles/reset.css";
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
