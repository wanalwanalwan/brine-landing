<script setup>
defineProps({
  icon: String,
  title: String,
  description: String,
})
</script>

<template>
  <div class="bg-white rounded-card p-6 shadow-sm hover:shadow-md transition-shadow">
    <div class="text-4xl mb-4">{{ icon }}</div>
    <h3 class="text-lg font-bold font-rounded text-dark mb-2">{{ title }}</h3>
    <p class="text-sm text-muted font-rounded leading-relaxed">{{ description }}</p>
  </div>
</template>
