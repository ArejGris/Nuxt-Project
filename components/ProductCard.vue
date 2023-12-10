<template>
<div class="card p-7">
    <img :src="product.image" alt="" />
   <h2 class="mx-auto h-20 text-centre">    {{ product.title }}</h2>
   <p class="btn"><NuxtLink :to="`/products/${product.id}`">view Details</NuxtLink></p>



</div>
</template>
<script setup>
const {product}= defineProps(['product'])
</script>
<style scoped>
img{
   width: 300px; 
   height: 300px;
}
h2{
    text-align: center;
    font-weight: 600;
}


</style>