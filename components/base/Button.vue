<template>
    <button class="rounded-lg bg-zinc-700 p-4 px-6 text-sm text-white shadow-md duration-200 hover:bg-zinc-800">
        {{ buttonText }}
    </button>
</template>

<script setup>
import { ref } from "vue";

const buttonText = ref("Click me");
</script>
