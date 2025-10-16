<script setup lang="ts">
defineProps<{
    image:string
    title:string
    highlight:string
    description:string
}>();
</script>

<template>
    <div>
    <!-- Image -->
        <img :src="image" class=" absolute right-4 top-3.5  w-136 h-82.25" />

        <div>
            <h1>{{ title }}:<span>{{ highlight }}</span></h1>
            <p>{{ description }}</p>
        </div>
    </div>
</template>



