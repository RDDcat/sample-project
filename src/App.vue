<template>
  <div class="font-sans text-gray-900">
    <!-- 섹션 1: 히어로 -->
    <HeroSection />

    <!-- 섹션 2: 경력 -->
    <CareerSection />

    <!-- 섹션 3: 연락처 -->
    <ContactSection />
  </div>
</template>

<script setup>
import HeroSection from "./sections/HeroSection.vue";
import CareerSection from "./sections/CareerSection.vue";
import ContactSection from "./sections/ContactSection.vue";
</script>

<style>
/* 필요시 전역 스타일 커스터마이징 가능 */
</style>
