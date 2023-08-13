<script setup lang="ts">
  defineProps<{ href: string, text: String }>()
</script>
<template>
  <li
    class="mx-4 active:border-b-2 active:border-b-blue-400 hover:border-b-2 hover:border-b-blue-400 transition duration-200 ease-in-out">
    <a :href="href" class="text-blue-400 hover:text-blue-400">{{ text }}</a>
  </li>
</template>