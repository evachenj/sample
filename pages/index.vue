<template>
  <div>
    <h1>Hello world</h1>
    <nuxt-link to="/about">
      About Page
    </nuxt-link>
    <br>
    <nuxt-link to="/mypage">
      My Page
    </nuxt-link>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Home page'
  }
}
</script>
