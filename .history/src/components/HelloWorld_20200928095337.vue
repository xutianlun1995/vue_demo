<template>
    <div >
      <p class="msg">{{msg}}</p>

    </div>
</template>

<script>
export default {
  data(){
    return{
      msg:'Hello'
    }
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .msg{
    color red
    font-size :30px
  }
</style>
