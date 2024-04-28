<template>
    <div class="flex text-[17px] px-3 py-1 items-center rounded-full bg-slate-200">
        {{text}}
    </div>
</template>
<script setup lang="ts">
    const props = defineProps<{
        text: string
    }>();
</script>