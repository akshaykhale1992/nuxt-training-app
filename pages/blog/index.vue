<template>
  <div class="container">
    <div>
      <h1 class="title">Blog of simple-website</h1>
      <li><NuxtLink to="/blog/First Article">First Article</NuxtLink></li>
      <li><NuxtLink to="/blog/Second Article">Second Article</NuxtLink></li>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
