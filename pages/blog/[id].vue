<template>
    <div>
        Inside blog
    </div>
    <div>
        Post id is {{ route.params.id }}
    </div>
</template>

<script setup>
// const { useRoute } = require('vue-router');

const route = useRoute();
console.log(route);
</script>