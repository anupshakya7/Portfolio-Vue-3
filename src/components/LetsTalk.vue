<template>
    <div class="flex flex-col space-y-5 justify-center items-center">
        <h1 class="text-3xl font-bold text-gray-300">Let's Talk</h1>
        <div class="flex justify-center flex-col items-start bg-[url('/public/assets/terminal.png')] bg-center bg-contain bg-no-repeat h-[700px] p-32 w-3/5">
            <h1 class="text-3xl font-bold text-gray-300 w-full">Let's Talk</h1>
            <p class="text-gray-500 text-sm">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro eaque, dolorem at velit ullam assumenda numquam harum voluptatibus suscipit quos, unde vitae est corporis ex non error, modi ut esse.
            </p>
            <div class="flex flex-col gap-2 my-1 w-full">
                <div class="text-gray-500">Full Name</div>
                <input type="text" placeholder="John Doe" class="w-full border-b border-gray-500 bg-gray-900 p-1 rounded-lg">
            </div>
            <div class="flex flex-col gap-2 my-1 w-full">
                <div class="text-gray-500">Email Address</div>
                <input type="text" placeholder="johndoe@gmail.com" class="w-full border-b border-gray-500 bg-gray-900 p-1 rounded-lg">
            </div>
            <div class="flex flex-col gap-2 my-1 w-full">
                <div class="text-gray-500">Your Message</div>
                <textarea type="text" placeholder="Your Comment" class="w-full border-b border-gray-500 bg-gray-900 p-1 rounded-lg"/>
            </div> 
            <button class="w-full p-2 rounded-lg bg-gray-800 mt-2">
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