<template>
  <div>
    <h1>About Page</h1>
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
</script>
