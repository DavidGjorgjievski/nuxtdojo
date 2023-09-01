<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="conatiner mx-auto p-4"> 
                <NuxtLink to="/" class="font-bold">Nux Dojo Merch</NuxtLink>
            </nav>
        </header>

        <!-- out put page contetnt -->
        <div class="conainer mx-auto p-4">
            <slot />
        </div>


        <footer class="conatiner mx-auto p-4 flex justify-between border-t-2">
            <ul class="flex gap-4">
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/products">Products</NuxtLink></li>
            </ul>
        </footer>
    </div>  
</template>

<style scoped>
    .router-link-exact-active {
        color: #12b488
    }
</style>