<template>
  <div>
    <h1 style="text-align: center">
      Article Title: {{ $route.params["article_id"] }}
    </h1>
    <NuxtLink to="/blog">Back to Blogs</NuxtLink>
  </div>
</template>

<script>
export default {
  layout: 'blog'
}
</script>
