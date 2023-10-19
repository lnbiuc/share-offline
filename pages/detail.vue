<script setup lang="ts">
definePageMeta({
  layout: 'article',

})

const data = [
  {
    name: 'Article Detail',
    path: 'type_article.png'
  },
  {
    name: 'Question Detail',
    path: 'type_question.png'
  },
  {
    name: 'Post Detail',
    path: 'type_post.png'
  },
  {
    name: 'Video Detail',
    path: 'type_video.png'
  },
  {
    name: 'Category Detail',
    path: 'type_category.png'
  },
]

</script>

<template>
  <Article :data="data"/>
</template>

