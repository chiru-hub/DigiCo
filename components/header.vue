<template>
  <div>
    <div class="bg-header custom-nav hide-on-med-and-down">
      <div class="container d-flex justify-content-start">
        <div class="nav-link">
          <nuxt-link class="link" to="/" exact>Home</nuxt-link>
        </div>
        <div class="nav-link">
          <nuxt-link class="link" to="/whoweare2">About</nuxt-link>
        </div>
        <div class="nav-link">
          <nuxt-link class="link" to="/securityservices">Products</nuxt-link>
        </div>
        <div class="nav-link">
          <nuxt-link class="link" to="/pknetwork">Gallery</nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.bg-header {
  background-color: #ffffff;
  border: 1px solid rgba(112, 112, 112, 0.52);
}

a,
a:hover {
  color: #3f3849;
  text-decoration: none;
  font-weight: 600;
  font-size: 20px;
}
</style>
