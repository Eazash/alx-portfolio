<script setup lang="ts">
  import NavLink from './NavLink.vue';
</script>
<template>
  <nav class="z-10 top-0 sticky">
    <ul class="flex items-center justify-end p-6 shadow-sm h-8 backdrop-blur-lg backdrop-invert bg-slate-300/90">
      <NavLink href="#" text="Home" />
      <NavLink href="#bio" text="Bio" />
      <NavLink href="#pitch" text="Elevator Pitch" />
      <NavLink href="#portfolio" text="Portfolio" />
    </ul>
  </nav>
</template>