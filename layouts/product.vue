<template>
    <div>
        <header class="shadow-sm bg-white"> 
        <nav class="container mx-auto p-2 ">

            <NuxtLink to="/" class="text-3xl font-bold font-serif antialiased md:subpixel-antialiased">CIL FABRICATORS</NuxtLink>
            
        </nav>

        </header>
        
        <div class="container mx-auto p-4">
            <!--Page Content-->

            <slot />

        </div>

        <footer class="shadow-sm bg-white ">

            <ul class="flex gap-2 font-bold p-1.5 rounded-2xl font-serif mx-7">
                <li><NuxtLink to="/"> Home |</NuxtLink></li>
                <li><NuxtLink to="/about"> About |</NuxtLink></li>
                <li><NuxtLink to="/products"> Products |</NuxtLink></li>
                <li><NuxtLink to="/contacts">Contact</NuxtLink></li>
            </ul>

        </footer>

    </div>
</template>

<script setup>

</script>

<style scoped>

</style>