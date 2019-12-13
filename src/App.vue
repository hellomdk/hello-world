<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld />
    <Test msg="我是test哦"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Test from './test/Test.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Test
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
