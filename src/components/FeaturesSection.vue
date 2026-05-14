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
  <section class="py-24 px-6 bg-cream">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold font-rounded text-dark text-center tracking-tight">
        Everything you need to improve
      </h2>
      <p class="text-muted font-rounded text-center mt-4 mb-16 max-w-lg mx-auto">
        Tools designed for players who want to get better.
      </p>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
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
