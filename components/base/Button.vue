<template>
    <button class="rounded-lg bg-zinc-700 py-4 px-6 text-sm shadow-md duration-200 hover:bg-zinc-800">
        <span class="text-white">{{ buttonText }}</span>
    </button>
</template>

<script setup>
const buttonText = ref("Click me");
</script>
