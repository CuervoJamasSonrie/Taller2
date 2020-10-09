<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/e.png">
    <Eddie msg="Ꮯꭺ🇳ꭺꮮ ꭰꭼ Ꭼꭰꭰꮖꭼ"/>
  </div>
</template>

<script>
import Eddie from './components/Eddie.vue'

export default {
  name: 'App',
  components: {
    Eddie
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
  background-color:white;
}
</style>
