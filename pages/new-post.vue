<template>
    <div class=" flex flex-col h-screen justify-center items-center gap-20 bg-slate-200">
        <GoBackLink />
        <Spengerhub />
        <p class=" text-3xl md:text-4xl font-bold">Neuer Eintrag</p>
        <div class="flex flex-col gap-7 rounded-xl px-8 py-9 bg-white shadow-2xl">
            <div class="flex gap-11 content-center items-center">
                <div class="flex gap-4 content-center items-center">
                    <label for="" class="text-[17px]">Titel:</label>
                    <input type="text" class="px-2 md:px-3 py-1 w-[350px]  rounded-md border-2 border-gray-600 outline-none">
                </div>
                <div class="flex gap-4 content-center items-center">
                    <label for="kategorie" class=" text-[17px]">Kategorie:</label>
                    <select name="cars" id="cars" class="px-3 py-1 h-9 rounded-md">
                        <option value="kategorie1">Kategorie 1</option>
                        <option value="kategorie2">Kategorie 2</option>
                        <option value="kategorie3">Kategorie 3</option>
                        <option value="kategorie4">Kategorie 4</option>
                    </select>
                </div>
            </div>
            <div class="flex gap-4 content-center items-center">
                <label for="" class="text-[17px]">Schlagworte:</label>
                <div class="flex w-full items-center content-center">
                    <input type="text" class="px-2 md:px-3 py-1 w-full  rounded-l-md border-2 border-gray-600 outline-none">
                    <button class="rounded-r-md  bg-slate-200 py-1 px-3 border-y-2 border-r-2 border-y-gray-600 border-r-gray-600">Hinzufügen</button>
                </div>
            </div>
            <div class="flex gap-4">
                <Schlagwort text="test1"/>
                <Schlagwort text="test2"/>
                <Schlagwort text="test3"/>
            </div>
            <div class="flex flex-col gap-4">
                <label for="" class="text-[17px]">Inhalt:</label>
                <textarea id="w3review" name="w3review" rows="13" cols="50" class=" max-h-72 min-h-16 outline-none border-2 border-gray-600 rounded-md py-1 px-3"></textarea>
            </div>
        </div>
    </div>
</template>