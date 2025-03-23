<script setup>
import { RouterLink, RouterView } from 'vue-router'
import AuthLayoutVue from './layout/AuthLayout.vue'
import MainLayoutVue from './layout/MainLayout.vue'
</script>

<template>
  <auth-layout-vue></auth-layout-vue>
  <router-view></router-view>
</template>

<style scoped>
</style>
