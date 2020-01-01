<template>
   <div id="link">
      <header>
         <h1 class="text-orphan">连接</h1>
         <h4 class="text-orphan">查看并更改路由器设置</h4>
         <div class="close-button text-orphan"></div>
      </header>
      <main>
         <Tabs type="card">
            <TabPane label="internet設置">标签一的内容</TabPane>
            <TabPane label="本地網絡">标签二的内容</TabPane>
            <TabPane label="高級路由">标签三的内容</TabPane>
         </Tabs>
      </main>
   </div>
</template>

<script>

</script>
<style lang="less">
   #link {
      background: #f8f8f9;
      header {
         background: #e0eaf1;
         padding: 25px 28px 25px;
      }
      main {
         padding: 10px
      }
      .ivu-tabs.ivu-tabs-card>.ivu-tabs-bar .ivu-tabs-tab {

         border-radius: 10px 10px 0 0;

      }
   }
</style>
