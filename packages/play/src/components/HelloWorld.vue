<script setup lang="ts">
import { ref } from "vue"

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <er-button />
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
