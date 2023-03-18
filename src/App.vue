<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="container">
    <div class="nav-wrapper">
      <div>
        <RouterLink class="selectDisable" to="/">Home</RouterLink>
      </div>
      <div>
        <RouterLink class="selectDisable" to="/about">About</RouterLink>
      </div>
    </div>
  </header>

  <RouterView />
</template>

<style scoped></style>
