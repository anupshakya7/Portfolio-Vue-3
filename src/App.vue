<template>
  <div class="p-10 px-20 flex flex-col gap-5">
    <Navbar/>
    <Header/>
    <About/>
    <Work/>
    <Client/>
    <Experience/>
    <LetsTalk/>
    <Footer/>
  </div>

</template>

<script setup>
import Navbar from './components/Navbar.vue';
import Header from './components/Header.vue';
import About from './components/About.vue';
import Work from './components/Work.vue';
import Client from './components/Client.vue';
import Experience from './components/Experience.vue';
import LetsTalk from './components/LetsTalk.vue';
import Footer from './components/Footer.vue';
</script>

<style scoped>

</style>