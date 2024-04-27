<template>
    <div>
        <label for="">{{label}}</label>
    </div>
</template>
<script setup lang="ts">
    const props = defineProps<{
        label:string
    }>();
</script>