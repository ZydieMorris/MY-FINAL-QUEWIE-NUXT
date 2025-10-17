<script setup lang="ts">
const props = defineProps<{
    title: string;
    description: string;
}>();
</script>


<template>
    <div class="text-center w-315.25  space-y-5 mb-20">
        <h1 class="text-3xl font-semibold text-[#3691EF]">{{ props.title }}</h1>
        <p class="text-[#696984] text-2xl font-normal text-justify  tracking-0.02 leading-10 ">{{
            props.description }}
        </p>
        <slot></slot>
    </div>
</template>
