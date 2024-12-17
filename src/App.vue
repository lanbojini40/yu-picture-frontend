
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
<template>
  <div id="app">
  <BasicLayout />
  </div>
  </template>

  <script setup lang="ts">
import BasicLayout from "@/layouts/BasicLayout.vue";
//已经改为在权限校验文件中获取
// import {useLoginUserStore} from "@/stores/useLoginUserStore.ts";
// const loginUserStore = useLoginUserStore()
// loginUserStore.fetchLoginUser()

</script>
<style>
#app {
}
</style>

