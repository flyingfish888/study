<template>
  <div id="app">
    <router-link to="/hello">go to hello</router-link>
    <router-link to="/world">go to world</router-link>
    <navigation> 
      <router-view/>
    </navigation>
  </div>
</template>

<script>
export default {
  name: 'App'
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
