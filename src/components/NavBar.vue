<script setup>
const scrollToTop = () => window.scrollTo({ top: 0, behavior: 'smooth' })
</script>

<template>
  <nav class="fixed top-0 left-0 right-0 z-50 bg-cream/90 backdrop-blur-md border-b border-teal/10">
    <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
      <button @click="scrollToTop" class="text-2xl font-bold font-rounded text-dark tracking-tight">
        🥒 Brine
      </button>
      <a
        href="https://apps.apple.com/app/brine"
        target="_blank"
        rel="noopener"
        class="bg-teal text-white font-rounded font-semibold text-sm px-5 py-2.5 rounded-full hover:bg-teal-dark transition-colors"
      >
        Download
      </a>
    </div>
  </nav>
</template>
