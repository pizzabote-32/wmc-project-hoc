<template>
    <div class="flex items-center h-screen justify-center">
        <GoBackLink/>
        <div class="flex flex-col gap-12">
            <Spengerhub />
            <p class=" text-3xl font-bold">Jetzt einloggen</p>
            <div class="flex flex-col shadow-md items-center">
                <InputLabel label="Email Adresse"/>
                <InputLabel label="Passwort"/>
            </div>
        </div>
    </div>
</template>