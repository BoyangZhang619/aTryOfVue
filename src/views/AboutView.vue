<template>
  <main class="about">
    <h1>About</h1>
    <p>欢迎来到关于页！</p>
    <router-link to="/">去 Home</router-link>
  </main>
</template>

<script setup>
</script>

<style scoped>
.about {
  padding: 2rem;
  background-color: #555a;
}
h1 {
  margin-bottom: 0.5rem;
}
p {
  margin-bottom: 1rem;
  color: #555;
}
</style>
