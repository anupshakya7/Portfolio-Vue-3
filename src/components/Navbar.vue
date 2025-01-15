<template>
   <nav class="flex justify-between items-center">
        <h1 class="text-3xl font-bold cursor-pointer">Anup</h1>
        <ul class="md:flex space-x-10 hidden">
            <li class="cursor-pointer transition duration-300 ease-in-out hover:text-custom-hover">Home</li>
            <li class="cursor-pointer transition duration-300 ease-in-out hover:text-custom-hover">About</li>
            <li class="cursor-pointer transition duration-300 ease-in-out hover:text-custom-hover">Work</li>
            <li class="cursor-pointer transition duration-300 ease-in-out hover:text-custom-hover">Contact</li>
        </ul>
        <div class="md:hidden">
            <Menu/>
        </div>
   </nav>
</template>

<script setup>
import Menu from '../../public/assets/Menu.vue';
</script>

<style scoped>

</style>