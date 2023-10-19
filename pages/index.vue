<script setup lang="ts">
definePageMeta({
  layout: 'article',

})

const data = [
  {
    name: 'Index',
    path: 'index.png'
  }
]

</script>

<template>
  <Article :data="data"/>
</template>

