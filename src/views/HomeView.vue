<template>
  <main class="home">
    <h1>Home</h1>
    <p>欢迎来到首页！</p>
    <router-link to="/about">去 About</router-link>
  </main>
</template>

<script setup>
</script>

<style scoped>
.home {
  padding: 2rem;
}
h1 {
  margin-bottom: 0.5rem;
}
p {
  margin-bottom: 1rem;
  color: #555;
}
</style>
