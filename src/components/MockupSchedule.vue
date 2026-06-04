<template>
  <div class="pt-14 px-3 pb-3 h-full">
    <!-- Large title -->
    <h2 class="text-[17px] font-bold text-dark mb-0.5">My Schedule</h2>
    <div class="text-[10px] text-muted mb-3">This Week</div>

    <!-- Schedule entries -->
    <div class="space-y-2">
      <!-- Monday — completed -->
      <div class="bg-success/8 rounded-xl px-3 py-2.5">
        <div class="flex items-center justify-between mb-0.5">
          <span class="text-[9px] text-muted font-medium">Monday</span>
          <span class="text-[10px] text-success font-semibold">Done ✓</span>
        </div>
        <span class="text-[11px] font-semibold text-dark/40 line-through">Cross-Court Dinks</span>
      </div>

      <!-- Tuesday — today, highlighted -->
      <div class="bg-teal/8 rounded-xl px-3 py-2.5 border border-teal/20">
        <div class="flex items-center justify-between mb-0.5">
          <span class="text-[9px] text-teal font-semibold">Today</span>
          <span class="text-[8px] bg-teal text-white px-1.5 py-0.5 rounded-full font-semibold">Up Next</span>
        </div>
        <span class="text-[11px] font-semibold text-dark">Third Shot Drop Practice</span>
        <div class="text-[9px] text-muted mt-0.5">3 sets × 10 reps</div>
      </div>

      <!-- Wednesday -->
      <div class="bg-[#f9f9f9] rounded-xl px-3 py-2.5">
        <div class="mb-0.5">
          <span class="text-[9px] text-muted font-medium">Wednesday</span>
        </div>
        <span class="text-[11px] font-semibold text-dark">Serve Placement</span>
        <div class="text-[9px] text-muted mt-0.5">4 sets × 5 reps</div>
      </div>

      <!-- Thursday -->
      <div class="bg-[#f9f9f9] rounded-xl px-3 py-2.5">
        <div class="mb-0.5">
          <span class="text-[9px] text-muted font-medium">Thursday</span>
        </div>
        <span class="text-[11px] font-semibold text-dark">Soft Block Volleys</span>
        <div class="text-[9px] text-muted mt-0.5">3 sets × 15 reps</div>
      </div>

      <!-- Friday -->
      <div class="bg-[#f9f9f9] rounded-xl px-3 py-2.5">
        <div class="mb-0.5">
          <span class="text-[9px] text-muted font-medium">Friday</span>
        </div>
        <span class="text-[11px] font-semibold text-dark">Reset Footwork</span>
        <div class="text-[9px] text-muted mt-0.5">2 sets × 12 reps</div>
      </div>
    </div>
  </div>
</template>
