<!-- the [...slug] file name is a vue pattern that acts as a catchall
    for routes under this page. 
    so in this instance, the "slug" would be 
    anything that came after /pages (id of the blog)
    i.e. /pages/[slug]
-->

<template>
  <article class="prose dark:prose-invert">
    <ContentDoc />
  </article>
</template>

<script setup>
// const { useRoute } = require('vue-router');

const route = useRoute();
console.log(route);
</script>
