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

    <!-- Coach profile -->
    <div class="flex items-center gap-2.5 mb-3 bg-[#f5f5f5] rounded-xl px-3 py-2.5">
      <div class="w-8 h-8 rounded-full bg-[#A78BFA] flex items-center justify-center text-white font-bold text-[11px] shrink-0">JR</div>
      <div class="flex-1 min-w-0">
        <div class="text-[11px] font-semibold text-dark">Coach Jordan R.</div>
        <div class="text-[9px] text-teal font-medium">● Available now</div>
      </div>
      <div class="text-[9px] text-muted shrink-0">4.9 ★</div>
    </div>

    <!-- Chat messages -->
    <div class="flex-1 space-y-2.5 overflow-hidden">
      <!-- Coach message -->
      <div class="flex justify-start">
        <div class="bg-[#f0f0f0] text-dark text-[10px] leading-snug rounded-2xl rounded-bl-sm px-2.5 py-2 max-w-[88%]">
          I reviewed your stats — dinking is coming along! Let's lock in those volleys next session.
        </div>
      </div>

      <!-- User -->
      <div class="flex justify-end">
        <div class="bg-teal text-white text-[10px] leading-snug rounded-2xl rounded-br-sm px-2.5 py-2 max-w-[82%]">
          When can we meet?
        </div>
      </div>

      <!-- Coach booking reply -->
      <div class="flex justify-start">
        <div class="bg-[#f0f0f0] text-dark text-[10px] leading-snug rounded-2xl rounded-bl-sm px-2.5 py-2 max-w-[88%]">
          <p class="mb-2">I have these slots open:</p>
          <div class="bg-white rounded-lg px-2.5 py-2 border border-black/5 space-y-2">
            <div class="flex items-center justify-between">
              <span class="text-[9px] text-dark font-medium">Thu, Jun 5 · 10am</span>
              <span class="text-[8px] bg-teal text-white px-2 py-0.5 rounded-full font-medium">Book</span>
            </div>
            <div class="flex items-center justify-between">
              <span class="text-[9px] text-dark font-medium">Fri, Jun 6 · 2pm</span>
              <span class="text-[8px] bg-teal text-white px-2 py-0.5 rounded-full font-medium">Book</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Input bar -->
    <div class="mt-2 bg-[#f5f5f5] rounded-full px-3 py-1.5 text-[10px] text-muted">
      Message your coach...
    </div>
  </div>
</template>
