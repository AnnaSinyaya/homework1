<template>
  <div id="app">
    <img src="./assets/logo.png">
    <InputComponent/>
  </div>
</template>

<script>
import InputComponent from './components/InputComponent'

export default {
  name: 'App',
  components: {
    InputComponent
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
