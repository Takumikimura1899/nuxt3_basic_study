<template>
  <div>
    <h1>About Page</h1>
    <h2>Counter</h2>
    <p>Count:{{ counter }}</p>
    <button @click="counter++">+</button>
  </div>
</template>
<script setup>
useHead({
  title: 'About Page',
  meta: [
    {
      hid: 'description',
      name: 'description',
      content: 'About Page',
    },
  ],
});
definePageMeta({
  middleware: 'auth',
});
const counter = useCounter();
</script>
