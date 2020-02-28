<template>
  <div>
      <nav class="navbar bg-white border-bottom navbar-light">
       <router-link class="navbar-brand mr-auto" to="/">LaravelBnb</router-link><br>
       <router-link class="btn nav-button" to="/second">Second</router-link>
      </nav>

      <div class="container mt-4 mb-4 pr-4 pl-4"></div>

       <router-view></router-view>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
