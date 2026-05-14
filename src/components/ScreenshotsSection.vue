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
  <section class="py-20 px-6 bg-cream">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold font-rounded text-dark text-center mb-4">
        See it in action
      </h2>
      <p class="text-muted font-rounded text-center mb-12">
        Designed with a warm, playful aesthetic that makes tracking fun.
      </p>
      <div class="flex gap-6 overflow-x-auto pb-4 snap-x snap-mandatory scrollbar-hide">
        <div
          v-for="shot in screenshots"
          :key="shot.label"
          class="flex-shrink-0 w-56 h-[400px] bg-white rounded-3xl shadow-sm border border-gray-100 flex flex-col items-center justify-center snap-center"
        >
          <div class="text-5xl mb-4">{{ shot.emoji }}</div>
          <p class="text-sm text-muted font-rounded">{{ shot.label }}</p>
        </div>
      </div>
    </div>
  </section>
</template>
