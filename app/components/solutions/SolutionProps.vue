<script setup lang="ts">
defineProps<{
    image: string
    highlight: string
    title: string
    description: string
    link: string

}>();

import { MoveRight } from 'lucide-vue-next';
</script>

<template>
    <div class=" w-450 flex justify-center items-center">

<!-- Left -->
        <div class="flex-1 h-140 relative">
        <!-- White rectangle -->
            <div class="w-157.25 h-111.25 rounded-3xl bg-[#F7F7F7] absolute left-0 top-0"></div>
        <!-- Blur Rectangle -->
            <div class="w-123.75 h-75.25 rounded-3xl bg-[#F7F7F7] absolute left-60 bottom-25"></div>
        <!-- Blur bottom -->
        
            <img src="/images/solutionblur.png" class="w-138.75 h-105.75 absolute -bottom-10  left-20"/>
        
        <!-- iMAGE -->
        <div>
        <img :src="image" class="absolute w-157.25 h-111.25 top-15 left-10 rounded-3xl"/>
        </div>

        
        </div>
<!-- Right -->
        <div class="flex-1 h-140 " >
        
            <div class="space-y-3 mt-15">
                <h1 class="font-semibold text-5xl text-[#3691EF]">{{ highlight }}</h1>
                <p class="text-[#1E1E1E] text-5xl font-semibold">{{ title }}</p>
                <p class="font-normal text-lg leading-10 text-[#1E1E1E] justify-start">{{ description }}</p>

                <form class="pt-20 flex items-center space-x-2 text-[#3691EF] font-normal text-lg">
                     <NuxtLink to="" class="">More info</NuxtLink>
                     <MoveRight class=""/>
                </form>
               
            </div>
        </div>

    </div>
</template>



