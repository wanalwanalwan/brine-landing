<template>
  <div class="pt-14 px-3 pb-3 h-full flex flex-col">
    <!-- Nav bar -->
    <div class="flex items-center justify-between mb-3">
      <svg class="w-4 h-4 text-muted" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7" />
      </svg>
      <span class="text-[13px] font-semibold text-dark">AI Coach</span>
      <div class="w-4"></div>
    </div>

    <!-- Chat messages -->
    <div class="flex-1 space-y-2.5 overflow-hidden">
      <!-- User message -->
      <div class="flex justify-end">
        <div class="bg-teal text-white text-[10px] leading-snug rounded-2xl rounded-br-sm px-2.5 py-2 max-w-[82%]">
          Played for an hour today. Worked on dinking and third shot drops.
        </div>
      </div>

      <!-- AI response with skill updates -->
      <div class="flex justify-start">
        <div class="bg-[#f0f0f0] text-dark text-[10px] leading-snug rounded-2xl rounded-bl-sm px-2.5 py-2 max-w-[88%]">
          <p class="mb-1.5">Nice session! Updated your ratings:</p>
          <div class="space-y-1 text-[9px]">
            <div class="flex items-center gap-1.5">
              <span class="text-success font-bold">↑</span>
              <span class="font-medium">Dinking</span>
              <span class="text-muted ml-auto">68% → 72%</span>
            </div>
            <div class="flex items-center gap-1.5">
              <span class="text-success font-bold">↑</span>
              <span class="font-medium">3rd Shot Drop</span>
              <span class="text-muted ml-auto">54% → 60%</span>
            </div>
          </div>
          <p class="mt-1.5 text-muted">Focus on drop consistency next.</p>
        </div>
      </div>

      <!-- User follow-up -->
      <div class="flex justify-end">
        <div class="bg-teal text-white text-[10px] leading-snug rounded-2xl rounded-br-sm px-2.5 py-2 max-w-[82%]">
          What drills should I do?
        </div>
      </div>

      <!-- AI drill suggestion -->
      <div class="flex justify-start">
        <div class="bg-[#f0f0f0] text-dark text-[10px] leading-snug rounded-2xl rounded-bl-sm px-2.5 py-2 max-w-[88%]">
          <p class="font-medium mb-1.5">Your practice plan:</p>
          <div class="bg-white rounded-lg px-2.5 py-2 border border-black/5">
            <div class="font-semibold text-teal text-[9px]">Cross-Court Dinks</div>
            <div class="text-[9px] text-muted">3 sets &times; 10 reps</div>
          </div>
        </div>
      </div>
    </div>

    <!-- Input bar -->
    <div class="mt-2 bg-[#f5f5f5] rounded-full px-3 py-1.5 text-[10px] text-muted">
      Tell me about your session...
    </div>
  </div>
</template>
