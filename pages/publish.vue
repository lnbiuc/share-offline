<script setup lang="ts">
definePageMeta({
  layout: 'article',

})

const data = [
  {
    name: 'Publish Article',
    path: 'publish_article.png'
  },
  {
    name: 'Publish Question',
    path: 'publish_question.png'
  },
  {
    name: 'Publish Video',
    path: 'publish_video.png'
  },
  {
    name: 'Publish Post',
    path: 'publish_post.png'
  },
]

</script>

<template>
  <Article :data="data"/>
</template>

