<template>
    <div class="md:flex gap-1 order-3 md:order-2 content-center">
            <p>Kategorien</p>
            <img :src="`${state ? 'arrow-down.png' : 'arrow.png'}`" alt="arrow" class="w-7 md:w-9">
        </div>
</template>
<script setup lang="ts">
    const props = defineProps<{ 
      state: boolean 
      }>()
</script>