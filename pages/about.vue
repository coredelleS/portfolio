<template>
  <div>This is my page.</div>
  <div>
    <button @click="enableCustomLayout">Update Layout</button>
  </div>
</template>

<script setup>
function enableCustomLayout() {
  setPageLayout("another");
}
// definePageMeta({
//   layout: "another",
// });
</script>
