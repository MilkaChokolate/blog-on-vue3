<template>
  <blog-navbar></blog-navbar>
  <div class="app">
    <router-view></router-view>
  </div>
</template>

<script>
import BlogNavbar from "@/components/BlogNavbar";

export default {
  components: {
    BlogNavbar
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.app {
  padding: 20px;
  background: #fcf0f5;
  min-height: 100vh;
  color: #960240;
}
</style>
