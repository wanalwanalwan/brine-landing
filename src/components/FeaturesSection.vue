<script setup>
import FeatureCard from './FeatureCard.vue'

const features = [
  {
    icon: '🤖',
    title: 'AI Coach',
    description: 'Tell Brine what you practiced. It updates your skills, spots weaknesses, and tells you exactly what to work on next.',
  },
  {
    icon: '📊',
    title: 'Skill Ratings',
    description: 'Every part of your game rated 0-100%. See exactly where you\'re strong and where you\'re falling behind.',
  },
  {
    icon: '🏋️',
    title: 'Targeted Drills',
    description: 'Stop wasting time on random practice. Get AI-generated drills that target your weakest skills first.',
  },
  {
    icon: '📖',
    title: 'Progress Timeline',
    description: 'Every session, every skill change, every insight — proof that your game is growing.',
  },
]
</script>

<template>
  <section class="py-24 px-8">
    <div class="max-w-6xl mx-auto">
      <div class="fade-up mb-16">
        <div class="border-b border-black/8"></div>
      </div>
      <h2 class="fade-up text-4xl md:text-5xl font-bold font-rounded text-dark tracking-tight leading-[1.1]">
        How Brine makes<br />you better.
      </h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-1 mt-16">
        <FeatureCard
          v-for="(feature, index) in features"
          :key="feature.title"
          :icon="feature.icon"
          :title="feature.title"
          :description="feature.description"
          :class="['fade-up', `fade-up-delay-${index + 1}`]"
        />
      </div>
    </div>
  </section>
</template>
