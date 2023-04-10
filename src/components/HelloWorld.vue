<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <el-button @click="count++">count is: {{ count }}</el-button>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
