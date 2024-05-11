<template>
    <div class="flex justify-center items-center h-screen bg-white">
        <div v-show="show" class="absolute w-[500px] h-[320px] p-6 bg-white shadow-lg">
            <div class="absolute mt-20 ml-4 w-[8rem] h-20 p-4 bg-neutral-300 rotate-[-45deg]"></div>
            <div class="position ml-48 w-44 h-36 p-4 bg-red-200"></div>
            <div class="position ml-32 mt-4 w-80 h-32 p-2 text-sm text-left">
                <p>文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述文字敘述</p>
            </div>
        </div>
        <div class="grid grid-cols-2 gap-4">
            <div class="flex flex-col bg-gray-300 w-[400px] pl-4 pr-6 py-4 rounded-sm space-y-10 ml-20">
                <div class="grid grid-cols-6 gap-4 bg-white px-4 py-4 float-left">
                    <button @click="toggleShow" class="bg-gray-300 h-12 w-8 cursor-pointer">
                        理學院學士班
                    </button>
                    <button class="bg-gray-300 h-12 w-8"></button>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                </div>
                <div class="grid grid-cols-6 gap-4 bg-white px-4 py-4 float-left">
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                </div>
                <div class="grid grid-cols-6 gap-4 bg-white px-4 py-4 float-left">
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                </div>
                <div class="grid grid-cols-6 gap-4 bg-white px-4 py-4 float-left">
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                    <div class="bg-gray-300 h-12 w-8"></div>
                </div>
            </div>
            <div class="flex flex-col bg-gray-300 w-[400px] pl-4 pr-20 py-4 rounded-sm space-y-10 ml-40">
                <div class="grid grid-cols-5 gap-1 bg-white px-4 py-3 float-left">
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                </div>
                <div class="grid grid-cols-5 gap-1 bg-white px-4 py-3 float-left">
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                </div>
                <div class="grid grid-cols-5 gap-1 bg-white px-4 py-3 float-left">
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                </div>
                <div class="grid grid-cols-5 gap-1 bg-white px-4 py-3 float-left">
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                    <div class="bg-gray-300 h-14 w-8"></div>
                </div>
            </div>
        </div>
    </div>
</template>
<script setup>
import { ref } from 'vue'

const show = ref(false)

function toggleShow() {
    show.value = !show.value
}

</script>