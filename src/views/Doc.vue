<template>
  <div>
    <Topnav/>
    <div class="content">
      <aside>侧边栏</aside>
      <main>主要内容</main>
    </div>
  </div>
</template>
<script lang="ts">
import Topnav from "../components/Topnav";
export default {
  components: {Topnav}
}
</script>