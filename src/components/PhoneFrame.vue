<template>
  <div class="mx-auto max-w-[260px]">
    <div class="aspect-[9/19.5] bg-gradient-to-b from-[#2a2a2c] to-[#1a1a1c] rounded-[3rem] p-[10px] phone-bezel relative">
      <!-- Dynamic Island -->
      <div class="absolute top-[18px] left-1/2 -translate-x-1/2 w-[90px] h-[24px] bg-black rounded-full z-20"></div>
      <!-- Screen -->
      <div class="w-full h-full bg-white rounded-[2.25rem] overflow-hidden relative">
        <div class="phone-screen-glare"></div>
        <slot />
      </div>
    </div>
  </div>
</template>
