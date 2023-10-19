<template>
  <nav class="h-50px flex justify-center items-center bg-purple-500">
    <ul class="flex space-x-1">
      <li class="menu-item" :class="{'menu-item-active': $route.path === '/'}" @click="$router.push('/')">
        Index
      </li>
      <li class="menu-item" :class="{'menu-item-active': $route.path === '/tab'}" @click="$router.push('/tab')">
        Tab
      </li>
      <li class="menu-item" :class="{'menu-item-active': $route.path === '/detail'}" @click="$router.push('/detail')">
        Detail
      </li>
      <li class="menu-item" :class="{'menu-item-active': $route.path === '/user-profile'}" @click="$router.push('/user-profile')">
        UserProfile
      </li>
      <li class="menu-item" :class="{'menu-item-active': $route.path === '/settings'}" @click="$router.push('/settings')">
        Settings
      </li>
      <li class="menu-item" :class="{'menu-item-active': $route.path === '/publish'}" @click="$router.push('/publish')">
        Publish
      </li>
    </ul>
  </nav>
</template>


<style>
.menu-item {
  transition: all 0.2s ease-out;
  padding: 5px 10px;
  cursor: pointer;
}

.menu-item-active {
  background-color: #7e33f5; /* 鼠标悬浮时的背景颜色，可自行调整 */
  color: #ffffff; /* 鼠标悬浮时的文字颜色，可自行调整 */
  transform: scale(1.05); /* 鼠标悬浮时的缩放效果，可自行调整 */
}

.menu-item:hover, .menu-item:focus {
  background-color: #7e33f5; /* 鼠标悬浮时的背景颜色，可自行调整 */
  color: #ffffff; /* 鼠标悬浮时的文字颜色，可自行调整 */
  transform: scale(1.05); /* 鼠标悬浮时的缩放效果，可自行调整 */
}
</style>
<script setup lang="ts">
</script>
