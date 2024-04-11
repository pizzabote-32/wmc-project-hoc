<template>
      <NuxtLink :to="link" class="my-12 mx-12 hover:bg-slate-300 py-3 px-3 rounded-md">
            <slot></slot>
      </NuxtLink>
</template>
  
<script lang="ts" setup>
  const props = defineProps<{ link: string }>()
</script>