<template>
    <div class="flex items-center h-screen justify-center bg-slate-200">
        <GoBackLink/>
        <div class="flex flex-col gap-9 md:gap-12">
            <Spengerhub />
            <p class=" text-3xl md:text-4xl font-bold m-auto">Jetzt einloggen</p>
            <div class="flex flex-col shadow-2xl sm:w-[470px] w-80 md:w-[600px] gap-4 md:gap-5 rounded-lg px-7 py-9 bg-white">
                <div class="flex flex-col gap-1 md:gap-3">
                    <InputLabel label="Email Adresse"/>
                    <InputLabel label="Passwort"/>
                </div>
                <div class="flex gap-3 content-center md:text-lg">
                    <input type="checkbox" id="rememberMe" name="remerberMe" value="boolRemerberMe">
                    <label for="rememberMe">Angemeldet bleiben</label>
                </div>
                <button class="text-lg md:text-xl hover:bg-slate-300 text-[17px] h-8 md:h-12 items-center justify-center content-center bg-slate-200 rounded-md text-center">
                    Anmelden
                </button>
            </div>
            <div class="flex flex-col items-center gap-4 md:gap-6">
                <div class="flex content-center justify-between min-w-full items-center gap-4">
                    <hr class=" border-t-2 md:border-black grow ">
                    <p class="m-auto text-lg md:text-xl font-medium gorw-0">Neu bei Spengerhub</p>
                    <hr class=" border-t-2 md:border-black grow ">
                </div>
                <NuxtLink to="/" class=" bg-white font-light shadow-xl h-11 text-center content-center min-w-full rounded-md md:text-lg">
                    Dein Spengerhub Konto erstellen
                </NuxtLink>
            </div>
        </div>
    </div>
</template>