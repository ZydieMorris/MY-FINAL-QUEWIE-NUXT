<script setup>
defineProps({
    title: String,
    highlight: String,
    description: String,
    link: String,
    image: String, // image path or URL
})



</script>

<template>
    <!-- Parent Card -->
    <div class="  flex justify-between h-89.5">
        <!-- Left Side (Text) -->
        <div class="flex-1 pt-10 pb-10">
            <div class="w-160 h-70  p space-y-5 relative">
                <!-- Title -->
                <div class="flex items-start ">
                    <div class="rounded-full bg-[#388FF0] w-14 h-14 flex-shrink-0"></div>
                    <p class="text-2xl whitespace-normal leading-9 -ml-8 mt-3 font-medium text-[#272727]">
                        {{ title }}:
                        <span class="text-[#388FF0]">{{ highlight }}</span>
                    </p>
                </div>

                <!-- small circle -->
                <div class="absolute bg-[#388FF0] rounded-full h-5 w-5 right-20 top-50"></div>

                <!-- description -->
                <div class="ml-5">
                    <p class=" leading-8 tracking-wide text-[#696984]">{{ description }}</p>
                </div>

                <div class="mt-13">
                    <NuxtLink :to="link" class="font-normal  text-[#696984] underline-offset-2 underline ml-5">
                        Learn More
                    </NuxtLink>
                </div>




            </div>
        </div>


        <!-- Right Side -->
        <div class="flex-1  relative">
            <!-- Black rectangle -->
            <div class="bg-[#272727] rounded-3xl absolute h-24 w-26.5 right-117"></div>

            <!-- Blue rectangle -->
            <div class="bg-[#388FF0] rounded-3xl absolute right-0 bottom-0 h-40.25 w-44.5 ">
            </div>

            <!-- Image wrapper -->
            <div class="">
                <img :src="image" class=" absolute right-4 top-3.5  w-136 h-82.25" />
            </div>
        </div>



    </div>
</template>
