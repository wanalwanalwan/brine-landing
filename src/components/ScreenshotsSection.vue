<script setup>
const screenshots = [
  { label: 'Skill List', emoji: '📋' },
  { label: 'Skill Detail', emoji: '🎯' },
  { label: 'Progress Charts', emoji: '📈' },
  { label: 'Achievements', emoji: '🏆' },
  { label: 'Categories', emoji: '📂' },
]
</script>

<template>
  <section class="py-24 px-6">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold font-rounded text-dark text-center tracking-tight">
        See it in action
      </h2>
      <p class="text-muted font-rounded text-center mt-4 mb-16">
        Clean design that makes tracking effortless.
      </p>
      <div class="flex gap-4 overflow-x-auto pb-4 snap-x snap-mandatory scrollbar-hide">
        <div
          v-for="shot in screenshots"
          :key="shot.label"
          class="flex-shrink-0 w-52 aspect-[9/16] bg-cream rounded-3xl border border-black/5 flex flex-col items-center justify-center snap-center"
        >
          <div class="text-4xl mb-3">{{ shot.emoji }}</div>
          <p class="text-xs text-muted font-rounded font-medium">{{ shot.label }}</p>
        </div>
      </div>
    </div>
  </section>
</template>
