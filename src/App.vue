<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MainComponent/>
  </div>
</template>

<script>
import MainComponent from './components/pages/MainComponent.vue'

export default {
  name: 'app',
  components: {
    MainComponent
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
