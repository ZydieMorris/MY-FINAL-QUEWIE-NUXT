<script setup lang="ts">
import HeroSectionAbout from '~/components/aboutus/HeroSectionAbout.vue';
import WhatWeDo from '~/components/aboutus/WhatWeDo.vue';


</script>

<template>
    <NuxtLayout name="marketing-layout">
        <!-- About Us -->
            <HeroSectionAbout/>
        <!-- Who we are -->
            <WhatWeDo/>
    </NuxtLayout>
</template>
