<template>
    <div class="section">
        <h1>Hello World</h1>
        <!-- <NuxtLayout name="default">
            hello
        </NuxtLayout> -->
        <div class="m-4 flex flex-col items-center justify-center space-y-4">
            <BaseButton />
        </div>
        <img src="~/assets/shiba-17.jpg" alt="shiba" />
        <div class="flex flex-row space-x-2">

            <button class="rounded-lg bg-zinc-700 p-4 px-6 text-sm text-white shadow-md duration-200 hover:bg-zinc-800">
                click me
            </button>
            
            <button class="rounded-lg bg-zinc-700 p-4 px-6 text-sm text-white shadow-md duration-200 hover:bg-zinc-800">
                <NuxtLink to="/ncufresh">NCUFresh</NuxtLink>
            </button>
            
        </div>
       
    </div>
</template>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.section {
    max-width: 800px;
    margin: 0 auto;
}

h1 {
    text-align: center;
    margin-top: 20px;
}

img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin: 0 auto;
    display: block;
}
</style>
