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
  <div class="py-12 md:py-24 border-t border-black/8">
    <div class="fade-up grid grid-cols-1 md:grid-cols-2 gap-8 md:gap-16 items-center">
      <!-- Phone side (always after text on mobile) -->
      <div class="flex justify-center order-2" :class="reverse ? 'md:order-2' : 'md:order-1'">
        <div class="bg-cream rounded-3xl p-6 md:p-10 w-full max-w-[320px] md:max-w-[400px]">
          <slot name="phone" />
        </div>
      </div>
      <!-- Text side (always first on mobile) -->
      <div class="order-1" :class="reverse ? 'md:order-1' : 'md:order-2'">
        <span class="text-teal font-semibold text-sm font-rounded">{{ label }}</span>
        <h3 class="text-2xl md:text-[2.5rem] font-bold font-rounded text-dark tracking-tight leading-[1.15] mt-2 md:mt-3">
          {{ title }}
        </h3>
        <p class="text-muted font-rounded leading-relaxed mt-4 md:mt-5 text-sm md:text-base">
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
