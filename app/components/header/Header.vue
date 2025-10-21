<script setup lang="ts">
import { ref } from 'vue'
const isOpen = ref(false)
</script>

<template>
    <div class="w-full fixed z-20 bg-white shadow h-[94px] flex justify-center text-[16px] font-normal">
        <div class="flex w-full  max-w-[1920px] px-15 items-center">

            <!-- LOGO -->
            <div class="flex-none ">
                <img src="/images/coloredLogo.png" class="w-45  xl:h-20   block" />
            </div>

            <!-- NAV (only visible when there's space, hides at xl->lg->md based on your choice) -->
            <div class="flex-4 ml-20  whitespace-nowrap hidden  lg:flex justify-start xl:space-x-10 space-x-6 ">
                <NuxtLink to="/"> HOME </NuxtLink>
                <NuxtLink to="/aboutus"> ABOUT US </NuxtLink>
                <NuxtLink to="/features"> FEATURES </NuxtLink>
                <NuxtLink to="/solutions"> SOLUTIONS </NuxtLink>
                <NuxtLink to="/contactus"> CONTACT US </NuxtLink>
                <NuxtLink to="/pricing"> PRICING </NuxtLink>
            </div>

            <!-- BUTTONS -->
            <div class="hidden lg:flex flex-1 space-x-3 justify-end">
                <Button variant="ghost">Login</Button>
                <Button class="bg-[#3691EF] rounded-[5px]">Signup</Button>
            </div>

            <!-- HAMBURGER (shows as soon as nav hides) -->
            <button @click="isOpen = !isOpen" class="lg:hidden flex-none ml-auto">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" fill="none" viewBox="0 0 24 24"
                    stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
            </button>

        </div>
    </div>

    <!-- MOBILE/TABLET DROPDOWN -->
    <div v-if="isOpen"
        class="xl:hidden fixed bg-white w-full mt-[94px] shadow-md flex flex-col space-y-4 p-6 text-[16px] z-10 items-center">
        <NuxtLink to="/"> HOME </NuxtLink>
        <NuxtLink to="/aboutus"> ABOUT US </NuxtLink>
        <NuxtLink to="/features"> FEATURES </NuxtLink>
        <NuxtLink to="/solutions"> SOLUTIONS </NuxtLink>
        <NuxtLink to="/contactus"> CONTACT US </NuxtLink>
        <NuxtLink to="/pricing"> PRICING </NuxtLink>

        <Button variant="ghost" class="w-full text-left mt-2">Login</Button>
        <Button class="bg-[#3691EF] rounded-[5px] w-full">Signup</Button>
    </div>
</template>
