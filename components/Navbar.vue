<template>
    <nav class="flex gap-5 md:gap-0 flex-col md:flex-row md:px-8 lg:px-20 xl:px-36 2xl:px-52 px-6 py-8 md:py-11 bg-slate-200 text-lg lg:text-xl md:items-center justify-between">
        <div class="flex items-center gap-2 w-100 font-semibold order-1">
            <img src="../pictures/logo.png" alt="spengergasse-logo" class="w-12 md:w-14">
            <p>HTL Spengergasse</p>
        </div>
        <p :class="`md:block order-3 md:order-2 ${
        state
          ? ' hidden'
          : ' block'
        }`">Kategorien</p>
        <div :class="`md:flex gap-7 order-2 md:order-3 ${
        state
          ? ' hidden'
          : ' flex'
        }`">
            <SearchBar />
            <SignInLink />
        </div>
        <button class="w-12 absolute right-0 mr-6 md:invisible" v-on:click="changeState">
            <img src="../pictures/menu-icon.png" alt="menu">
        </button>
    </nav>
</template>

<script lang="ts" setup>
    const state = ref(true);
    const changeState = () => {
        state.value = !state.value;
    }
</script>

