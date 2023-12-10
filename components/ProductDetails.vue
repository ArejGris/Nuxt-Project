<template>

    <div class="grid grid-cols-2 gap-10">
    <div class="p-7">
        <img :src="product.image" alt="">
    </div>
    <div class="p-7"><h1>{{ product.title }}</h1></div>

</div>
</template>
<script setup>
const {product} =defineProps(['product'])
</script>
