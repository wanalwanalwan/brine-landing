<script setup>
defineProps({
  icon: String,
  title: String,
  description: String,
})
</script>

<template>
  <div class="p-6">
    <div class="text-3xl mb-4">{{ icon }}</div>
    <h3 class="text-base font-semibold font-rounded text-dark mb-1">{{ title }}</h3>
    <p class="text-sm text-muted font-rounded leading-relaxed">{{ description }}</p>
  </div>
</template>
