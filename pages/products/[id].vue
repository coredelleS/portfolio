<template>
    <div>
        <ProductDetails :product="product"/>
    </div>
</template>

<script setup>
import { useRoute } from 'vue-router';

const { id } = useRoute().params;
const uri = 'https://fakestoreapi.com/products/' + id;

const { data: product } = await useFetch(uri, {key: id});

definePageMeta({
    layout: 'products'
})

</script>

<style scoped>
.bold {
    font-weight: bolder;
}
</style>