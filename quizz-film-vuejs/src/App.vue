<template>
  <div>
    <ProgressBar />
  </div>
<div>
  <Button />
</div>

</template>

<script setup>
import ProgressBar from './components/ProgressBar.vue'
import Button from './components/Button.vue'
import { ref,onMounted,onUnmounted } from 'vue'
import quizz from './quizz'
</script>

<style>

</style>