<script setup lang="ts">
  import SectionTitle from './SectionTitle.vue';
</script>
<template>
  <section id="portfolio" class="py-4 my-2 bg-slate-200">
    <SectionTitle title="My Portfolio" subtitle="My Past Experiences" />
    <div class="h-full max-w-xl m-auto flex flex-col justify-center gap-4">
      <div class="bg-slate-200 p-2">
        <iframe src="https://www.youtube.com/embed/mKtEfAiL4Qc" title="YouTube video player" class="w-full" height="315"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
      </div>
    </div>
    <div class="flex w-100 justify-center my-2">
      <button class="rounded-full bg-blue-600 text-white px-4 py-2">
        <a href="/slide-deck.pdf" download>Download Slide Deck</a>
      </button>
    </div>
  </section>
</template>