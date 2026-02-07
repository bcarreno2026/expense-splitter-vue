<template>
  <main class="card">
    <slot />
  </main>
</template>

<style scoped>
.card {
    width: min(600 px, 100%);
    background: #1a1a1a;
    padding: 18px;
    border-radius: 16px;
    box-shadow: 0 10px 24px rgba(255, 165, 0, 0.3);
    border: 2px solid #267809;
}
</style>