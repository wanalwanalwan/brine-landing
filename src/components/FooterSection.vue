<template>
  <footer class="py-10 px-6 border-t border-black/5">
    <div class="max-w-5xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
      <div class="flex items-center gap-2 font-rounded font-semibold text-dark">
        <img src="/dino-logo.png" alt="Brine mascot" class="w-6 h-6" />
        Brine
      </div>
      <div class="flex gap-6 text-sm font-rounded text-muted">
        <a href="#" class="hover:text-dark transition-colors">Privacy</a>
        <a href="#" class="hover:text-dark transition-colors">Terms</a>
        <a href="mailto:support@trainwithalbert.com" class="hover:text-dark transition-colors">Support</a>
      </div>
      <div class="text-xs text-muted font-rounded">
        &copy; {{ new Date().getFullYear() }} Brine
      </div>
    </div>
  </footer>
</template>
