<template>
  <div>
    导航栏 ｜ 
    <router-link to="/">首页</router-link> ｜ 
    <router-link to="/xxx">姓名</router-link>
  </div>
  <hr>
  <router-view />
</template>

<script>
import hello from "./components/hello.vue";

export default {
  name: "App",
};
</script>
