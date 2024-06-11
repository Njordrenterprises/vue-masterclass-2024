<script setup lang="ts"></script>

<template>
  <div>
    <h1>Home Page</h1>
    <RouterLink :to="{ name: '/episodes/[id]', params: { id: 1 } }">Episode 1</RouterLink>
  </div>
</template>
