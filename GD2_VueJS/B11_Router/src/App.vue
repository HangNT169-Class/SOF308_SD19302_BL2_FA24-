<script setup>
import FooterLayout from './layout/FooterLayout.vue'
import HeaderLayout from './layout/HeaderLayout.vue'
</script>

<template>
  <HeaderLayout />
  <main>
    <!-- Chua noi dung thay doi theo Header -->
    <RouterView />
  </main>
  <FooterLayout />
</template>
