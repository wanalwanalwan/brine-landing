<template>
  <footer class="py-10 px-6 md:px-8 bg-dark">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
      <div class="font-rounded font-bold text-teal text-[15px]">
        brine
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
