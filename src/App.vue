<template>
  <h1>{{ string }}</h1>
</template>

<script setup>
import { ref } from "vue";
const string = ref("Hello Web3");
</script>

<style lang="less">
h1 {
  color: red;
}
</style>
