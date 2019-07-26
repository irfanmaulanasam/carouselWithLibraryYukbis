<template>
  <div id="app">
    <carousel3d/>
    <owlcarousel/>
  </div>
</template>

<script>
import carousel3d from './components/carousel3d'
import owlcarousel from './components/owlcarousel'
export default {
  name:'app',
  components: {
    carousel3d,
    owlcarousel
  }
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
