<template>
    <div>
        <header class="shadow-sm bg-white p-4"> 
        <nav class="container mx-auto p-4 flex justify-between ">
            <NuxtLink to="/" class="text-xl font-bold">CIL FABRICATORS</NuxtLink>
            <ul class="flex gap-2">
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