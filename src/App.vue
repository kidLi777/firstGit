<template>
  <div>
<!--    头部-->
    <Header/>
<!--    主体-->
    <div style="display: flex">  <!--侧边栏，因为是主体加一个div-->
      <Aside/>
<!--      内容区域-->
      <router-view/>
    </div>

  </div>

</template>

<style>

</style>

<script>
import Header from "@/components/Header";
import Aside from "@/components/Aside";

export default {
  name: "Layout",
  components: {
    Header,
    Aside
  }
}
</script>
