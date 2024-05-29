<template>
  <div class="flex flex-row items-center gap-x-12">
    <div class="flex flex-col">
      <p class="font-bold">{{ props.name }}</p>
      <div class="grid grid-cols-2 gap-x-1">
        <p class="col-span-1 flex flex-row justify-between">Battery Level <span>:</span></p>
        <p class="col-span-1">{{ batteryLevel }}</p>
      </div>
      <div class="grid grid-cols-2 gap-x-1">
        <p class="col-span-1 flex flex-row justify-between">Device Status <span>:</span></p>
        <p class="col-span-1">{{ deviceStatus }}</p>
      </div>
      <div class="grid grid-cols-2 gap-x-1">
        <p class="col-span-1 flex flex-row justify-between">Location <span>:</span></p>
        <p class="col-span-1">{{ location }}</p>
      </div>
      <div class="grid grid-cols-2 gap-x-1">
        <p class="col-span-1 flex flex-row justify-between">Panic Button <span>:</span></p>
        <p class="col-span-1">{{ panicButtonStatus }}</p>
      </div>
    </div>
    <button>
      <Icon icon="material-symbols-light:expand-circle-right" class="text-4xl text-blue-500" />
    </button>
  </div>
</template>

<script setup>
import { Icon } from '@iconify/vue'

const props = defineProps({
  name: String,
  batteryLevel: Number,
  deviceStatus: String,
  location: String,
  panicButtonStatus: String
})
</script>

<style></style>
