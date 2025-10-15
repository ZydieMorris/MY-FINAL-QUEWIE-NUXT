<script setup lang="ts">

</script>

<template>
    <div
        class="w-full shadow-[0_4px_6px_-1px_rgba(0,0,0,0.1)] h-[94px] pr-[85px] pl-[85px] items-center flex justify-between text-[16px] font-normal">
        <!-- Left Side -->
        <div class="flex space-x-25">
            <!-- Logo -->
            <div>
                <img src="/images/coloredLogo.png" class="h-[76px] w-[206px]" />
            </div>
            <!-- Navigation -->
            <div class="flex items-center space-x-15 ">
                <NuxtLink to="/"> HOME </NuxtLink>
                <NuxtLink to="/aboutus"> ABOUT US </NuxtLink>
                <NuxtLink to="/features"> FEATURES </NuxtLink>
                <NuxtLink to="/solutions"> SOLUTIONS </NuxtLink>
                <NuxtLink to="/contactus"> CONTACT US </NuxtLink>
                <NuxtLink to="/pricing"> PRICING </NuxtLink>

            </div>
        </div>

        <!-- Right Side -->
        <div class="flex space-x-3  ">
            <Button variant="ghost" class="">Login</Button>
            <Button class="bg-[#3691EF] rounded-[5px]">Signup</Button>

        </div>

    </div>
</template>
