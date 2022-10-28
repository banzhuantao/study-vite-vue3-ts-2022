<!--
  @description 介绍文件的作用、文件的入参、出参
-->

<script lang="ts" setup>
</script>

<template>
  <div class="dashboard">
    <h1>我现在是导航页</h1>

    <div class="dashboard-content">我是导航页的内容区</div>
  </div>
</template>

<script lang="ts">
export default {
  name: "DashboardPage"
}
</script>

<style lang="scss" scoped>
.dashboard {
  background-color: #f66;

  &-content {
    color: aqua;
  }
}
</style>
