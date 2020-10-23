<template>
  <div class="navbar">
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/about">About</nuxt-link>
    <nuxt-link to="/contact">Contact</nuxt-link>
  </div>
</template>

<style scoped>
.navbar {
  background: #0089a7;
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
  text-transform: uppercase;
}

.nuxt-link-exact-active {
  border-bottom: 2px solid black;
  padding-bottom: 8px;
}
</style>
