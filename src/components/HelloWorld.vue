<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>Petfeed</h1>
  <span>Welcome to PetFeed</span>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
