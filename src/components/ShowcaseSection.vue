<template>
  <section class="py-24 px-8">
    <div class="max-w-6xl mx-auto">
      <div class="fade-up mb-16">
        <div class="border-b border-black/8"></div>
      </div>
      <h2 class="fade-up text-4xl md:text-5xl font-bold font-rounded text-dark tracking-tight leading-[1.1]">
        Track, rate, improve.<br />All in one place.
      </h2>

      <!-- 3-up phone mockups -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-16">

        <!-- Phone 1: AI Coach -->
        <div class="fade-up fade-up-delay-1 flex flex-col items-center">
          <div class="w-full max-w-[280px] aspect-[9/17] bg-dark rounded-[2.5rem] p-3 shadow-xl">
            <div class="w-full h-full bg-white rounded-[2rem] overflow-hidden flex flex-col">
              <!-- Status bar -->
              <div class="flex items-center justify-between px-5 pt-3 pb-1">
                <span class="text-[10px] font-semibold text-dark">9:41</span>
                <div class="flex gap-1 items-center">
                  <div class="w-3.5 h-2 border border-dark/30 rounded-sm">
                    <div class="w-2.5 h-full bg-dark/30 rounded-sm"></div>
                  </div>
                </div>
              </div>
              <!-- Header -->
              <div class="px-5 pt-2 pb-3 border-b border-black/5">
                <div class="text-sm font-semibold text-dark">AI Coach</div>
              </div>
              <!-- Chat content -->
              <div class="flex-1 px-4 py-3 space-y-3 overflow-hidden">
                <div class="bg-cream rounded-2xl rounded-tl-md px-3.5 py-2.5 max-w-[85%]">
                  <p class="text-[11px] text-dark leading-relaxed">Played doubles for an hour. Worked on my third shot drops and dinking consistency.</p>
                </div>
                <div class="bg-dark rounded-2xl rounded-tr-md px-3.5 py-2.5 max-w-[85%] ml-auto">
                  <p class="text-[11px] text-white leading-relaxed">Nice work! I've updated your Drops to 68% (+5%) and Dinking to 74% (+3%).</p>
                </div>
                <div class="bg-dark rounded-2xl rounded-tr-md px-3.5 py-2.5 max-w-[85%] ml-auto">
                  <p class="text-[11px] text-white leading-relaxed">Try this drill: Cross-court dinks, 3 sets of 10 reps.</p>
                </div>
              </div>
              <!-- Input bar -->
              <div class="px-4 pb-4 pt-2">
                <div class="h-9 bg-cream rounded-full flex items-center px-3.5">
                  <span class="text-[10px] text-muted">Log a session...</span>
                </div>
              </div>
            </div>
          </div>
          <div class="mt-5 flex items-center gap-2">
            <span class="w-5 h-5 rounded-full bg-teal/15 flex items-center justify-center">
              <span class="w-2 h-2 rounded-full bg-teal"></span>
            </span>
            <span class="text-sm font-semibold font-rounded text-teal">AI Coach</span>
          </div>
        </div>

        <!-- Phone 2: Skill Tracking -->
        <div class="fade-up fade-up-delay-2 flex flex-col items-center">
          <div class="w-full max-w-[280px] aspect-[9/17] bg-dark rounded-[2.5rem] p-3 shadow-xl">
            <div class="w-full h-full bg-white rounded-[2rem] overflow-hidden flex flex-col">
              <!-- Status bar -->
              <div class="flex items-center justify-between px-5 pt-3 pb-1">
                <span class="text-[10px] font-semibold text-dark">9:41</span>
                <div class="flex gap-1 items-center">
                  <div class="w-3.5 h-2 border border-dark/30 rounded-sm">
                    <div class="w-2.5 h-full bg-dark/30 rounded-sm"></div>
                  </div>
                </div>
              </div>
              <!-- Header -->
              <div class="px-5 pt-2 pb-3 border-b border-black/5">
                <div class="text-sm font-semibold text-dark">My Skills</div>
              </div>
              <!-- Skill list -->
              <div class="flex-1 px-4 py-3 space-y-2.5 overflow-hidden">
                <div class="bg-cream rounded-xl px-3.5 py-2.5">
                  <div class="flex items-center justify-between mb-1.5">
                    <div class="flex items-center gap-2">
                      <span class="text-sm">🎯</span>
                      <span class="text-[11px] font-semibold text-dark">Dinking</span>
                    </div>
                    <span class="text-[11px] font-bold text-teal">74%</span>
                  </div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-teal rounded-full" style="width: 74%"></div>
                  </div>
                </div>
                <div class="bg-cream rounded-xl px-3.5 py-2.5">
                  <div class="flex items-center justify-between mb-1.5">
                    <div class="flex items-center gap-2">
                      <span class="text-sm">⬇️</span>
                      <span class="text-[11px] font-semibold text-dark">Drops</span>
                    </div>
                    <span class="text-[11px] font-bold text-teal">68%</span>
                  </div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-teal rounded-full" style="width: 68%"></div>
                  </div>
                </div>
                <div class="bg-cream rounded-xl px-3.5 py-2.5">
                  <div class="flex items-center justify-between mb-1.5">
                    <div class="flex items-center gap-2">
                      <span class="text-sm">🚀</span>
                      <span class="text-[11px] font-semibold text-dark">Drives</span>
                    </div>
                    <span class="text-[11px] font-bold text-coral">52%</span>
                  </div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-coral rounded-full" style="width: 52%"></div>
                  </div>
                </div>
                <div class="bg-cream rounded-xl px-3.5 py-2.5">
                  <div class="flex items-center justify-between mb-1.5">
                    <div class="flex items-center gap-2">
                      <span class="text-sm">🛡️</span>
                      <span class="text-[11px] font-semibold text-dark">Defense</span>
                    </div>
                    <span class="text-[11px] font-bold text-teal">81%</span>
                  </div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-teal rounded-full" style="width: 81%"></div>
                  </div>
                </div>
                <div class="bg-cream rounded-xl px-3.5 py-2.5">
                  <div class="flex items-center justify-between mb-1.5">
                    <div class="flex items-center gap-2">
                      <span class="text-sm">♟️</span>
                      <span class="text-[11px] font-semibold text-dark">Strategy</span>
                    </div>
                    <span class="text-[11px] font-bold text-coral">45%</span>
                  </div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-coral rounded-full" style="width: 45%"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="mt-5 flex items-center gap-2">
            <span class="w-5 h-5 rounded-full bg-teal/15 flex items-center justify-center">
              <span class="w-2 h-2 rounded-full bg-teal"></span>
            </span>
            <span class="text-sm font-semibold font-rounded text-teal">Skills</span>
          </div>
        </div>

        <!-- Phone 3: Drills -->
        <div class="fade-up fade-up-delay-3 flex flex-col items-center">
          <div class="w-full max-w-[280px] aspect-[9/17] bg-dark rounded-[2.5rem] p-3 shadow-xl">
            <div class="w-full h-full bg-white rounded-[2rem] overflow-hidden flex flex-col">
              <!-- Status bar -->
              <div class="flex items-center justify-between px-5 pt-3 pb-1">
                <span class="text-[10px] font-semibold text-dark">9:41</span>
                <div class="flex gap-1 items-center">
                  <div class="w-3.5 h-2 border border-dark/30 rounded-sm">
                    <div class="w-2.5 h-full bg-dark/30 rounded-sm"></div>
                  </div>
                </div>
              </div>
              <!-- Header -->
              <div class="px-5 pt-2 pb-3 border-b border-black/5">
                <div class="text-sm font-semibold text-dark">Drill Queue</div>
              </div>
              <!-- Drill list -->
              <div class="flex-1 px-4 py-3 space-y-2.5 overflow-hidden">
                <div class="bg-cream rounded-xl px-3.5 py-3">
                  <div class="flex items-center justify-between mb-1">
                    <span class="text-[11px] font-semibold text-dark">Cross-Court Dinks</span>
                    <span class="text-[9px] bg-coral/10 text-coral px-2 py-0.5 rounded-full font-semibold">High</span>
                  </div>
                  <div class="text-[10px] text-muted mb-2">3 sets x 10 reps</div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-teal rounded-full" style="width: 60%"></div>
                  </div>
                </div>
                <div class="bg-cream rounded-xl px-3.5 py-3">
                  <div class="flex items-center justify-between mb-1">
                    <span class="text-[11px] font-semibold text-dark">Third Shot Drop</span>
                    <span class="text-[9px] bg-yellow-500/10 text-yellow-600 px-2 py-0.5 rounded-full font-semibold">Med</span>
                  </div>
                  <div class="text-[10px] text-muted mb-2">2 sets x 15 reps</div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-teal rounded-full" style="width: 30%"></div>
                  </div>
                </div>
                <div class="bg-cream rounded-xl px-3.5 py-3">
                  <div class="flex items-center justify-between mb-1">
                    <span class="text-[11px] font-semibold text-dark">Serve Placement</span>
                    <span class="text-[9px] bg-teal/10 text-teal px-2 py-0.5 rounded-full font-semibold">Low</span>
                  </div>
                  <div class="text-[10px] text-muted mb-2">4 sets x 5 reps</div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-teal rounded-full" style="width: 0%"></div>
                  </div>
                </div>
                <div class="bg-success/10 rounded-xl px-3.5 py-3">
                  <div class="flex items-center justify-between">
                    <span class="text-[11px] font-semibold text-dark line-through opacity-50">Reset Footwork</span>
                    <span class="text-[11px] text-success font-semibold">Done ✓</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="mt-5 flex items-center gap-2">
            <span class="w-5 h-5 rounded-full bg-teal/15 flex items-center justify-center">
              <span class="w-2 h-2 rounded-full bg-teal"></span>
            </span>
            <span class="text-sm font-semibold font-rounded text-teal">Drills</span>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>
