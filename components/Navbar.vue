<template>
  <nav>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/about">About</NuxtLink>
    <NuxtLink :to="{ name: 'users-list' }">User List</NuxtLink>
    <NuxtLink to="/posts">Posts</NuxtLink>
  </nav>
</template>
