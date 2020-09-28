<template>
  <div id="app">
    <img class="logo" src="./assets/logo.png">
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
    width: 200;
    height: 200;
  }
</style>
