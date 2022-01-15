<template>
  <div>
    <!-- <Header/> -->
    Hello world!
    <!-- THIS WORK AS SPA - no reload -->
    <nuxt-link to="/1omraj">/1omraj</nuxt-link> <br>
    <nuxt-link to="/2shyam">/2shyam</nuxt-link> <br>
    <nuxt-link to="/products">/Products</nuxt-link> <br>
    <nuxt-link to="users">/users</nuxt-link> <br>
    <nuxt-link to="/nested-routes">/nested-routes</nuxt-link>
    
    <!-- THIS RELOADS THE PAGE -->
    <!-- <a href="/1omraj">omraj</a> -->
  </div>
</template>

<script>
// import Header from '~/components/Header.vue'

export default {
  name: 'IndexPage',
  components: {
    
  }
}
</script>
