<script setup>
const videos = {
  aiCoach: '/videos/ai-coach.mp4',
  timeline: '/videos/timeline.mp4',
  drills: '/videos/drills.mp4',
  skills: '/videos/skills.mp4',
}
</script>

<template>
  <section class="px-8">
    <div class="max-w-6xl mx-auto">

      <!-- Section 1: AI Coach — video left, text right -->
      <div class="py-16 md:py-24 border-t border-black/8">
        <div class="fade-up grid grid-cols-1 md:grid-cols-2 gap-10 md:gap-16 items-center">
          <!-- Phone -->
          <div class="flex justify-center">
            <div class="bg-cream rounded-3xl p-6 md:p-10 w-full max-w-[400px]">
              <div class="mx-auto max-w-[260px]">
                <div class="aspect-[9/19.5] bg-dark rounded-[3rem] p-[10px] shadow-xl">
                  <div class="w-full h-full bg-white rounded-[2.25rem] overflow-hidden">
                    <video
                      class="w-full h-full object-cover"
                      autoplay
                      muted
                      loop
                      playsinline
                      preload="metadata"
                      :src="videos.aiCoach"
                    ></video>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Text -->
          <div>
            <span class="text-teal font-semibold text-sm font-rounded">AI-Powered</span>
            <h3 class="text-3xl md:text-[2.5rem] font-bold font-rounded text-dark tracking-tight leading-[1.15] mt-3">
              Tell it what you practiced. It does the rest.
            </h3>
            <p class="text-muted font-rounded leading-relaxed mt-5 text-base">
              Log sessions in plain English. Brine's AI analyzes what you worked on, updates your skill ratings, and builds a practice plan — all from one conversation.
            </p>
            <ul class="mt-6 space-y-3">
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Natural Language Input</span>
              </li>
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Instant Skill Updates</span>
              </li>
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Personalized Drill Plans</span>
              </li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Section 2: Timeline — text left, video right -->
      <div class="py-16 md:py-24 border-t border-black/8">
        <div class="fade-up grid grid-cols-1 md:grid-cols-2 gap-10 md:gap-16 items-center">
          <!-- Phone (first on mobile, right on desktop) -->
          <div class="flex justify-center order-1 md:order-2">
            <div class="bg-cream rounded-3xl p-6 md:p-10 w-full max-w-[400px]">
              <div class="mx-auto max-w-[260px]">
                <div class="aspect-[9/19.5] bg-dark rounded-[3rem] p-[10px] shadow-xl">
                  <div class="w-full h-full bg-white rounded-[2.25rem] overflow-hidden">
                    <video
                      class="w-full h-full object-cover"
                      autoplay
                      muted
                      loop
                      playsinline
                      preload="metadata"
                      :src="videos.timeline"
                    ></video>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Text (second on mobile, left on desktop) -->
          <div class="order-2 md:order-1">
            <span class="text-teal font-semibold text-sm font-rounded">Transparent</span>
            <h3 class="text-3xl md:text-[2.5rem] font-bold font-rounded text-dark tracking-tight leading-[1.15] mt-3">
              Your complete pickleball journal.
            </h3>
            <p class="text-muted font-rounded leading-relaxed mt-5 text-base">
              Every session, every skill change, every AI insight — automatically logged in one timeline. See exactly how your game evolves over time.
            </p>
            <ul class="mt-6 space-y-3">
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Full Session History</span>
              </li>
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Skill Change Log</span>
              </li>
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">AI Insights Saved</span>
              </li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Section 3: Drills — video left, text right -->
      <div class="py-16 md:py-24 border-t border-black/8">
        <div class="fade-up grid grid-cols-1 md:grid-cols-2 gap-10 md:gap-16 items-center">
          <!-- Phone -->
          <div class="flex justify-center">
            <div class="bg-cream rounded-3xl p-6 md:p-10 w-full max-w-[400px]">
              <div class="mx-auto max-w-[260px]">
                <div class="aspect-[9/19.5] bg-dark rounded-[3rem] p-[10px] shadow-xl">
                  <div class="w-full h-full bg-white rounded-[2.25rem] overflow-hidden">
                    <video
                      class="w-full h-full object-cover"
                      autoplay
                      muted
                      loop
                      playsinline
                      preload="metadata"
                      :src="videos.drills"
                    ></video>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Text -->
          <div>
            <span class="text-teal font-semibold text-sm font-rounded">Targeted</span>
            <h3 class="text-3xl md:text-[2.5rem] font-bold font-rounded text-dark tracking-tight leading-[1.15] mt-3">
              Drills built for your weaknesses.
            </h3>
            <p class="text-muted font-rounded leading-relaxed mt-5 text-base">
              Stop wasting time on random practice. Brine generates drills that go after your lowest-rated skills first, with sets, reps, and completion tracking.
            </p>
            <ul class="mt-6 space-y-3">
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Weakness-First Priority</span>
              </li>
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Sets & Reps Tracking</span>
              </li>
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Completion Progress</span>
              </li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Section 4: Skills — text left, video right -->
      <div class="py-16 md:py-24 border-t border-black/8">
        <div class="fade-up grid grid-cols-1 md:grid-cols-2 gap-10 md:gap-16 items-center">
          <!-- Phone (first on mobile, right on desktop) -->
          <div class="flex justify-center order-1 md:order-2">
            <div class="bg-cream rounded-3xl p-6 md:p-10 w-full max-w-[400px]">
              <div class="mx-auto max-w-[260px]">
                <div class="aspect-[9/19.5] bg-dark rounded-[3rem] p-[10px] shadow-xl">
                  <div class="w-full h-full bg-white rounded-[2.25rem] overflow-hidden">
                    <video
                      class="w-full h-full object-cover"
                      autoplay
                      muted
                      loop
                      playsinline
                      preload="metadata"
                      :src="videos.skills"
                    ></video>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Text (second on mobile, left on desktop) -->
          <div class="order-2 md:order-1">
            <span class="text-teal font-semibold text-sm font-rounded">Measurable</span>
            <h3 class="text-3xl md:text-[2.5rem] font-bold font-rounded text-dark tracking-tight leading-[1.15] mt-3">
              Watch every skill move.
            </h3>
            <p class="text-muted font-rounded leading-relaxed mt-5 text-base">
              Every part of your game rated 0-100%. After each session, see which skills improved, which dropped, and where you stand across the board.
            </p>
            <ul class="mt-6 space-y-3">
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">0-100% Skill Ratings</span>
              </li>
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">Category Breakdown</span>
              </li>
              <li class="flex items-center gap-2.5">
                <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                <span class="text-teal font-semibold text-sm font-rounded">After-Session Updates</span>
              </li>
            </ul>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>
