<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/psicologia.png">
    <!--<HelloWorld msg="Mi primera aplicación"/>-->
    <ejemplo></ejemplo>
    <lista></lista>

  </div>
</template>

<script>
  //import HelloWorld from './components/HelloWorld.vue'
  import lista from './components/lista.vue'
  import ejemplo from './components/ejemplo.vue'


export default {
  name: 'App',
  components: {
    //HelloWorld,
    ejemplo,
    lista,

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
