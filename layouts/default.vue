<template>
    <div>
        <header class="shadow-sm bg-white "> 
        <nav class="container mx-auto p-2 flex justify-between ">
            <NuxtLink to="/" class="text-2xl font-bold font-serif antialiased md:subpixel-antialiased text-shadow-2xs">CIL FABRICATORS</NuxtLink>
            <ul class="flex gap-2 font-bold bg-amber-50 p-1.5 font-serif rounded-tl-lg rounded-br-lg">
                <li><NuxtLink to="/"> Home |</NuxtLink></li>
                <li><NuxtLink to="/about"> About |</NuxtLink></li>
                <li><NuxtLink to="/products"> Products |</NuxtLink></li>
                <li><NuxtLink to="/contacts">Contact</NuxtLink></li>
            </ul>
        </nav>

        </header>

        <div class="container mx-auto p-4">
            <!--Page Content-->

            <slot />

        </div>

    </div>
</template>

<script setup>

</script>

<style scoped>
    .router-link-exact-active {

        color:crimson;
    }
</style>