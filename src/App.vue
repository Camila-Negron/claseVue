<template>
  <div id="app">
  <h1>Hola Mundo</h1>
    <img alt="Vue logo" src="https://stickerly.pstatic.net/sticker_pack/B2dUGvnp1W2reKHUwBZE5g/ZZ2GBK/2/96e41462-a182-4a03-8ead-36b6ba7a53d2.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
