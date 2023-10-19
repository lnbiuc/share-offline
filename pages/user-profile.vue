<script setup lang="ts">
definePageMeta({
  layout: 'article',

})

const data = [
  {
    name: 'Publish',
    path: 'user_profile_publish.png'
  },
  {
    name: 'Collection',
    path: 'user_profile_collection.png'
  },
  {
    name: 'Comment',
    path: 'user_profile_comment.png'
  },
  {
    name: 'History',
    path: 'user_profile_history.png'
  },
  {
    name: 'Like',
    path: 'user_profile_like.png'
  },
  {
    name: 'Subscribe',
    path: 'user_profile_subcribe.png'
  },
]

</script>

<template>
  <Article :data="data"/>
</template>

