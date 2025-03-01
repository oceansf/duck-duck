<template>
  <div class="bg-[url(/img/hero-bg.png)] h-screen bg-fixed bg-cover bg-no-repeat">
    <div class="sticky z-20 md:top-6 top-3 md:left-12 left-6 lg:w-40 w-24">
      <a href="#" class="hover:border-2">
        <img src="/img/logo.png" alt="OG Studios Logo" />
      </a>
    </div>
    <div
      class="flex flex-col items-center md:gap-4 absolute z-10 md:top-[170px] top-[90px] md:left-[200px] md:w-1/2"
    >
      <img src="/img/duckducklogowithduck.png" alt="Duck duck logo" />
      <h1 class="lg:text-6xl md:text-4xl text-2xl font-bold text-white">COMING SOON TO STEAM</h1>
      <CTAButton />
    </div>
  </div>
</template>

<script lang="ts" setup>
//
</script>

<style scoped>
* {
  cursor: url("/img/duckcursor.png"), auto;
}

h1 {
  font-family: Istok Web, sans-serif;
}
</style>
