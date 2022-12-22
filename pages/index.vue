<script lang="ts" setup>
const { data } = await useFetch("/api/hello");
</script>

<template>
  <div>
    <h1>Hello Nuxt</h1>
    {{ data?.foo }}
    <NuxtLink to="/about">About</NuxtLink>
  </div>
</template>
