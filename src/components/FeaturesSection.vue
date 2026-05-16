<script setup>
import FeatureShowcase from './FeatureShowcase.vue'
import PhoneFrame from './PhoneFrame.vue'
import MockupAgent from './MockupAgent.vue'
import MockupTimeline from './MockupTimeline.vue'
import MockupSkills from './MockupSkills.vue'
</script>

<template>
  <section class="px-6 md:px-8">
    <div class="max-w-6xl mx-auto">

      <!-- Section 1: AI Agent — phone left, text right -->
      <FeatureShowcase
        label="AI-Powered"
        title="Tell it what you practiced. It does the rest."
        description="Log sessions in plain English. Brine's AI analyzes what you worked on, updates your skill ratings, and builds a practice plan — all from one conversation."
        :features="['Natural Language Input', 'Instant Skill Updates', 'Personalized Drill Plans']"
      >
        <template #phone>
          <PhoneFrame>
            <MockupAgent />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

      <!-- Section 2: Timeline — text left, phone right -->
      <FeatureShowcase
        label="Transparent"
        title="Your complete pickleball journal."
        description="Every session, every skill change, every AI insight — automatically logged in one timeline. See exactly how your game evolves over time."
        :features="['Full Session History', 'Skill Change Log', 'AI Insights Saved']"
        :reverse="true"
      >
        <template #phone>
          <PhoneFrame>
            <MockupTimeline />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

      <!-- Section 3: Skills — phone left, text right -->
      <FeatureShowcase
        label="Measurable"
        title="Watch every skill move."
        description="Every part of your game rated 0-100%. After each session, see which skills improved, which dropped, and where you stand across the board."
        :features="['0-100% Skill Ratings', 'Category Breakdown', 'After-Session Updates']"
      >
        <template #phone>
          <PhoneFrame>
            <MockupSkills />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

    </div>
  </section>
</template>
