<template>
<div id="app">
  <Menu></Menu>
  <Contenido></Contenido>
</div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Menu from './components/Menu.vue';
import Contenido from './components/Contenido.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Menu,
    Contenido,
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
