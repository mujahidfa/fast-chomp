<template>
  <section>
    <Logo />
    Home page
    <nuxt-link to="/">Home page</nuxt-link>
    <nuxt-link to="/order">Order</nuxt-link>
    <nuxt-link to="/checkout">Checkout</nuxt-link>
    <nuxt-link to="/complete">Complete</nuxt-link>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* add styles here */
</style>
