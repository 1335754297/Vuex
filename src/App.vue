<template>
  <!-- <div id="app"> -->
    <!-- <img src="./assets/logo.png">
    <div style="background:red;margin:0 auto;width:100px;height: 1px;
transform: scale(0.5);"></div> -->
    <!-- <router-view/> -->
    <!-- <div>Hello wordld.</div> -->
  <!-- </div>   -->
  <div>
  <my-addition></my-addition>
  <p>---------------</p>
  <my-subtraction></my-subtraction>
  </div>
</template>

<script>
import Addition from './components/Addition.vue'
import Subtraction from './components/Subtraction.vue'
export default {
  // name: 'App',
  data() {
    return {}
  },
  components: {
    'my-addition': Addition,
    'my-subtraction': Subtraction,
  },
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
