<template>
  <h1>Usersページ</h1>
  <p>Count:{{ counter }}</p>
  <NuxtPage />
</template>
<script setup>
const counter = useCounter();
</script>
