<script setup>
import FeatureCard from './FeatureCard.vue'

const features = [
  {
    icon: '📊',
    title: 'Skill Ratings',
    description: 'Rate each skill from 0–100% and track your proficiency over time with beautiful charts.',
  },
  {
    icon: '✅',
    title: 'Progress Checklists',
    description: 'Break down skills into actionable checkers. Toggle them off as you master each component.',
  },
  {
    icon: '📈',
    title: 'Trend Charts',
    description: 'See your rating history visualized with sparklines and detailed charts for every skill.',
  },
  {
    icon: '🏆',
    title: 'Achievements',
    description: 'Earn badges as you hit milestones. Stay motivated with unlockable achievements.',
  },
  {
    icon: '📂',
    title: 'Skill Categories',
    description: 'Organize skills by offense, defense, strategy, movement, and more.',
  },
  {
    icon: '📱',
    title: 'Built for iOS',
    description: 'A native SwiftUI experience designed to feel right at home on your iPhone.',
  },
]
</script>

<template>
  <section class="py-20 px-6 bg-white">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold font-rounded text-dark text-center mb-4">
        Everything you need to improve
      </h2>
      <p class="text-muted font-rounded text-center mb-12 max-w-2xl mx-auto">
        Track every aspect of your pickleball game with tools designed for players who want to get better.
      </p>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
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
