<template>
  <div class="pt-14 px-3 pb-3 h-full">
    <!-- Large title -->
    <h2 class="text-[17px] font-bold text-dark mb-3">My Skills</h2>

    <!-- Category tabs -->
    <div class="flex gap-1.5 mb-3">
      <span class="text-[9px] font-semibold bg-teal text-white px-2 py-0.5 rounded-full">All</span>
      <span class="text-[9px] font-medium text-muted bg-[#f0f0f0] px-2 py-0.5 rounded-full">Offense</span>
      <span class="text-[9px] font-medium text-muted bg-[#f0f0f0] px-2 py-0.5 rounded-full">Defense</span>
    </div>

    <!-- Skill cards -->
    <div class="space-y-2">
      <!-- Dinking -->
      <div class="bg-[#f9f9f9] rounded-xl px-3 py-2.5">
        <div class="flex items-center justify-between mb-1.5">
          <span class="text-[11px] font-semibold text-dark">Dinking</span>
          <div class="flex items-center gap-1">
            <span class="text-[10px] font-bold text-teal">72%</span>
            <span class="text-[8px] text-success font-semibold">+4</span>
          </div>
        </div>
        <div class="h-1.5 bg-[#e5e5e5] rounded-full overflow-hidden">
          <div class="h-full bg-teal rounded-full" style="width: 72%"></div>
        </div>
      </div>

      <!-- Third Shot Drop -->
      <div class="bg-[#f9f9f9] rounded-xl px-3 py-2.5">
        <div class="flex items-center justify-between mb-1.5">
          <span class="text-[11px] font-semibold text-dark">Third Shot Drop</span>
          <div class="flex items-center gap-1">
            <span class="text-[10px] font-bold text-teal">60%</span>
            <span class="text-[8px] text-success font-semibold">+6</span>
          </div>
        </div>
        <div class="h-1.5 bg-[#e5e5e5] rounded-full overflow-hidden">
          <div class="h-full bg-teal rounded-full" style="width: 60%"></div>
        </div>
      </div>

      <!-- Drives -->
      <div class="bg-[#f9f9f9] rounded-xl px-3 py-2.5">
        <div class="flex items-center justify-between mb-1.5">
          <span class="text-[11px] font-semibold text-dark">Drives</span>
          <span class="text-[10px] font-bold text-teal">82%</span>
        </div>
        <div class="h-1.5 bg-[#e5e5e5] rounded-full overflow-hidden">
          <div class="h-full bg-teal rounded-full" style="width: 82%"></div>
        </div>
      </div>

      <!-- Returns -->
      <div class="bg-[#f9f9f9] rounded-xl px-3 py-2.5">
        <div class="flex items-center justify-between mb-1.5">
          <span class="text-[11px] font-semibold text-dark">Returns</span>
          <span class="text-[10px] font-bold text-teal">79%</span>
        </div>
        <div class="h-1.5 bg-[#e5e5e5] rounded-full overflow-hidden">
          <div class="h-full bg-teal rounded-full" style="width: 79%"></div>
        </div>
      </div>

      <!-- Volleys -->
      <div class="bg-[#f9f9f9] rounded-xl px-3 py-2.5">
        <div class="flex items-center justify-between mb-1.5">
          <span class="text-[11px] font-semibold text-dark">Volleys</span>
          <div class="flex items-center gap-1">
            <span class="text-[10px] font-bold text-coral">48%</span>
            <span class="text-[8px] text-coral font-semibold">-2</span>
          </div>
        </div>
        <div class="h-1.5 bg-[#e5e5e5] rounded-full overflow-hidden">
          <div class="h-full bg-coral rounded-full" style="width: 48%"></div>
        </div>
      </div>
    </div>
  </div>
</template>
