<script setup lang="ts">
definePageMeta({
  layout: 'article',

})

const data = [
  {
    name: 'Article Tab',
    path: 'tab_article.png'
  },
  {
    name: 'Question Tab',
    path: 'tab_question.png'
  },
  {
    name: 'Post Tab',
    path: 'tab_post.png'
  },
  {
    name: 'Video Tab',
    path: 'tab_video.png'
  },
  {
    name: 'Category Tab',
    path: 'tab_category.png'
  }
]

</script>

<template>
  <Article :data="data"/>
</template>

