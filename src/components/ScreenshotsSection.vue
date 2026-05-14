<script setup>
const screens = [
  { label: 'Track', emoji: '📊', color: 'text-teal' },
  { label: 'Rate', emoji: '🎯', color: 'text-teal' },
  { label: 'Improve', emoji: '📈', color: 'text-teal' },
]
</script>

<template>
  <section class="pb-24 px-8">
    <div class="max-w-6xl mx-auto">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div v-for="screen in screens" :key="screen.label" class="flex flex-col items-center">
          <div class="w-full aspect-[9/16] bg-cream rounded-[2rem] flex items-center justify-center">
            <div class="text-center">
              <div class="text-6xl mb-3">{{ screen.emoji }}</div>
              <p class="text-xs text-muted/50 font-rounded">Screenshot coming soon</p>
            </div>
          </div>
          <div class="mt-4 flex items-center gap-2">
            <span class="w-5 h-5 rounded-full bg-teal/15 flex items-center justify-center">
              <span class="w-2 h-2 rounded-full bg-teal"></span>
            </span>
            <span :class="['text-sm font-semibold font-rounded', screen.color]">{{ screen.label }}</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
