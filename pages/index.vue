<template>
  <main>
    <h1>Home page</h1>
    <NuxtLink to="/about"> About </NuxtLink>

    <NuxtLink to="/posts"> posts </NuxtLink>
    <a href="https://nuxtjs.org">External Link to another page</a>
  </main>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
