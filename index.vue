<template>
  <div>
    <h1>LAB3 - 058ForFork</h1>
    <hr>
    <input type="text" name="userName" id="test" v-model="userName">
    <p>Your Username: {{ userName }}</p>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
const userName = ref<String>('')
</script>
