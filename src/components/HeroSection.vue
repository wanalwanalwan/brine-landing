<template>
  <section class="pt-20 pb-24 px-8 overflow-hidden">
    <div class="max-w-6xl mx-auto relative">
      <!-- Left UI elements -->
      <div class="hidden lg:block absolute left-0 top-8 w-64">
        <!-- Skill rating card -->
        <div class="float-slow bg-white rounded-2xl shadow-lg shadow-black/5 border border-black/5 p-4 mb-4 -rotate-3">
          <div class="flex items-center gap-3 mb-3">
            <div class="w-8 h-8 rounded-full bg-teal/10 flex items-center justify-center text-sm">🎯</div>
            <div>
              <div class="text-xs font-semibold text-dark">Dinking</div>
              <div class="text-[10px] text-muted">Updated today</div>
            </div>
          </div>
          <div class="flex items-center gap-2">
            <div class="flex-1 h-2 bg-cream rounded-full overflow-hidden">
              <div class="h-full bg-teal rounded-full" style="width: 72%"></div>
            </div>
            <span class="text-xs font-semibold text-teal">72%</span>
          </div>
        </div>

        <!-- Timeline entry card -->
        <div class="float-medium bg-white rounded-2xl shadow-lg shadow-black/5 border border-black/5 p-4 ml-6 rotate-2">
          <div class="text-[10px] text-muted mb-1.5">Today, 3:15 PM</div>
          <div class="text-xs text-dark font-medium leading-relaxed">
            "Worked on backhand dinks and third shot drops for an hour"
          </div>
          <div class="mt-2 flex gap-1.5">
            <span class="text-[10px] bg-teal/10 text-teal px-2 py-0.5 rounded-full font-medium">+3% Dinking</span>
            <span class="text-[10px] bg-teal/10 text-teal px-2 py-0.5 rounded-full font-medium">+5% Drops</span>
          </div>
        </div>
      </div>

      <!-- Right UI elements -->
      <div class="hidden lg:block absolute right-0 top-4 w-64">
        <!-- AI coach card -->
        <div class="float-medium bg-white rounded-2xl shadow-lg shadow-black/5 border border-black/5 p-4 mb-4 rotate-3">
          <div class="flex items-center gap-2 mb-2">
            <div class="w-6 h-6 rounded-full bg-dark flex items-center justify-center">
              <span class="text-[10px]">🤖</span>
            </div>
            <span class="text-xs font-semibold text-dark">AI Coach</span>
          </div>
          <div class="text-xs text-muted leading-relaxed">
            "Great session! Your dinking consistency is improving. Try the cross-court drill next."
          </div>
        </div>

        <!-- Drill card -->
        <div class="float-slow bg-white rounded-2xl shadow-lg shadow-black/5 border border-black/5 p-4 ml-4 -rotate-2">
          <div class="flex items-center justify-between mb-2">
            <span class="text-xs font-semibold text-dark">Cross-Court Dinks</span>
            <span class="text-[10px] bg-coral/10 text-coral px-2 py-0.5 rounded-full font-medium">High Priority</span>
          </div>
          <div class="text-[10px] text-muted mb-2">15 reps remaining</div>
          <div class="h-1.5 bg-cream rounded-full overflow-hidden">
            <div class="h-full bg-coral rounded-full" style="width: 40%"></div>
          </div>
        </div>
      </div>

      <!-- Center content -->
      <div class="text-center max-w-2xl mx-auto relative z-10">
        <h1 class="fade-up text-5xl md:text-7xl font-bold font-rounded text-dark tracking-tight leading-[1.1]">
          Track, rate, improve.<br />
          All in one app.
        </h1>
        <p class="fade-up fade-up-delay-1 mt-8 text-lg md:text-xl text-muted font-rounded leading-relaxed max-w-lg mx-auto">
          Rate your pickleball game, track progress with custom checklists, and watch yourself improve over time.
        </p>
        <div class="fade-up fade-up-delay-2 mt-10">
          <a
            href="https://apps.apple.com/app/brine"
            target="_blank"
            rel="noopener"
            class="inline-flex items-center justify-center gap-2.5 bg-dark text-white font-rounded font-medium px-7 py-3.5 rounded-full hover:bg-dark/85 transition-colors text-base"
          >
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="currentColor">
              <path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/>
            </svg>
            Download on iOS
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
