<template>
    <div class="flex flex-col gap-7">
        <button v-on:click="changeState" class="flex rounded-md md:pl-3 md:p-2 md:hover:bg-slate-300 gap-0 md:gap-1 content-center">
            <p class="md:m-auto">Kategorien</p>
            <img src="../public/arrow-down.png" alt="arrow" :class="`w-7 lg:w-9 ${state ? '': 'rotate-180'}`">
        </button>
        <div :class="`flex text-lg lg:text-xl gap-6 md:absolute md:top-[130px] flex-col w-full md:w-auto p-5 overflow-scroll md:pr-14 lg:pr-24 bg-sky-50 md:p-5 rounded-md max-h-[170px] ${state ? 'flex' : 'hidden'}`">
            <p>Kategorie 1</p>
            <p>Kategorie 2</p>
            <p>Kategorie 3</p>
            <p>Kategorie 4</p>
            <p>Kategorie 5</p>
            <p>Kategorie 6</p>
            <p>Kategorie 7</p>
            <p>Kategorie 8</p>
            <p>Kategorie 9</p>
            <p>Kategorie 10</p>
            <p>Kategorie 11</p>
            <p>Kategorie 12</p>
            <p>Kategorie 13</p>
        </div>
    </div>
</template>
<script setup lang="ts">
    const state = ref(false);
    const changeState = () => {
        state.value = !state.value;
    }
</script>