<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
.size{
  width: 100%;
  height: 100%;
}
html,body{
  .size;
  overflow-y: hidden;
  margin: 0;
  padding: 0 200px;
  min-width:1000px;
  background-image:linear-gradient(#01528b,#001b2d);
}
#app {
  .size;
   .ivu-layout{
     background: none;
   }
}
</style>
