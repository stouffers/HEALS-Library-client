<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <p>Example HEALS Library component below</p>
    <InfoModule title="This is a custom InfoModule title"/>
  </div>
</template>

<script>
import {InfoModule} from 'heals-library'

export default {
  name: 'App',
  components: {
    InfoModule,
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
