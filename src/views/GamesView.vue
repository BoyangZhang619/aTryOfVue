<script setup>
const games = [
    { id: '2048', title: '2048' },
    { id: 'klotski', title: 'Klotski' },
]
</script>


<template>
  <div style="padding: 20px">
    <h1>Games</h1>
    <p>这里是游戏列表页（/games）</p>

    <ul>
      <li v-for="g in games" :key="g.id">
        <!-- 先占位：未来我们会跳到 /game/:id -->
        {{ g.title }} (id: {{ g.id }})
      </li>
    </ul>

    <p style="margin-top: 16px">
      <router-link to="/">← 回首页</router-link>
    </p>
  </div>
</template>