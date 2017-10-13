<template>
  <div id="app">
    <home></home>
  </div>
</template>

<script>
import Home from './components/home.vue'
export default {
  name: 'app',
  components:{Home}
}
</script>

<style>
#app {
   width: 1200px;
   margin: 0 auto;
   background-color: lightblue;
   height: 100vh;
   padding-top: 50px;
}
*{
  margin: 0;
}
</style>
