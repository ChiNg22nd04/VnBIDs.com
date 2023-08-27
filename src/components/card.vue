<template>
    <div class="w-full h-100 bg-gray-200 rounded-md p-10">
      <h2 class="text-2xl font-semibol text-pink-600">{{ title}}</h2>
      <p class="text-base text-gray-500 mt-2">
        {{content}}
      </p>
    </div>
</template>
  
<script setup lang='ts'>
  defineProps({
    title: String,
    content: String
  })
</script>
