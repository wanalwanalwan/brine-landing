<template>
  <section class="py-24 px-8">
    <div class="max-w-6xl mx-auto">
      <div class="fade-up mb-16">
        <div class="border-b border-black/8"></div>
      </div>
      <h2 class="fade-up text-4xl md:text-5xl font-bold font-rounded text-dark tracking-tight leading-[1.1]">
        Know your game<br />inside out.
      </h2>

      <!-- Bento grid -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mt-16">

        <!-- Your AI Coach — tall card, spans 2 rows -->
        <div class="fade-up fade-up-delay-1 md:row-span-2 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="flex-1 bg-dark p-7 flex flex-col justify-center">
            <div class="space-y-5">
              <!-- Log -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-teal flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"/>
                  </svg>
                </div>
                <div>
                  <div class="text-white font-semibold text-[13px]">Log What You Practiced</div>
                  <div class="text-white/50 text-xs leading-relaxed">Just tell it what you worked on. Plain English.</div>
                </div>
              </div>
              <!-- See changes -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-teal flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"/>
                  </svg>
                </div>
                <div>
                  <div class="text-white font-semibold text-[13px]">See What Changed</div>
                  <div class="text-white/50 text-xs leading-relaxed">Skills update instantly. See gains and gaps.</div>
                </div>
              </div>
              <!-- Get drills -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-coral flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/>
                  </svg>
                </div>
                <div>
                  <div class="flex items-center gap-2">
                    <span class="text-white font-semibold text-[13px]">Get Your Next Drill</span>
                    <span class="text-[9px] text-white/40 border border-white/20 rounded px-1.5 py-0.5 font-medium">AI</span>
                  </div>
                  <div class="text-white/50 text-xs leading-relaxed">Practice plans built around your weakest skills.</div>
                </div>
              </div>
              <!-- Track progress -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-[#A78BFA] flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"/>
                  </svg>
                </div>
                <div>
                  <div class="text-white font-semibold text-[13px]">Watch Yourself Improve</div>
                  <div class="text-white/50 text-xs leading-relaxed">Every session tracked. Progress you can see.</div>
                </div>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Your AI Coach</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Tell Brine what you practiced. It finds your weaknesses and tells you what to work on.</p>
          </div>
        </div>

        <!-- Spot Your Weaknesses — top middle -->
        <div class="fade-up fade-up-delay-2 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-center justify-center overflow-hidden">
            <!-- Weakness indicator in coral -->
            <div class="bg-white rounded-full border-2 border-coral/20 px-5 py-3 flex items-center gap-3 shadow-sm">
              <svg class="w-7 h-7 shrink-0" viewBox="0 0 36 36">
                <circle cx="18" cy="18" r="15" fill="none" stroke="#e5e7eb" stroke-width="3"/>
                <circle cx="18" cy="18" r="15" fill="none" stroke="#E8756A" stroke-width="3" stroke-dasharray="94.2" stroke-dashoffset="45.2" stroke-linecap="round" transform="rotate(-90 18 18)"/>
              </svg>
              <span class="text-sm font-bold text-dark whitespace-nowrap">Drives 52%</span>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Spot Your Weaknesses</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Every skill rated 0-100%.<br/>See exactly where you need work.</p>
          </div>
        </div>

        <!-- See What Improved — top right -->
        <div class="fade-up fade-up-delay-3 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-end justify-end overflow-hidden">
            <!-- Improvement list, offset to crop at edge -->
            <div class="bg-white rounded-xl px-4 py-3.5 shadow-sm border border-black/5 translate-x-5">
              <div class="flex items-center gap-2.5 mb-3">
                <div class="w-4 h-4 rounded-full bg-success flex items-center justify-center shrink-0">
                  <svg class="w-2.5 h-2.5 text-white" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                </div>
                <span class="text-xs font-semibold text-success">Dinking +3%</span>
                <span class="text-[10px] text-muted ml-4 whitespace-nowrap">Jul 15 · 2:30p</span>
              </div>
              <div class="flex items-center gap-2.5 mb-3">
                <div class="w-4 h-4 rounded-full bg-success flex items-center justify-center shrink-0">
                  <svg class="w-2.5 h-2.5 text-white" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                </div>
                <span class="text-xs font-semibold text-success">Drops +5%</span>
              </div>
              <div class="flex items-center gap-2.5">
                <div class="w-4 h-4 rounded-full border-2 border-black/10 shrink-0"></div>
                <span class="text-xs text-muted">Defense —</span>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">See What Improved</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">After every session, see exactly<br/>what changed and by how much.</p>
          </div>
        </div>

        <!-- Know What to Practice — bottom middle -->
        <div class="fade-up fade-up-delay-3 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-center justify-center overflow-hidden">
            <!-- Drill stat mockup -->
            <div class="flex items-center gap-4">
              <div class="text-right">
                <div class="text-xl font-bold text-dark leading-tight">3 sets</div>
                <div class="text-sm text-muted">× 10 reps</div>
              </div>
              <div class="flex flex-col gap-1.5">
                <div class="w-8 h-8 rounded-full bg-teal flex items-center justify-center">
                  <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z" clip-rule="evenodd"/></svg>
                </div>
                <div class="w-8 h-8 rounded-full bg-coral flex items-center justify-center">
                  <div class="w-2 h-2 rounded-full bg-white"></div>
                </div>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Know What to Practice</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">AI drills that target your<br/>weakest skills first.</p>
          </div>
        </div>

        <!-- Proof You're Improving — bottom right -->
        <div class="fade-up fade-up-delay-4 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-center justify-center overflow-hidden">
            <!-- Upward trend line -->
            <div class="translate-x-4">
              <svg class="w-40 h-20" viewBox="0 0 160 80">
                <polyline points="0,65 25,60 50,52 75,48 100,35 125,25 150,12" fill="none" stroke="#2AA6A0" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
                <circle cx="150" cy="12" r="4" fill="#2AA6A0"/>
              </svg>
              <div class="flex items-baseline gap-1 mt-2">
                <span class="text-lg font-bold text-teal">74%</span>
                <span class="text-xs text-success font-semibold">↑ 12%</span>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Proof You're Improving</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Watch your ratings climb over<br/>weeks and months.</p>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>
