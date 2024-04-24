<template>
    <div class="md:flex gap-1 order-3 md:order-2 content-center">
            <p class="m-auto">Kategorien</p>
            <img src="../public/arrow-down.png" alt="arrow" :class="`w-7 md:w-9 ${state ? '': 'rotate-180'}`">
        </div>
</template>
<script setup lang="ts">
    const props = defineProps<{ 
      state: boolean 
      }>()
</script>