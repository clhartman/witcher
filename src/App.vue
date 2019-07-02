<template>
  <div id="app">
    <nav class="navbar navbar-light bg-light">
      <a class="navbar-brand" href="#">
        <img src="assets/medallion.png" width="30" height="30" class="d-inline-block align-top" alt="">
        Witcher
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span></button>
      </span>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <!-- <router-link class="router-link-style" to="/services">Services<br></router-link> -->
          <!-- <router-link class="router-link-style" to="/calendar">Calendar<br></router-link> -->
          <router-link class="router-link-style" to="/about">About<br></router-link>
          <!-- <router-link class="router-link-style" to="modal">Contact for a Quote<br></router-link> -->
          <router-link class="router-link-style" to="/wintering"><b>Wintering</b><br></router-link>
        </div>
      </div>
    </nav>
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view />
  </div>
</template>

<script>
  export default {
    watch: {
      '$route'() {
        $('#collapse').collapse('hide');
      }
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }

  #nav {
    padding: 30px;
  }

  #nav a {
    font-weight: bold;
    color: #2c3e50;
  }

  #nav a.router-link-exact-active {
    color: #42b983;
  }
</style>