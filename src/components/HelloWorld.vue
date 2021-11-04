<script setup lang="ts">
import { defineProps } from 'vue'

defineProps({
  username: { type: String, required: true },
})
</script>

<template>
  <h1>Hi {{ username }}</h1>
  <p>How are you?</p>
</template>

<style scoped lang="scss">
h1 {
  margin: 40px 0 0;
}
p {
  color: #42b983;
}
</style>
