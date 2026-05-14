<script setup>
import { onMounted } from 'vue'
import NavBar from './components/NavBar.vue'
import HeroSection from './components/HeroSection.vue'
import ShowcaseSection from './components/ShowcaseSection.vue'
import FeaturesSection from './components/FeaturesSection.vue'
import CtaSection from './components/CtaSection.vue'
import FooterSection from './components/FooterSection.vue'

onMounted(() => {
  const observer = new IntersectionObserver(
    (entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add('is-visible')
        }
      })
    },
    { threshold: 0.1 }
  )

  document.querySelectorAll('.fade-up, .fade-in').forEach((el) => {
    observer.observe(el)
  })
})
</script>

<template>
  <div class="min-h-screen bg-white font-rounded antialiased">
    <NavBar />
    <main>
      <HeroSection />
      <ShowcaseSection />
      <FeaturesSection />
      <CtaSection />
    </main>
    <FooterSection />
  </div>
</template>
