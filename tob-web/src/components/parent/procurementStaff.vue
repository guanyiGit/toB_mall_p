<template>
    <!--采购人员-->
  <!--主体内容-->
  <div class="w1200 c-b mm100">
    <!--侧边栏-->
    <main-memu></main-memu>
    <!--侧边栏END-->

    <!--内容区-->
    <div class="mgl170 pdr15 ifrmae1">
      <router-view></router-view>
    </div>
    <!--内容区END-->
  </div>
  <!--主体内容END-->
</template>

<script>
  import mainMemu from '../common/mainMemu'
    export default {
      name: "procurementStaff",
      components: {
        mainMemu
      },
    }
</script>

<style scoped>

</style>
