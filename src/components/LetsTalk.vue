<template>
    <div class="flex flex-col space-y-5 justify-center items-center">
        <!-- <h1 class="text-3xl font-bold text-gray-300">Let's Talk</h1> -->
        <div class="flex justify-center flex-col items-start bg-[url('/public/assets/terminal.png')] bg-center bg-contain bg-no-repeat md:h-[700px] p-10 md:p-32 w-full md:w-3/5">
            <h1 class="md:text-3xl font-bold text-center text-gray-300 w-full">Let's Talk</h1>
            <p class="text-gray-500 mt-4 text-center text-sm hidden md:block">
                We’d love to hear from you! Whether you have a question, need support, or just want to share your thoughts, we're here to listen.
                Feel free to reach out to us, and we’ll make sure to get back to you as soon as possible. 
            </p>
            <div class="flex flex-col md:gap-2 my-1 w-full">
                <div class="text-sm md:text-lg text-gray-500">Full Name</div>
                <input type="text" placeholder="Full Name" class="w-full border-b border-gray-500 bg-gray-900 p-1 rounded-lg">
            </div>
            <div class="flex flex-col md:gap-2 my-1 w-full">
                <div class="text-sm md:text-lg text-gray-500">Email Address</div>
                <input type="text" placeholder="Email Address" class="w-full border-b border-gray-500 bg-gray-900 p-1 rounded-lg">
            </div>
            <div class="flex flex-col md:gap-2 my-1 w-full">
                <div class="text-sm md:text-lg text-gray-500">Your Message</div>
                <textarea type="text" placeholder="Your Comment" class="w-full border-b border-gray-500 bg-gray-900 p-1 rounded-lg h-15 md:h-20"/>
            </div> 
            <button class="w-full transition duration-300 p-1 md:p-2 rounded-lg bg-gray-800 mt-2 hover:bg-custom-hover">
                Send Message
            </button>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>