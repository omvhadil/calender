<script setup>
import { ref } from 'vue'

// const date = ref(new Date())
const attributes = ref([
  {
    // bar: 'green',
    // dot: 'red',
    highlight: 'red',
    dates: new Date()
  }
])
</script>

<template>
  <div sclass="">
    <VCalendar :attributes="attributes" expanded locale="id" />
    <!-- <VDatePicker v-model="date" mode="time" :timezone="timezone" is24hr hide-time-header /> -->
  </div>
</template>

<style scoped></style>
