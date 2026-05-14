<script setup>
const scrollToTop = () => window.scrollTo({ top: 0, behavior: 'smooth' })
</script>

<template>
  <nav class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-xl border-b border-black/5">
    <div class="max-w-5xl mx-auto px-6 h-14 flex items-center justify-between">
      <button @click="scrollToTop" class="flex items-center gap-2 text-lg font-semibold font-rounded text-dark tracking-tight">
        <img src="/dino-logo.png" alt="Brine mascot" class="w-7 h-7" />
        Brine
      </button>
      <a
        href="https://apps.apple.com/app/brine"
        target="_blank"
        rel="noopener"
        class="text-dark font-rounded font-medium text-sm px-4 py-2 rounded-full bg-cream hover:bg-black/10 transition-colors"
      >
        Download
      </a>
    </div>
  </nav>
</template>
