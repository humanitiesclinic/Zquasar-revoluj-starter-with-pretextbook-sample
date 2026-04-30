<template>
  <iframe
    src="/book/index.html"
    style="width: 100%; height: 100%; border: none; margin: 0; padding: 0;"
    :sandbox="'allow-same-origin allow-scripts allow-forms allow-popups'"
  ></iframe>
</template>

<script setup lang="ts">
// Pretextbook loads via iframe at /book/index.html
</script>

<style scoped>
/* Ensure page takes full viewport */
:deep(.q-page) {
  padding: 0 !important;
  margin: 0;
}
</style>
