<template>
<div class="h-screen w-screen pt-24">
    <div class="flex flex-col md:flex-row gap-8 h-full w-full items-center justify-center">
        <NuxtLink to="/ncufresh">
            <button
                class="rounded-sm bg-gray-300 p-12 text-2xl text-black shadow-md duration-200 hover:bg-gray-500">
                系所
            </button>
        </NuxtLink>

        <button @click="notReady"
            class="rounded-sm bg-gray-300 p-12 text-2xl text-black shadow-md duration-200 hover:bg-gray-500">
            交通
        </button>
        <button @click="notReady"
            class="rounded-sm bg-gray-300 p-12 text-2xl text-black shadow-md duration-200 hover:bg-gray-500">
            社團
        </button>
        <button @click="notReady"
            class="rounded-sm bg-gray-300 p-12 text-2xl  text-black shadow-md duration-200 hover:bg-gray-500">
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