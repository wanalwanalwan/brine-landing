<script setup>
import FeatureCard from './FeatureCard.vue'

const features = [
  {
    icon: '🤖',
    title: 'AI Coach',
    description: 'Log sessions in natural language. Get intelligent analysis, feedback, and personalized recommendations.',
  },
  {
    icon: '📊',
    title: 'Skill Tracking',
    description: 'Rate skills 0-100% across categories like dinking, drives, defense, and strategy. Track progress over time.',
  },
  {
    icon: '🏋️',
    title: 'Drills',
    description: 'AI-generated practice drills tailored to your weakest skills. Track reps and completion.',
  },
  {
    icon: '📖',
    title: 'Timeline',
    description: 'A complete journal of every session, skill update, and coach insight — all in one place.',
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
        Everything you need<br />to improve your game.
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
