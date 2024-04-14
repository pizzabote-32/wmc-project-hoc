<template>
      <NuxtLink :to="link" class="lg:my-12 lg:mx-12 my-7 mx-7 hover:bg-slate-200 py-3 px-3 rounded-md">
            <slot></slot>
      </NuxtLink>
</template>
  
<script lang="ts" setup>
  const props = defineProps<{ link: string }>()
</script>