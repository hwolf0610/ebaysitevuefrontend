<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">ebaySiteVue</h1>
      <h2 class="subtitle">just update</h2>

      <nuxt-link to="/login" class="button--green">
        <span>Login</span>
      </nuxt-link>
      <nuxt-link to="/signup" class="button--green">
        <span>Signup</span>
      </nuxt-link>
      <nuxt-link to="/packageplan" class="button--green">
        <span>Package Plan</span>
      </nuxt-link>

      <!-- <div class="links">      
        <a href="/login" target="_blank" class="button--green">Login</a>
        <a href="/signup" target="_blank" class="button--grey">Signup</a>
        <a href="/packageplan" target="_blank" class="button--grey">Package Plan</a>
      </div>-->
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
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

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
