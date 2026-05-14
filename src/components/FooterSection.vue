<template>
  <footer class="py-12 px-6 bg-dark text-white">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
      <div class="font-rounded font-bold text-lg">🥒 Brine</div>
      <div class="flex gap-6 text-sm font-rounded text-gray-400">
        <a href="#" class="hover:text-white transition-colors">Privacy Policy</a>
        <a href="#" class="hover:text-white transition-colors">Terms of Service</a>
        <a href="mailto:support@trainwithalbert.com" class="hover:text-white transition-colors">Support</a>
      </div>
      <div class="text-sm text-gray-500 font-rounded">
        &copy; {{ new Date().getFullYear() }} Brine. All rights reserved.
      </div>
    </div>
  </footer>
</template>
