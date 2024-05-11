<template>
    <div class="section">
        <div class="flex flex-row space-x-8 h-screen items-center justify-center">


            <NuxtLink to="/ncufresh">
                <button
                    class="rounded-sm bg-gray-300 p-12 text-2xl text-black shadow-md duration-200 hover:bg-gray-500">
                    系所
                </button>
            </NuxtLink>

            <button @click="notReady" class="rounded-sm bg-gray-300 p-12 text-2xl text-black shadow-md duration-200 hover:bg-gray-500">
                交通
            </button>
            <button @click="notReady" class="rounded-sm bg-gray-300 p-12 text-2xl text-black shadow-md duration-200 hover:bg-gray-500">
                社團
            </button>
            <button @click="notReady" class="rounded-sm bg-gray-300 p-12 text-2xl  text-black shadow-md duration-200 hover:bg-gray-500">
                宿舍
            </button>

        </div>

    </div>
</template>
<script setup>
function notReady() {
    alert('The link is not ready')
}

</script>

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
