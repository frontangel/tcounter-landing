<script setup lang="ts">
  const goApp = () => (window.location.href = 'https://app.tcounter.pp.ua')
</script>

<template>
  <main class="wrap">
    <h1>TrafficClicker</h1>
    <p>
      Додаток для замірів трафіку: запускай замір, клікай, дивись статистику по часу та середній трафік/год.
    </p>

    <button class="btn" @click="goApp">Перейти в додаток</button>

    <p class="small">
      PWA • швидка авторизація через Telegram • офлайн режим (незабаром)
    </p>
  </main>
</template>

<style scoped>
  .wrap { max-width: 720px; padding: 40px 16px; margin: 0 auto; font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial; }
  .btn { padding: 12px 16px; border-radius: 10px; border: 0; cursor: pointer; font-weight: 600; }
  .small { opacity: .7; margin-top: 16px; }
</style>
