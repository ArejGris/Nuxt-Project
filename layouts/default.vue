<template>
<div>
    <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4 flex justify-between">
            <NuxtLink to="/" class="font-bold">Nuxt dojo</NuxtLink>
            <ul class="flex justify-center gap-8">
             <li><NuxtLink to="/home">home</NuxtLink></li>
             <li><NuxtLink to="/products">product</NuxtLink></li>
             </ul>

        </nav>
    </header>
    <div class="container mx-auto p-4">
        <slot />
    </div>
</div>
</template>
<style scoped>
.router-link-exact-active{
    color:#12b488
}
</style>