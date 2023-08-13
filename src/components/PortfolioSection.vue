<template>
  <section id="portfolio" class="py-4 my-2 bg-slate-200">
    <d class="flex flex-col w-100 justify-center items-center my-2">
      <h2 class="grow-0 text-6xl text-center text-blue-400 border-b-2 border-blue-400">My Portfolio</h2>
      <p class="text-lg text-center">My past experiences</p>
    </d>
    <div class="h-full max-w-xl m-auto flex flex-col justify-center gap-4">
      <div class="bg-slate-200 p-2">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/mKtEfAiL4Qc" title="YouTube video player"
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