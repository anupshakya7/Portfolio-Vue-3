<template>
    <footer class="flex flex-col md:flex-row justify-between items-center w-full py-3">
        <p class="text-gray-500">Terms & Conditions | Privacy Policies</p>
        <div class="flex gap-2">
            <a href="#"><img src="/public/assets/instagram.svg" class="h-8 bg-gray-900 p-2 cursor-pointer rounded-full transition ease-in-out duration-100 hover:scale-[1.1]" alt=""></a>
            <a href="#"><img src="/public/assets/github.svg" class="h-8 bg-gray-900 p-2 cursor-pointer rounded-full transition ease-in-out duration-100 hover:scale-[1.1]" alt=""></a>
            <a href="#"><img src="/public/assets/twitter.svg" class="h-8 bg-gray-900 p-2 cursor-pointer rounded-full transition ease-in-out duration-100 hover:scale-[1.1]" alt=""></a>
        </div>
        <p class="text-gray-500">{{currentYear}} Anup All Right Reserved</p>
    </footer>
</template>

<script setup>
import {ref} from 'vue';

let currentYear = ref(new Date().getFullYear());
</script>

<style scoped>

</style>