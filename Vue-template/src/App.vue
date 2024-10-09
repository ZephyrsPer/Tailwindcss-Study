<script setup>
import Box from "./components/Box/index.vue";
import Select from "./components/Select/index.vue";
</script>

<template>
  <div class="flex h-1/3">
    <Box class="w-1/2"></Box>
    <div class="w-1/3 bg-yellow-100">223423424</div>
  </div>
  <div class="h-1/3">
    <ul class="flex">
      <li class="w-1/3 text-center bg-purple-300">1</li>
      <li class="w-1/3 text-center">2</li>
      <li class="w-1/3 text-center">3</li>
    </ul>
  </div>
  <Select class="h-full bg-slate-100"></Select>
</template>
