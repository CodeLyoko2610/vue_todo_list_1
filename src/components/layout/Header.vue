<template>
  <header class="header">
    <h1>Todo List 1</h1>
     <div id="nav">
      <router-link to="/">Home</router-link>| 
      <router-link to="/about">About</router-link>|
      <router-link to="/hello-world">Hello World</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
  .header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
  }
  .header a {
    color: #fff;
    padding-right: 5px;
    text-decoration: none;
  }
  #nav {
  padding: 30px;
  }
  #nav a {
    font-weight: bold;
    color: #ffffff;
  }
  #nav a.router-link-exact-active {
    color: #42b983;
  }
</style>