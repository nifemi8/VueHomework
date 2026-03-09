<template>
  <div>
    <h1>Hello Vue</h1>
    <p>This is my Vue homework app.</p>

    <button @click="count++">
      Clicked {{ count }} times
    </button>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>
