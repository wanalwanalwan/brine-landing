<template>
  <section class="py-16 md:py-24 px-6 md:px-8">
    <div class="max-w-6xl mx-auto">
      <div class="fade-up mb-12 md:mb-16">
        <div class="border-b border-black/8"></div>
      </div>
      <h2 class="fade-up text-3xl md:text-5xl font-bold font-rounded text-dark tracking-tight leading-[1.1]">
        Everything you need<br />to level up.
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
                  <div class="text-white font-semibold text-[13px]">Talk to a Real Coach</div>
                  <div class="text-white/50 text-xs leading-relaxed">Book sessions with certified coaches who review your data.</div>
                </div>
              </div>
              <!-- Drills + Progress -->
              <div class="flex items-start gap-3.5">
                <div class="w-9 h-9 rounded-full bg-coral flex items-center justify-center shrink-0">
                  <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"/>
                  </svg>
                </div>
                <div>
                  <div class="text-white font-semibold text-[13px]">Drills & Progress Checker</div>
                  <div class="text-white/50 text-xs leading-relaxed">Targeted drills for your weaknesses. Watch every skill climb.</div>
                </div>
              </div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Everything in one app</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Sessions, AI coaching, real coaches, drills, and progress tracking — all connected.</p>
          </div>
        </div>

        <!-- Talk to a Real Coach — top middle -->
        <div class="fade-up fade-up-delay-2 rounded-[20px] border border-black/8 overflow-hidden flex flex-col">
          <div class="bg-cream min-h-[200px] p-6 flex items-center justify-center overflow-hidden">
            <div class="bg-white rounded-2xl shadow-sm border border-black/5 p-4 w-full max-w-[200px]">
              <div class="flex items-center gap-2.5 mb-3">
                <div class="w-9 h-9 rounded-full bg-[#A78BFA] flex items-center justify-center text-white font-bold text-[11px] shrink-0">JR</div>
                <div>
                  <div class="text-xs font-semibold text-dark">Coach Jordan</div>
                  <div class="text-[9px] text-teal font-medium">● Available now</div>
                </div>
              </div>
              <div class="bg-[#f5f5f5] rounded-lg p-2.5 text-[9px] text-muted leading-snug mb-2.5">
                "I reviewed your stats — let's work on those volleys next."
              </div>
              <div class="bg-dark text-white text-[9px] font-semibold text-center rounded-full py-1.5">Book a Session</div>
            </div>
          </div>
          <div class="p-5 pt-4">
            <h3 class="text-lg font-bold font-rounded text-dark">Talk to a Real Coach</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Book sessions with certified coaches who already know your game.</p>
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
            <h3 class="text-lg font-bold font-rounded text-dark">Drills</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">AI-generated drills targeting<br/>your weakest skills first.</p>
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
            <h3 class="text-lg font-bold font-rounded text-dark">Progress Checker</h3>
            <p class="text-sm text-muted font-rounded leading-relaxed mt-1">Watch every skill climb over<br/>weeks and months.</p>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>
