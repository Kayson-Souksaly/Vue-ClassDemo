<script setup>
import CounterBtn from './components/Calculator.vue'
</script>

<template>
  <header>
    <h2 class="green">Vue Calculator App 🚀</h2>
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
