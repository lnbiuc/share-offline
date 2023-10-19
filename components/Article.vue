<script setup lang="ts">
const props = defineProps(['data'])
</script>

<template>
  <div class="image-gallery">
    <div class="image-container" v-for="i in data">
      <p class="image-caption">{{ i.name }}</p>
      <img :src="'../share-pic/' + i.path" :alt="i.name">
    </div>
  </div>
</template>

<style scoped>
.image-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  gap: 20px; /* 适当的上下左右间距 */
}

.image-container {
  width: 100%;
  text-align: center;
  margin: 10px; /* 适当的上下左右间距 */
}

img {
  width: 100%;
  max-width: 100%;
}

.image-caption {
  font-size: 20px;
  font-weight: bold;
  margin: 10px; /* 文本与图像的上间距 */
}
</style>
