<template>
  <div>
    <h1> Home page </h1>
    <nav>
      <NuxtLink to="/docs">Docs</NuxtLink>
      <NuxtLink to="/learn">Learn</NuxtLink>
    </nav>
    <p>This is the home page.</p>
    <a href="https://www.google.com">External link to google.com</a>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
  nav {
    background: navy;
    height: 36px;
    width: 100%;
  }
  nav a {
    color: white;
    text-decoration: none;
    padding: 0 24px;
    margin: 0 24px;
    line-height: 36px;
    font-size: 20px;
  }
</style>