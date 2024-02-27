<!-- the [...slug] file name is a vue pattern that acts as a catchall
    for routes under this page. 
    so in this instance, the "slug" would be 
    anything that came after /pages (id of the blog)
    i.e. /pages/[slug]
-->

<template>
  <article
    class="prose dark:prose-invert prose-pre:bg-white dark:prose-pre:bg-gray-800 prose-pre:text-gray-700 dark:prose-pre:text-gray-300"
  >
    <ContentDoc />
  </article>
</template>

<script setup>
// const { useRoute } = require('vue-router');

const route = useRoute();
console.log(route);
</script>
