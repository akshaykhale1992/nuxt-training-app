<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">About simple-website</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'About my Simple NuxtJS Website',
    meta: [
      { charset: 'utf-8' },
      { name: 'author', content: 'Akshay Khale' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'my website description'
      }
    ]
  }
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
