<template>
  <div>
    <div class="bg-header d-flex custom-nav hide-on-med-and-down">
      <div class="d-flex container justify-content-between">
        <div class="d-flex justify-content-start align-self-center">
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
        <div>
          <img class="logo" src="/images/logo.png" alt />
        </div>
        <div class="align-self-center">
          <a style="font-size:16px:font-weight:none" href>+12356789</a>
          <button class="btn btn-contact">CONTACT</button>
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

.logo {
  height: 67px;
  width: 100%;
}

.btn-contact {
  background-color: #34a2db;
  color: white;
  font-size: 16px;
  text-align: center;
  font-weight: 700;
  height: 41px;
  width: 150px;
}
</style>
