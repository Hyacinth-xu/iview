<template>
  <div>

    <Row :gutter="20">
      <div> 1</div>
    </Row>
    <Row :gutter="20" style="margin-top: 10px;">
           22
    </Row>

  </div>
</template>

<script>
export default {
  name: 'home',
  components: {

  },
  data () {
    return {

    }
  },
  mounted () {
    //
  }
}
</script>

<style lang="less">
  .ivu-row{
    background: #fff;
  }
.count-style{
  font-size: 50px;
}
</style>
