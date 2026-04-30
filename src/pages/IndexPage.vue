<template>
  <div class="fullscreen-container">
    <iframe
      src="/book/index.html"
      :sandbox="'allow-same-origin allow-scripts allow-forms allow-popups'"
    ></iframe>
  </div>
</template>

<script setup lang="ts">
// Pretextbook loads via iframe at /book/index.html
</script>

<style scoped>
.fullscreen-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

iframe {
  width: 100%;
  height: 100%;
  border: none;
  margin: 0;
  padding: 0;
}
</style>
