<template>
  <div class="custom-layout">
    <slot />
  </div>
</template>

<style scoped>
.custom-layout {
  margin: 20px auto;
  padding: 0 5px; /* 5px 留空 */
  max-width: 100vw;
  text-align: center;
}

@media (min-width: 900px) {
  .custom-layout {
    padding: 0 0; /* 5px 留空 */
  }
}
</style>
