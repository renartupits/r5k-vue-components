<script setup lang="ts">
defineProps<{
  title: string;
  onClick?: () => void;
}>()
</script>

<template>
  <div class="flex flex-col gap-4 w-full justify-center items-center">
    <h2>Custom Component</h2>
    <button class="border rounded w-64 py-2 px-3 bg-gray-500 hover:bg-gray-400 border-gray-500 text-white" @click="onClick">{{title}}</button>
  </div>

</template>

<style scoped>

</style>
