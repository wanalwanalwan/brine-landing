<template>
  <div class="mx-auto max-w-[260px]">
    <div class="aspect-[9/19.5] bg-[#1d1d1f] rounded-[3rem] p-[10px] shadow-xl relative">
      <!-- Dynamic Island -->
      <div class="absolute top-[18px] left-1/2 -translate-x-1/2 w-[90px] h-[24px] bg-black rounded-full z-20"></div>
      <!-- Screen -->
      <div class="w-full h-full bg-white rounded-[2.25rem] overflow-hidden">
        <slot />
      </div>
    </div>
  </div>
</template>
