<template>
  <button class="btn">
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: 'my-button'
}
</script>

<style scoped>
.btn {
  padding: 10px 15px;
  background: #fcbdd9;
  color: #960240;
  border: 2px solid #960240;
  border-radius: 5px;
}
</style>
