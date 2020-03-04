<template>
  <div id="app">
    <img alt="humanIT" width="30%" src="./assets/hands.png">
    <HelloWorld msg="Welcome to ShakeIT!"/>
    <p style="color: #999; font-size: small; font-weight: normal">ShakeIT is a simple and fun Internet of Things game, used for the development of an IoT showcase in purpose
      of a thesis.<br>
      &copy; Stefanie Motzokan, 2020
      <br>This work is licensed under a <a href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 License</a></p>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: monospace;
  font-size: medium;
  font-weight: bold;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
