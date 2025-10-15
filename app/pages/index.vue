<script setup lang="ts">
import HeroSection from '~/index/HeroSection.vue';
import QuewieWay from '~/index/QuewieWay.vue';
import Testimonial from '~/index/Testimonial.vue';
import WhatisQuewie from '~/index/WhatisQuewie.vue';


</script>

<template>
  <NuxtLayout name="marketing-layout">
    <HeroSection />
    <WhatisQuewie />
    <QuewieWay />
    <Testimonial />
  </NuxtLayout>
</template>
