<template>
  <div>
    <h1>User Indexページ</h1>
    <p>Count:{{ counter }}</p>
    <NuxtPage />
  </div>
</template>
<script setup>
const counter = useState('counter');
</script>
