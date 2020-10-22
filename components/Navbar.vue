<template>
  <div class="navbar">
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/about">About</nuxt-link>
    <nuxt-link to="/contact">Contact</nuxt-link>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.navbar {
  background: lightskyblue;
  width: 100%;
  padding: 1rem;
  text-align: center;
  position: relative;
  z-index: 1000;
}

.navbar a {
  text-decoration: none;
  color: white;
  margin-right: 1rem;
}

.nuxt-link-exact-active {
  border-bottom: 1px solid black;
  padding-bottom: 5px;
}
</style>
