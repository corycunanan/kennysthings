<template>
  <div id="app">
    <nav class="navbar is-fixed-top is-black has-text-centered">
      <div class="navbar-menu has-text-centered">
        <figure class="image is-128x128">
          <img src="assets/logo.jpg">
        </figure>
        <router-link to="/" class="navbar-item has-text-white">Home</router-link>
        <router-link to="About" class="navbar-item has-text-white">About</router-link>
        <router-link to="Contact" class="navbar-item has-text-white">Contact</router-link>
      </div>
    </nav>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="sass">
@import 'mq'

</style>
