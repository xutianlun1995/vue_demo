<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
export default {
  components:{
    HelloWorld
  }
}
</script>

<style>
  .logo{
    width: 20;
  }
</style>
