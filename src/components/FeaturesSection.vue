<script setup>
import FeatureShowcase from './FeatureShowcase.vue'
import PhoneFrame from './PhoneFrame.vue'
import MockupAgent from './MockupAgent.vue'
import MockupCoach from './MockupCoach.vue'
import MockupTimeline from './MockupTimeline.vue'
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
        title="Talk to a real coach who knows your game."
        description="Book sessions with certified pickleball coaches directly in the app. They can see your stats, your sessions, and exactly where you need help — no catch-up needed."
        :features="['Certified Pickleball Coaches', 'They See Your Data', 'Book Sessions In-App']"
        :reverse="true"
      >
        <template #phone>
          <PhoneFrame>
            <MockupCoach />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

      <!-- Section 3: Progress Checker — phone left, text right -->
      <FeatureShowcase
        label="Measurable"
        title="Check your progress after every session."
        description="Every part of your game rated 0–100%. After each session, see which skills improved, which need work, and how far you've come over time."
        :features="['0–100% Skill Ratings', 'Session-by-Session Changes', 'Long-Term Progress Tracking']"
      >
        <template #phone>
          <PhoneFrame>
            <MockupSkills />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

      <!-- Section 4: Sessions Timeline — text left, phone right -->
      <FeatureShowcase
        label="History"
        title="Every session, every gain, all in one place."
        description="Your complete practice journal — every session logged, every skill change recorded, every AI insight saved. See your whole journey at a glance."
        :features="['Full Session History', 'Skill Change Log', 'AI Insights Saved']"
        :reverse="true"
      >
        <template #phone>
          <PhoneFrame>
            <MockupTimeline />
          </PhoneFrame>
        </template>
      </FeatureShowcase>

    </div>
  </section>
</template>
