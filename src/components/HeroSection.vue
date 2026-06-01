<template>
  <section class="hero-section pt-16 md:pt-20 pb-16 md:pb-24 px-6 md:px-8 overflow-hidden">

    <div class="max-w-6xl mx-auto relative">
      <!-- Left UI elements (desktop only) -->
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

        <!-- Real coach card -->
        <div class="float-slow bg-white rounded-2xl shadow-lg shadow-black/5 border border-black/5 p-4 -ml-2 -rotate-1 mt-4">
          <div class="flex items-center gap-2 mb-2">
            <div class="w-7 h-7 rounded-full bg-[#A78BFA] flex items-center justify-center text-white text-[10px] font-bold">JR</div>
            <div>
              <div class="text-xs font-semibold text-dark">Coach Jordan</div>
              <div class="text-[9px] text-teal font-medium">● Available now</div>
            </div>
          </div>
          <div class="text-[10px] text-muted leading-snug">"Let's work on your volleys — I've reviewed your progress."</div>
        </div>
      </div>

      <!-- Right UI elements (desktop only) -->
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
            "Your Drops are at 52%. Try cross-court dinks — 3 sets of 10 reps."
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

        <!-- Progress card -->
        <div class="float-medium bg-white rounded-2xl shadow-lg shadow-black/5 border border-black/5 p-4 -ml-2 rotate-1 mt-4">
          <div class="flex items-center gap-2 mb-2">
            <span class="text-sm">📈</span>
            <span class="text-xs font-semibold text-dark">Weekly Progress</span>
          </div>
          <div class="flex items-center gap-3">
            <div class="text-[10px] text-muted">Serves</div>
            <div class="flex-1 h-1.5 bg-cream rounded-full overflow-hidden">
              <div class="h-full bg-success rounded-full" style="width: 68%"></div>
            </div>
            <span class="text-[10px] font-semibold text-success">+8%</span>
          </div>
          <div class="flex items-center gap-3 mt-1.5">
            <div class="text-[10px] text-muted">Volleys</div>
            <div class="flex-1 h-1.5 bg-cream rounded-full overflow-hidden">
              <div class="h-full bg-success rounded-full" style="width: 45%"></div>
            </div>
            <span class="text-[10px] font-semibold text-success">+5%</span>
          </div>
        </div>
      </div>

      <!-- Center content -->
      <div class="text-center max-w-2xl mx-auto relative z-10">
        <h1 class="fade-up text-4xl md:text-7xl font-bold font-rounded text-dark tracking-tight leading-[1.1]">
          Your complete<br />
          pickleball coach.
        </h1>
        <p class="fade-up fade-up-delay-1 mt-6 md:mt-8 text-base md:text-xl text-muted font-rounded leading-relaxed max-w-lg mx-auto">
          Log sessions, get AI coaching, talk to real coaches, run targeted drills, and watch your progress — all in one place.
        </p>
        <div class="fade-up fade-up-delay-2 mt-8 md:mt-10">
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

      <!-- Mobile preview cards (visible below lg) -->
      <div class="lg:hidden flex gap-3 mt-10 overflow-x-auto pb-2 -mx-6 px-6 snap-x snap-mandatory scrollbar-hide">
        <!-- Skill card -->
        <div class="bg-white rounded-xl shadow-sm shadow-black/5 border border-black/5 p-3.5 min-w-[200px] snap-start shrink-0">
          <div class="flex items-center gap-2.5 mb-2">
            <div class="w-7 h-7 rounded-full bg-teal/10 flex items-center justify-center text-xs">🎯</div>
            <div>
              <div class="text-[11px] font-semibold text-dark">Dinking</div>
              <div class="text-[9px] text-muted">Updated today</div>
            </div>
          </div>
          <div class="flex items-center gap-2">
            <div class="flex-1 h-1.5 bg-cream rounded-full overflow-hidden">
              <div class="h-full bg-teal rounded-full" style="width: 72%"></div>
            </div>
            <span class="text-[10px] font-semibold text-teal">72%</span>
          </div>
        </div>

        <!-- AI Coach card -->
        <div class="bg-white rounded-xl shadow-sm shadow-black/5 border border-black/5 p-3.5 min-w-[200px] snap-start shrink-0">
          <div class="flex items-center gap-1.5 mb-1.5">
            <div class="w-5 h-5 rounded-full bg-dark flex items-center justify-center">
              <span class="text-[8px]">🤖</span>
            </div>
            <span class="text-[11px] font-semibold text-dark">AI Coach</span>
          </div>
          <div class="text-[10px] text-muted leading-snug">
            "Your Drops are at 52%. Try cross-court dinks."
          </div>
        </div>

        <!-- Timeline card -->
        <div class="bg-white rounded-xl shadow-sm shadow-black/5 border border-black/5 p-3.5 min-w-[200px] snap-start shrink-0">
          <div class="text-[9px] text-muted mb-1">Today, 3:15 PM</div>
          <div class="text-[10px] text-dark font-medium leading-snug">
            "Worked on dinks and drops for an hour"
          </div>
          <div class="mt-1.5 flex gap-1">
            <span class="text-[9px] bg-teal/10 text-teal px-1.5 py-0.5 rounded-full font-medium">+3% Dinking</span>
            <span class="text-[9px] bg-teal/10 text-teal px-1.5 py-0.5 rounded-full font-medium">+5% Drops</span>
          </div>
        </div>

        <!-- Drill card -->
        <div class="bg-white rounded-xl shadow-sm shadow-black/5 border border-black/5 p-3.5 min-w-[200px] snap-start shrink-0">
          <div class="flex items-center justify-between mb-1.5">
            <span class="text-[11px] font-semibold text-dark">Cross-Court Dinks</span>
            <span class="text-[8px] bg-coral/10 text-coral px-1.5 py-0.5 rounded-full font-medium">Priority</span>
          </div>
          <div class="text-[9px] text-muted mb-1.5">15 reps remaining</div>
          <div class="h-1 bg-cream rounded-full overflow-hidden">
            <div class="h-full bg-coral rounded-full" style="width: 40%"></div>
          </div>
        </div>

        <!-- Real Coach card -->
        <div class="bg-white rounded-xl shadow-sm shadow-black/5 border border-black/5 p-3.5 min-w-[200px] snap-start shrink-0">
          <div class="flex items-center gap-1.5 mb-1.5">
            <div class="w-5 h-5 rounded-full bg-[#A78BFA] flex items-center justify-center text-white text-[8px] font-bold shrink-0">JR</div>
            <span class="text-[11px] font-semibold text-dark">Real Coach</span>
            <span class="text-[8px] text-teal font-medium ml-auto">● Online</span>
          </div>
          <div class="text-[9px] text-muted leading-snug">"Let's work on your volleys next session."</div>
        </div>

        <!-- Progress card -->
        <div class="bg-white rounded-xl shadow-sm shadow-black/5 border border-black/5 p-3.5 min-w-[200px] snap-start shrink-0">
          <div class="flex items-center gap-1.5 mb-1.5">
            <span class="text-xs">📈</span>
            <span class="text-[11px] font-semibold text-dark">Weekly Progress</span>
          </div>
          <div class="flex items-center gap-2">
            <div class="text-[9px] text-muted">Serves</div>
            <div class="flex-1 h-1 bg-cream rounded-full overflow-hidden">
              <div class="h-full bg-success rounded-full" style="width: 68%"></div>
            </div>
            <span class="text-[9px] font-semibold text-success">+8%</span>
          </div>
          <div class="flex items-center gap-2 mt-1">
            <div class="text-[9px] text-muted">Volleys</div>
            <div class="flex-1 h-1 bg-cream rounded-full overflow-hidden">
              <div class="h-full bg-success rounded-full" style="width: 45%"></div>
            </div>
            <span class="text-[9px] font-semibold text-success">+5%</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
