<script setup>
import CardVue from './components/Card.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <h1 class="text-green-700">Home page</h1>
    </div>
  </header>

  <main>
    <CardVue icon="teenyicons:tick-circle-outline" amount="150" description="Testing description" />
  </main>
</template>

<style scoped></style>
