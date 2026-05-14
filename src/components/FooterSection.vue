<template>
  <footer class="py-10 px-8 bg-dark">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
      <div class="flex items-center gap-2.5 font-rounded font-semibold text-white">
        <img src="/dino-logo.png" alt="Brine mascot" class="w-6 h-6" />
        Brine
      </div>
      <div class="flex gap-6 text-sm font-rounded text-white/50">
        <a href="#" class="hover:text-white transition-colors">Privacy</a>
        <a href="#" class="hover:text-white transition-colors">Terms</a>
        <a href="mailto:support@trainwithalbert.com" class="hover:text-white transition-colors">Support</a>
      </div>
      <div class="text-xs text-white/30 font-rounded">
        &copy; {{ new Date().getFullYear() }} Brine
      </div>
    </div>
  </footer>
</template>
