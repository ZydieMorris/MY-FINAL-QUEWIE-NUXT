<script setup lang="ts">

</script>

<template>
    <div
        class="w-full z-20 fixed bg-white shadow-[0_4px_6px_-1px_rgba(0,0,0,0.1)]  h-[94px] flex justify-center  text-[16px] font-normal">
      
        <div class=" flex w-[1920px] pl-20 pr-20   justify-between  items-center">
              <!-- Left Side -->
        <div class="flex space-x-25">
            <!-- Logo -->
            <div >
                <img src="/images/coloredLogo.png" class="h-[76px] w-[206px] " />
            </div>
            <!-- Navigation -->
            <div class="flex items-center space-x-15 font-sans font-normal">
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
    </div>
</template>
