<script setup lang="ts">
  import SectionTitle from './SectionTitle.vue';
</script>
<template>
  <section id="bio" class="px-2 py-8 bg-slate-50">
    <SectionTitle title="Bio" />
    <div class="max-w-xl m-auto flex flex-col justify-center items-center  md:flex-row md:justify-evenly gap-4">
      <div class="md:sticky md:top-16 md:self-start basis-full md:basis-1/3">
        <img src="/mugshot.png" alt="Mugshot Image"
          class="object-contain inline-block h-50 w-50 rounded-md ring-2 ring-white">
      </div>
      <div class="basis-full md:basis-2/3 text-justify">
        <p class="text-md mb-2">
          Ezira Ashenafi is an accomplished iOS Developer and Fullstack Developer at Tefer PLC,
          known for his exceptional skills and dedication. His goal is to achieve financial sustainability while
          continually
          advancing in his field and expanding his knowledge. With a track record of remarkable accomplishments, Ezira
          stands out for his role in building a delivery application from scratch within a backend team and his pursuit of
          a master's degree in software engineering.
        </p>
        <p class="text-md mb-2">
          Ezira's ability to solve complex problems, meticulous attention to detail, and proficiency in coding languages
          enabled him to lead the development of a highly efficient and user-friendly delivery application. This
          achievement showcases his talent and commitment to creating innovative solutions. Simultaneously, he is pursuing
          a master's degree, demonstrating his dedication to lifelong learning and staying at the forefront of software
          engineering advancements. With his exceptional drive and determination, Ezira aspires to succeed in his career
          while making valuable contributions to the field of software development.
        </p>
      </div>
    </div>
  </section>
</template>