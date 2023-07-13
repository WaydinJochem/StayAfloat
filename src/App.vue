<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>
<script>
</script>

<style>
body {
  background-image:
    radial-gradient(at top left, transparent 72%, #3BADCF 10%, #054D62),
    radial-gradient(at top left, transparent 70%,#6CC2DB 10%),
    radial-gradient(at top left, transparent 69%, #043D4E 10% ),
    linear-gradient(125deg,transparent, white);
  background-size: 100%;
  background-attachment: fixed;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
