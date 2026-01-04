<template>
    <div>
        <header class="shadow-sm bg-white p-4"> 
        <nav class="container mx-auto p-4 ">

            <NuxtLink to="/" class="text-3xl font-bold font-serif antialiased md:subpixel-antialiased">CIL FABRICATORS</NuxtLink>
            
        </nav>

        </header>
        
        <div class="container mx-auto p-4">
            <!--Page Content-->

            <slot />

        </div>

        <footer>

            <ul class="flex gap-4">
                <li><NuxtLink to="./"> Home</NuxtLink></li>
                <li><NuxtLink to="./about"> About</NuxtLink></li>
                <li><NuxtLink to="./products"> Products</NuxtLink></li>
                <li><NuxtLink to="./contacts">Contact</NuxtLink></li>
            </ul>

        </footer>

    </div>
</template>

<script setup>

</script>

<style scoped>

</style>