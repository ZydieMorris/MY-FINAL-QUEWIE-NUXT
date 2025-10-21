<template>
    <div class="h-auto relative">
        <!-- Top Background -->
        <div class="h-74.5 bg-gray-300"></div>

        <!-- White Card -->
        <div class="h-auto p-10 bg-white absolute left-5 right-5 lg:left-20 lg:right-20 top-15 rounded-3xl">

            <h1 class="text-4xl font-semibold text-center">
                What is <span class="text-[#3691EF]">QUEWIE?</span>
            </h1>

            <p class="leading-10 tracking-wide text-center text-[#696984] mt-8">
                QUEWIE is an innovative Queue Management solution designed to eliminate the hassle<br />
                of long and disorganized lines. It empowers users to book, place orders, track, and<br />
                manage their queue position in real time.
            </p>

           <!-- IMAGE SECTION -->
<div class="flex flex-col lg:flex-row justify-between items-center gap-4 lg:gap-8 mt-5">

    <!-- ADMIN -->
    <div class="relative">
        <img src="/images/foradmin.png" class="rounded-2xl h-90 w-134.75 object-contain" />
        <div class="absolute top-34 left-1/2 -translate-x-1/2 lg:left-35 lg:translate-x-0">
            <Button class="rounded-[80px] w-63.5 h-18 text-lg bg-transparent border">
                For Administrator
            </Button>
        </div>
    </div>

    <!-- GUEST -->
    <div class="relative">
        <img src="/images/forguest.png" class="rounded-[20px] h-[360px] w-[539px] object-contain" />
        <div class="absolute top-34 left-1/2 -translate-x-1/2 lg:left-34 lg:translate-x-0">
            <Button class="rounded-[80px] w-63.5 h-18 text-lg bg-[#388FF0]">
                For Guest Experience
            </Button>
        </div>
    </div>

</div>
<!-- END IMAGE SECTION -->


        </div>

        <!-- Bottom Blue Background -->
        <div class="bg-[#388FF0] h-145.5 mt-96 lg:mt-0"></div>
    </div>
</template>

<script setup lang="ts">
</script>
