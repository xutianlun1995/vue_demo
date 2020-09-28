<template>
  <li class="list-group-item">
    <div class="handle">
      <a href="javascript:;">删除</a>
    </div>
    <p class="user"><span>{{comm}}</span><span>说:</span></p>
    <p class="centence">React不错!</p>
  </li>
</template>

<script>
export default {
    props:{
        //指定属性名和属性值的类型
        comments:Object
    }
};
</script>

<style>
</style>
