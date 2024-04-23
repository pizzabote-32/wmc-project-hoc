<template> 
    <div class="flex sm:flex-row flex-col border-black flex-nowrap border-2 py-4 sm:py-6 px-10 sm:px-12 rounded-full items-center">  
        <p class=" font-semibold text-[18px] lg:text-xl truncate max-w-64 lg:max-w-[500px] pb-2 sm:pb-0 sm:pr-6">{{ title }}</p>
        <p class="border-black text-[18px] lg:text-xl border-t-2 sm:border-t-0 sm:border-l-2 pt-2 sm:pt-0 truncate max-w-48 lg:max-w-60 sm:pl-6">{{ autor }}</p>
    </div>
</template>
<script setup lang="ts">
    const props = defineProps<{
        title: string
        autor: string
    }>();
</script>