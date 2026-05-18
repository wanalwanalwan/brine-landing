<script setup>
const scrollToTop = () => window.scrollTo({ top: 0, behavior: 'smooth' })
</script>

<template>
  <nav class="bg-cream">
    <div class="max-w-6xl mx-auto px-6 md:px-8 h-14 md:h-16 flex items-center justify-between">
      <button @click="scrollToTop" class="flex items-center gap-2 md:gap-2.5 text-base md:text-lg font-semibold font-rounded text-dark tracking-tight">
        <img src="/brine-logo.png" alt="Brine mascot" class="w-6 h-6 md:w-7 md:h-7" />
        Brine
      </button>
      <a
        href="https://apps.apple.com/app/brine"
        target="_blank"
        rel="noopener"
        class="text-dark font-rounded font-medium text-sm px-4 md:px-5 py-2 rounded-full border border-dark/15 hover:bg-dark hover:text-white transition-colors"
      >
        Get the App
      </a>
    </div>
    <div class="max-w-6xl mx-auto px-6 md:px-8">
      <div class="border-b border-black/8"></div>
    </div>
  </nav>
</template>
