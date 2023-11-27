<template>
    <div class="bg-[#0f0f0f] text-white min-h-screen">
        <div class="container mx-auto px-32">
            <nav class="flex items-center justify-between py-10">
                <div>
                    <img src="../asset/img/logo.webp" alt="">
                </div>
                <div class="flex space-x-8">
                    <NuxtLink to="/">Home</NuxtLink>
                    <NuxtLink to="/birds">Birds</NuxtLink>
                </div>
                <div class="">
                    <button class="py-2 px-4 rounded-md bg-[#323232] hover:bg-white hover:text-black">Let's Fly</button>
                </div>
            </nav>
            <div class="my-6">
                <slot />
            </div>

            <footer class="my-[100px]">
                <div class="flex justify-center">
                    <img src="../asset/img/logo.webp" alt="">
                </div>
            </footer>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>