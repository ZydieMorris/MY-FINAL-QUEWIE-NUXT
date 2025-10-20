<script setup lang="ts">
defineProps<{
    image: string
    title: string
    highlight: string
    description: string
}>();
</script>

<template>
    <div class="pt-48.75 pb-15  flex flex-col space-y-15">

        <!-- Image -->
        <img :src="image" class=" w-314.75 h-142.5" />


        <div class="flex flex-col w-314.75  items-start space-y-8">
            <h1 class="text-4xl text-[#272727] font-semibold leading-12">{{ title }}:<br><span class="text-[#469AF0]">{{
                highlight }}</span></h1>
            <p class=" text-justify  text-[#696984] tracking-wide leading-9">{{ description }}</p>
        </div>
    </div>
</template>
