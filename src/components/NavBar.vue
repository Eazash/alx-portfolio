<script setup lang="ts">
  import { onMounted, onUnmounted, ref } from 'vue';
  import NavLink from './NavLink.vue';
  const nav = ref<HTMLElement | null>(null)
  const scrollListener = () => {
    if (window.scrollY > (nav.value?.offsetHeight ?? 0)) {
      nav.value?.children[0].classList.add('bg-black/75');
    } else {
      nav.value?.children[0].classList.remove('bg-black/75');
    }
  };
  onMounted(() => {
    if (nav.value !== null) {
      document.addEventListener("scroll", scrollListener)
    }
  })
  onUnmounted(() => {
    document.removeEventListener("scroll", scrollListener)
  })
</script>
<template>
  <nav class="z-10 top-0 sticky" ref="nav">
    <ul
      class="flex items-center justify-end p-6 shadow-sm h-8 backdrop-blur-lg backdrop-invert transition-all duration-150 bg-black/50">
      <NavLink href="#" text="Home" />
      <NavLink href="#bio" text="Bio" />
      <NavLink href="#pitch" text="Elevator Pitch" />
      <NavLink href="#portfolio" text="Portfolio" />
    </ul>
  </nav>
</template>