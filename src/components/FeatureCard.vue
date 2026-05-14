<script setup>
defineProps({
  icon: String,
  title: String,
  description: String,
})
</script>

<template>
  <div class="bg-white rounded-card p-6 transition-colors">
    <div class="text-3xl mb-3">{{ icon }}</div>
    <h3 class="text-base font-semibold font-rounded text-dark mb-1.5">{{ title }}</h3>
    <p class="text-sm text-muted font-rounded leading-relaxed">{{ description }}</p>
  </div>
</template>
