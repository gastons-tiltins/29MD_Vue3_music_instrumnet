<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="container">
    <div class="nav-wrapper">
      <div>
        <RouterLink to="/">Home</RouterLink>
      </div>
      <div>
        <RouterLink to="/about">About</RouterLink>
      </div>
    </div>
  </header>

  <RouterView />
</template>

<style scoped></style>
