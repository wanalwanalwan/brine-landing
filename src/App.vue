<script setup>
import NavBar from './components/NavBar.vue'
import HeroSection from './components/HeroSection.vue'
import FeaturesSection from './components/FeaturesSection.vue'
import CtaSection from './components/CtaSection.vue'
import FooterSection from './components/FooterSection.vue'
</script>

<template>
  <div class="min-h-screen bg-white font-rounded antialiased">
    <NavBar />
    <main>
      <HeroSection />
      <FeaturesSection />
      <CtaSection />
    </main>
    <FooterSection />
  </div>
</template>
