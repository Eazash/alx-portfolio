<script setup lang="ts">
  defineProps<{ title: string, subtitle?: string }>()
</script>
<template>
  <d class="flex flex-col w-100 justify-center items-center my-2">
    <h2 class="grow-0 text-4xl md:text-6xl text-center text-blue-400 border-b-2 border-blue-400">{{ title }}</h2>
    <p v-if="subtitle" class="text-md md:text-lg text-center">
      {{ subtitle }}
    </p>
  </d>
</template>