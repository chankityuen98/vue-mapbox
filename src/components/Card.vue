<template>
  <div class="flex flex-row gap-x-4 items-center px-3 py-6 bg-white max-w-52 rounded-lg">
    <div class="bg-blue-300 p-2 rounded-full">
      <Icon :icon="props.icon" class="text-blue-500 text-2xl" />
    </div>
    <div class="flex flex-col">
      <p>{{ props.amount }}</p>
      <p class="text-gray-500">{{ props.description }}</p>
    </div>
  </div>
</template>

<script setup>
import { Icon } from '@iconify/vue'

const props = defineProps({
  amount: Number,
  description: String,
  icon: String
})
</script>

<style></style>
