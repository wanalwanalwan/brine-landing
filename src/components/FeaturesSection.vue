<script setup>
import FeatureCard from './FeatureCard.vue'

const features = [
  {
    icon: '📊',
    title: 'Skill Ratings',
    description: 'Rate each skill 0-100% and track proficiency over time.',
  },
  {
    icon: '✅',
    title: 'Progress Checklists',
    description: 'Break skills into actionable steps. Check them off as you improve.',
  },
  {
    icon: '📈',
    title: 'Trend Charts',
    description: 'Visualize your rating history with sparklines and detailed charts.',
  },
  {
    icon: '🏆',
    title: 'Achievements',
    description: 'Earn badges as you hit milestones and stay motivated.',
  },
  {
    icon: '📂',
    title: 'Categories',
    description: 'Organize by offense, defense, strategy, movement, and more.',
  },
  {
    icon: '📱',
    title: 'Built for iOS',
    description: 'Native SwiftUI experience designed for iPhone.',
  },
]
</script>

<template>
  <section class="py-24 px-8">
    <div class="max-w-6xl mx-auto">
      <div class="max-w-6xl mx-auto px-0 mb-16">
        <div class="border-b border-black/8"></div>
      </div>
      <h2 class="text-4xl md:text-5xl font-bold font-rounded text-dark tracking-tight leading-[1.1]">
        Everything you need<br />to improve your game.
      </h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-1 mt-16">
        <FeatureCard
          v-for="feature in features"
          :key="feature.title"
          :icon="feature.icon"
          :title="feature.title"
          :description="feature.description"
        />
      </div>
    </div>
  </section>
</template>
