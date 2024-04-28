<template>
    <div class="flex flex-col text-lg md:text-xl gap-1 md:gap-2">
        <label for="" class="">{{label}}</label>
        <input type="text" class=" min-w-full  md:w-40 lg:w-56 px-2 md:px-3 py-1 md:py-2 rounded-md border-2 outline-none">
    </div>
</template>
<script setup lang="ts">
    const props = defineProps<{
        label:string
    }>();
</script>