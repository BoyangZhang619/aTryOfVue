<script setup>
  import HelloWorld from '../components/HelloWorld.vue';
</script>
<template>
  <main class="home">
    <h1>Home</h1>
    <p>欢迎来到首页！</p>
    <router-link to="/about">去 About</router-link><br/>
    <router-link to="/games">去 Games</router-link><br/>
    <HelloWorld msg="Vite + Vue" />
  </main>
</template>
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
