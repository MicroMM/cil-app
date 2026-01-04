<template>
    <div>
        <header> CIL FABRICATORS</header>
        
        <div>
            <!--Page Content-->

            <slot />

        </div>

        <footer>

            <ul>
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

<style lang="scss" scoped>

</style>