<template>
  <div class="flex flex-col">
    <h1 class="text-center font-bold text-4xl">盒子模型</h1>
    <div class="bg-pink-700 h-56 w-full flex justify-center items-center">
      <span class="bg-gray-500 text-4xl text-white w-fit p-5">天气预报</span>
    </div>
    <div class="bg-blue-500 h-56 w-full flex">
      <div class="bg-green-500 size-1/3"></div>
      <div class="bg-yellow-500 w-full h-1/3"></div>
    </div>
    <div class="bg-purple-500 h-56 w-full p-12 flex">
      <span class="text-center bg-white w-full">内容</span>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
