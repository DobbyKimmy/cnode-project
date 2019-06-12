<template>
    <div class="header clearfix">
      <router-link :to="{name:'root'}">
        <img src="../assets/cnodejs_light.svg" alt="">
      </router-link>

      <ul>
        <li><a href="">首页</a></li>
        <li><a href="">新手入门</a></li>
        <li><a href="">API</a></li>
        <li><a href="">关于</a></li>
        <li><a href="">注册</a></li>
        <li><a href="">登陆</a></li>
      </ul>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
  .header{
    background: #5a5555;
    height: 50px;
  }
  .clearfix{
    content: '';
    overflow: hidden;
    clear: both;
  }
  img{
    max-width: 120px;
    margin-left: 50px;
    margin-top: 10px;
  }
  ul{
    list-style: none;
    float: right;
    margin: 4px;
  }
  li{
    display: inline-block;
    padding: 10px 15px;
  }
  a{
    text-decoration: none;
    color: #cccccc;
    font-size: 14px;
    text-shadow: none;
  }
</style>
