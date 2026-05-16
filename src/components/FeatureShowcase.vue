<script setup>
defineProps({
  label: String,
  title: String,
  description: String,
  features: Array,
  reverse: { type: Boolean, default: false },
})
</script>

<template>
  <div class="py-16 md:py-24 border-t border-black/8">
    <div class="fade-up grid grid-cols-1 md:grid-cols-2 gap-10 md:gap-16 items-center">
      <!-- Phone side -->
      <div class="flex justify-center" :class="reverse ? 'order-1 md:order-2' : ''">
        <div class="bg-cream rounded-3xl p-6 md:p-10 w-full max-w-[400px]">
          <slot name="phone" />
        </div>
      </div>
      <!-- Text side -->
      <div :class="reverse ? 'order-2 md:order-1' : ''">
        <span class="text-teal font-semibold text-sm font-rounded">{{ label }}</span>
        <h3 class="text-3xl md:text-[2.5rem] font-bold font-rounded text-dark tracking-tight leading-[1.15] mt-3">
          {{ title }}
        </h3>
        <p class="text-muted font-rounded leading-relaxed mt-5 text-base">
          {{ description }}
        </p>
        <ul class="mt-6 space-y-3">
          <li v-for="feat in features" :key="feat" class="flex items-center gap-2.5">
            <svg class="w-5 h-5 text-teal shrink-0" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
            </svg>
            <span class="text-teal font-semibold text-sm font-rounded">{{ feat }}</span>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
