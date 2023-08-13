<script setup lang="ts">
  import NavLink from './NavLink.vue';
</script>
<template>
  <nav class="z-10 bg-black-30 backdrop-blur-lg top-0 sticky">
    <ul class="flex items-center justify-end p-6 shadow-sm bg-transparent h-8">
      <NavLink href="#" text="Home" />
      <NavLink href="#bio" text="Bio" />
      <NavLink href="#pitch" text="Elevator Pitch" />
      <NavLink href="#portfolio" text="Portfolio" />
    </ul>
  </nav>
</template>