<script setup>
import CounterBtn from './components/CounterBtn.vue'
</script>

<template>
  <header>
    <h2>Vue Counter App 🚀</h2>
  </header>

  <main>
    <CounterBtn />
  </main>
</template>

<style scoped>
header {
  text-align: center;
  font-size: 1.5rem;
}

main {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 2rem;
}
</style>
