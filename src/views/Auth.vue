<template>
  <div class="overlay-header">
    <h1>Auth</h1>
  </div>
</template>

<script setup>

</script>

<style scoped>
  .overlay-header {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      z-index: 1050; /* Для гарантии, что элемент будет сверху */
      background-color: rgba(0, 0, 0, 0.5); /* Полупрозрачный фон */
      color: white;
      padding: 20px;
      border-radius: 5px;
    }
</style>