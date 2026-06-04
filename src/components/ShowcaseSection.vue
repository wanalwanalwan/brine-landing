<template>
  <section class="py-16 md:py-24 px-6 md:px-8">
    <div class="max-w-6xl mx-auto">
      <h2 class="fade-up text-3xl md:text-5xl font-bold font-rounded text-dark tracking-tight leading-[1.1]">
        All in one app.<br />Built to make you better.
      </h2>

      <!-- Bento grid -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-3 md:gap-4 mt-10 md:mt-16">

        <!-- Your AI Coach — tall card, spans 2 rows -->
        <div class="fade-up fade-up-delay-1 md:row-span-2 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="flex-1 bg-dark p-7 flex flex-col justify-center">
            <div class="space-y-5">
              <!-- Log sessions -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-teal flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"/>
                  </svg>
                </div>
                <div>
                  <div class="text-white font-semibold text-[13px]">Log Your Sessions</div>
                  <div class="text-white/50 text-xs leading-relaxed">Describe what you practiced. Skills update instantly.</div>
                </div>
              </div>
              <!-- AI coach -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-teal flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/>
                  </svg>
                </div>
                <div>
                  <div class="flex items-center gap-2">
                    <span class="text-white font-semibold text-[13px]">AI Coach</span>
                    <span class="text-[9px] text-white/40 border border-white/20 rounded px-1.5 py-0.5 font-medium">AI</span>
                  </div>
                  <div class="text-white/50 text-xs leading-relaxed">Get instant feedback and a drill plan after every session.</div>
                </div>
              </div>
              <!-- Real coach -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-[#A78BFA] flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"/>
                  </svg>
                </div>
                <div>
                  <div class="text-white font-semibold text-[13px]">Talk to Real Coaches</div>
                  <div class="text-white/50 text-xs leading-relaxed">Get expert advice with quick response times.</div>
                </div>
              </div>
              <!-- Personalized schedule -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-coral flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"/>
                  </svg>
                </div>
                <div>
                  <div class="text-white font-semibold text-[13px]">Personalized Schedules</div>
                  <div class="text-white/50 text-xs leading-relaxed">A drill plan built around your weakest skills, day by day.</div>
                </div>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Everything in one app</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Sessions, AI coaching, real coaches, schedules, and skill tracking — all connected.</p>
          </div>
        </div>

        <!-- Talk to a Real Coach — top middle -->
        <div class="fade-up fade-up-delay-2 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-center justify-center overflow-hidden">
            <div class="bg-white rounded-2xl shadow-sm border border-black/5 p-4 w-full max-w-[210px]">
              <div class="flex items-center gap-2 mb-2.5">
                <div class="w-7 h-7 rounded-full bg-[#A78BFA] flex items-center justify-center text-white font-bold text-[10px] shrink-0">JR</div>
                <span class="text-[11px] font-semibold text-dark">Coach Jordan</span>
                <span class="w-1.5 h-1.5 rounded-full bg-success ml-auto"></span>
              </div>
              <div class="bg-[#f5f5f5] rounded-lg p-2.5 text-[9px] text-dark leading-snug mb-2">
                "Your volleys are at 48% — you're swinging too hard at the kitchen. Try blocking instead of driving under pressure."
              </div>
              <div class="flex gap-1.5">
                <span class="text-[8px] bg-coral/10 text-coral px-2 py-0.5 rounded-full font-medium">Volleys 48%</span>
                <span class="text-[8px] bg-teal/10 text-teal px-2 py-0.5 rounded-full font-medium">Replied in 5 min</span>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Talk to Real Coaches</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Get expert advice with quick response times from coaches who know your stats.</p>
          </div>
        </div>

        <!-- Log Your Sessions — top right -->
        <div class="fade-up fade-up-delay-3 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-center justify-center overflow-hidden">
            <div class="bg-white rounded-xl px-4 py-3.5 shadow-sm border border-black/5 w-full max-w-[200px]">
              <div class="text-[9px] text-muted mb-1.5">Today · 3:15 PM</div>
              <div class="text-[11px] text-dark font-medium leading-snug mb-2.5">"Worked on dinks and third shot drops for an hour"</div>
              <div class="flex gap-1.5 flex-wrap">
                <span class="text-[9px] bg-teal/10 text-teal px-2 py-0.5 rounded-full font-medium">Dinking +3%</span>
                <span class="text-[9px] bg-teal/10 text-teal px-2 py-0.5 rounded-full font-medium">Drops +5%</span>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Log Your Sessions</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Just describe what you practiced.<br/>Skills update automatically.</p>
          </div>
        </div>

        <!-- Personalized Schedule — bottom middle -->
        <div class="fade-up fade-up-delay-3 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-center justify-center overflow-hidden">
            <div class="w-full max-w-[200px] space-y-1.5">
              <div class="bg-success/10 rounded-lg px-3 py-2">
                <div class="flex items-center justify-between">
                  <span class="text-[9px] text-muted">Mon</span>
                  <span class="text-[9px] text-success font-semibold">Done ✓</span>
                </div>
                <span class="text-[10px] font-semibold text-dark/40 line-through">Cross-Court Dinks</span>
              </div>
              <div class="bg-teal/10 rounded-lg px-3 py-2 border border-teal/20">
                <div class="flex items-center justify-between">
                  <span class="text-[9px] text-teal font-semibold">Today</span>
                  <span class="text-[7px] bg-teal text-white px-1.5 py-0.5 rounded-full font-semibold">Up Next</span>
                </div>
                <span class="text-[10px] font-semibold text-dark">Third Shot Drops</span>
              </div>
              <div class="bg-white rounded-lg px-3 py-2 border border-black/5">
                <span class="text-[9px] text-muted">Wed</span>
                <div class="text-[10px] font-semibold text-dark">Serve Placement</div>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Personalized Schedules</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">A drill plan built for you,<br/>focused on your weak spots.</p>
          </div>
        </div>

        <!-- Skill Tracking — bottom right -->
        <div class="fade-up fade-up-delay-4 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-center justify-center overflow-hidden">
            <div class="w-full max-w-[180px]">
              <div class="space-y-2">
                <div>
                  <div class="flex items-center justify-between mb-1">
                    <span class="text-[10px] font-semibold text-dark">Dinking</span>
                    <span class="text-[10px] font-bold text-teal">72%</span>
                  </div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-teal rounded-full" style="width: 72%"></div>
                  </div>
                </div>
                <div>
                  <div class="flex items-center justify-between mb-1">
                    <span class="text-[10px] font-semibold text-dark">Drives</span>
                    <span class="text-[10px] font-bold text-teal">82%</span>
                  </div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-teal rounded-full" style="width: 82%"></div>
                  </div>
                </div>
                <div>
                  <div class="flex items-center justify-between mb-1">
                    <span class="text-[10px] font-semibold text-dark">Volleys</span>
                    <span class="text-[10px] font-bold text-coral">48%</span>
                  </div>
                  <div class="h-1.5 bg-white rounded-full overflow-hidden">
                    <div class="h-full bg-coral rounded-full" style="width: 48%"></div>
                  </div>
                </div>
              </div>
              <div class="flex items-baseline gap-1 mt-3">
                <span class="text-lg font-bold text-teal">68%</span>
                <span class="text-xs text-success font-semibold">↑ 8% this week</span>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Skill Tracking</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Every skill rated 0–100%.<br/>Watch your progress over time.</p>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>
