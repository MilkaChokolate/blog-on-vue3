<template>
  <div class="navbar">
    <h1>&#127799;</h1>
    <div class="navbar-buttons">
      <my-button style="margin-right: 20px" @click="$router.push('/')">ABOUT MYSELF</my-button>
      <my-button @click="$router.push('/posts')">POSTS</my-button>
      <my-button style="margin-left: 20px" @click="$router.push('/about')">ABOUT SITE</my-button>
      <my-button style="margin-left: 20px" @click="$router.push('/store')">STORE</my-button>
      <my-button style="margin-left: 20px" @click="$router.push('/composition')">COMPOSITION</my-button>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.navbar {
  height: 50px;
  background-color: #fcbdd9;
  box-shadow: 2px 2px 4px gray;
  display: flex;
  align-items: center;
  padding: 0 15px;
}
.navbar-buttons {
  margin-left: auto;
}
</style>