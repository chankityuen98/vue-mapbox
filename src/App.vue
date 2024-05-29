<script setup>
import Card from './components/Card.vue'
import ParticipantCard from './components/ParticipantCard.vue'
import ParticipantList from './components/ParticipantList.vue'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <h1 class="text-green-700">Home page</h1>
    </div>
  </header> -->

  <main class="bg-gray-100">
    <ParticipantList />
    <Card icon="teenyicons:tick-circle-outline" amount="150" description="Testing description" />
  </main>
</template>

<style scoped></style>
