<template>
  <div class="pt-14 px-3 pb-3 h-full">
    <!-- Large title -->
    <h2 class="text-[17px] font-bold text-dark mb-3">Timeline</h2>

    <!-- Today section -->
    <div class="mb-3">
      <div class="text-[10px] font-semibold text-muted uppercase tracking-wide mb-2">Today</div>
      <div class="space-y-2">
        <!-- Session entry -->
        <div class="flex gap-2">
          <div class="w-5 h-5 rounded-full bg-teal flex items-center justify-center shrink-0 mt-0.5">
            <svg class="w-2.5 h-2.5 text-white" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
            </svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="flex items-baseline justify-between">
              <span class="text-[10px] font-semibold text-dark">Session Logged</span>
              <span class="text-[9px] text-muted">2:30 PM</span>
            </div>
            <p class="text-[9px] text-muted leading-snug mt-0.5">Dinking and drops practice</p>
          </div>
        </div>
        <!-- Skill update -->
        <div class="flex gap-2">
          <div class="w-5 h-5 rounded-full bg-success flex items-center justify-center shrink-0 mt-0.5">
            <svg class="w-2.5 h-2.5 text-white" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" />
            </svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="flex items-baseline justify-between">
              <span class="text-[10px] font-semibold text-dark">Skills Updated</span>
              <span class="text-[9px] text-muted">2:31 PM</span>
            </div>
            <div class="flex gap-2 mt-0.5">
              <span class="text-[9px] text-success font-medium">Dinking +4%</span>
              <span class="text-[9px] text-success font-medium">Drops +6%</span>
            </div>
          </div>
        </div>
        <!-- AI insight -->
        <div class="flex gap-2">
          <div class="w-5 h-5 rounded-full bg-coral flex items-center justify-center shrink-0 mt-0.5">
            <svg class="w-2.5 h-2.5 text-white" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
            </svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="flex items-baseline justify-between">
              <span class="text-[10px] font-semibold text-dark">AI Insight</span>
              <span class="text-[9px] text-muted">2:31 PM</span>
            </div>
            <p class="text-[9px] text-muted leading-snug mt-0.5">Focus on drop consistency next</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Yesterday section -->
    <div>
      <div class="text-[10px] font-semibold text-muted uppercase tracking-wide mb-2">Yesterday</div>
      <div class="flex gap-2">
        <div class="w-5 h-5 rounded-full bg-teal flex items-center justify-center shrink-0 mt-0.5">
          <svg class="w-2.5 h-2.5 text-white" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
          </svg>
        </div>
        <div class="flex-1 min-w-0">
          <div class="flex items-baseline justify-between">
            <span class="text-[10px] font-semibold text-dark">Session Logged</span>
            <span class="text-[9px] text-muted">11:00 AM</span>
          </div>
          <p class="text-[9px] text-muted leading-snug mt-0.5">Open play, 3 games</p>
        </div>
      </div>
    </div>
  </div>
</template>
