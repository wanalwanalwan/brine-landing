<template>
  <div class="pt-14 px-3 pb-3 h-full flex flex-col">
    <!-- Nav bar -->
    <div class="flex items-center justify-between mb-3">
      <svg class="w-4 h-4 text-muted" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7" />
      </svg>
      <span class="text-[13px] font-semibold text-dark">Coach Jordan</span>
      <div class="w-4"></div>
    </div>

    <!-- Chat messages -->
    <div class="flex-1 space-y-2.5 overflow-hidden">
      <!-- User -->
      <div class="flex justify-end">
        <div class="bg-teal text-white text-[10px] leading-snug rounded-2xl rounded-br-sm px-2.5 py-2 max-w-[82%]">
          I keep losing points at the kitchen line. Not sure what I'm doing wrong.
        </div>
      </div>

      <!-- Coach insight -->
      <div class="flex justify-start">
        <div class="bg-[#f0f0f0] text-dark text-[10px] leading-snug rounded-2xl rounded-bl-sm px-2.5 py-2 max-w-[90%]">
          <p class="mb-2">Your volley rating is at 48% — that tracks. A few things I'm seeing:</p>
          <div class="space-y-1.5 text-[9px]">
            <div class="flex gap-1.5">
              <span class="text-coral font-bold shrink-0">→</span>
              <span>You're hitting volleys too hard. Soft hands at the kitchen win more points.</span>
            </div>
            <div class="flex gap-1.5">
              <span class="text-coral font-bold shrink-0">→</span>
              <span>Try resetting with a block volley instead of driving when under pressure.</span>
            </div>
          </div>
        </div>
      </div>

      <!-- User -->
      <div class="flex justify-end">
        <div class="bg-teal text-white text-[10px] leading-snug rounded-2xl rounded-br-sm px-2.5 py-2 max-w-[82%]">
          That makes sense. What should I drill?
        </div>
      </div>

      <!-- Coach drill rec -->
      <div class="flex justify-start">
        <div class="bg-[#f0f0f0] text-dark text-[10px] leading-snug rounded-2xl rounded-bl-sm px-2.5 py-2 max-w-[90%]">
          <p class="mb-1.5">Start with this:</p>
          <div class="bg-white rounded-lg px-2.5 py-2 border border-black/5">
            <div class="font-semibold text-teal text-[9px]">Soft Block Volleys</div>
            <div class="text-[9px] text-muted">3 sets × 15 reps — focus on zero backswing</div>
          </div>
        </div>
      </div>
    </div>

    <!-- Response time indicator -->
    <div class="mt-1.5 flex items-center justify-center gap-1">
      <span class="w-1 h-1 rounded-full bg-success"></span>
      <span class="text-[8px] text-success font-medium">Typically replies in minutes</span>
    </div>

    <!-- Input bar -->
    <div class="mt-1.5 bg-[#f5f5f5] rounded-full px-3 py-1.5 text-[10px] text-muted">
      Ask your coach anything...
    </div>
  </div>
</template>
