<script setup>
import FeatureShowcase from './FeatureShowcase.vue'
import PhoneFrame from './PhoneFrame.vue'
import MockupAgent from './MockupAgent.vue'
import MockupCoach from './MockupCoach.vue'
import MockupSchedule from './MockupSchedule.vue'
import MockupSkills from './MockupSkills.vue'
</script>

<template>
  <section class="px-6 md:px-8">
    <div class="max-w-6xl mx-auto">

      <!-- Section 1: Log Sessions + AI Coach — phone left, text right -->
      <FeatureShowcase
        label="AI-Powered"
        title="Log sessions. Get coached instantly."
        description="Tell Brine what you practiced in plain English. The AI analyzes your session, updates your skill ratings, and gives you a personalized drill plan — right away."
        :features="['Log Sessions in Plain English', 'Instant Skill Updates', 'AI Drill Plans']"
      >
        <template #phone>
          <PhoneFrame>
            <MockupAgent />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

      <!-- Section 2: Real Coach — text left, phone right -->
      <FeatureShowcase
        label="Human Coaching"
        title="Talk to real coaches. Get fast answers."
        description="Message real pickleball coaches who already see your stats and session history. They know your game, respond quickly, and tell you exactly what to fix."
        :features="['Quick Response Times', 'Coaches See Your Stats', 'Specific Drills from a Pro']"
        :reverse="true"
      >
        <template #phone>
          <PhoneFrame>
            <MockupCoach />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

      <!-- Section 3: Skill Tracking — phone left, text right -->
      <FeatureShowcase
        label="Measurable"
        title="Track every skill. See real progress."
        description="Every part of your game rated 0–100%. After each session, see which skills improved, which need work, and how far you've come over time."
        :features="['0–100% Skill Ratings', 'Session-by-Session Changes', 'Long-Term Progress Tracking']"
      >
        <template #phone>
          <PhoneFrame>
            <MockupSkills />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

      <!-- Section 4: Personalized Schedule — text left, phone right -->
      <FeatureShowcase
        label="Personalized"
        title="A drill schedule built for you."
        description="Brine builds a personalized practice schedule based on your weakest skills. Know exactly what to work on each day so every session counts."
        :features="['Personalized Drill Plans', 'Daily Practice Schedule', 'Focused on Your Weak Spots']"
        :reverse="true"
      >
        <template #phone>
          <PhoneFrame>
            <MockupSchedule />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

    </div>
  </section>
</template>
