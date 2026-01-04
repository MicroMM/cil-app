<template>
    <div>
        <header class="shadow-sm bg-white "> 
        <nav class="container mx-auto p-4 flex justify-between ">
            <NuxtLink to="/" class="text-2xl font-bold font-serif antialiased md:subpixel-antialiased">CIL FABRICATORS</NuxtLink>
            <ul class="flex gap-2 font-bold bg-amber-50 p-1.5 rounded-2xl font-serif">
                <li><NuxtLink to="/"> Home</NuxtLink></li>
                <li><NuxtLink to="/about"> About</NuxtLink></li>
                <li><NuxtLink to="/products"> Products</NuxtLink></li>
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