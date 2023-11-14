<!-- @format -->

<template>
  <div class="my-foo">我是测试组件组件</div>
</template>

<script lang="ts" setup>
defineEmits(["click"]);
</script>

<style scoped>
.my-foo {
  color: hsl(160, 82%, 60%);
}
</style>
