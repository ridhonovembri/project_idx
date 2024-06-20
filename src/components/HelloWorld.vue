<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  Hello World from project idx
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
