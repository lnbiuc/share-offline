<script setup lang="ts">
definePageMeta({
  layout: 'article',

})

const data = [
  {
    name: 'Account',
    path: 'user_settings_account.png'
  },
  {
    name: 'Security',
    path: 'user_settings_security.png'
  },
  {
    name: 'Password',
    path: 'user_settings_password.png'
  },
  {
    name: 'Other',
    path: 'user_settings_other.png'
  },
]

</script>

<template>
  <Article :data="data"/>
</template>

