<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <!--<router-view></router-view>-->
    <button type="button" class="mui-btn">默认</button>
    <button type="button" class="mui-btn mui-btn-primary">蓝色</button>
    <button type="button" class="mui-btn mui-btn-success">绿色</button>
    <button type="button" class="mui-btn mui-btn-warning">黄色</button>
    <button type="button" class="mui-btn mui-btn-danger">红色</button>
    <button type="button" class="mui-btn mui-btn-royal">紫色</button>

  </div>
</template>

<script>
import plus from 'plus' // use plus
import mui from 'mui' // use mui
mui.init();
const a = 0;
console.log(a);
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
