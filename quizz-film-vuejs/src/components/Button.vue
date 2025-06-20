<template>

<button>
  <input type="checkbox">{{}}
</button>

</template>

<script>
import { ref,onMounted,onUnmounted } from 'vue'
import from './composable/use.js'
import rawQuizzData from '../quizz-data.json'

function showQuizz(title: string) {
  const quizz = rawtechData.find(t => t.title.toLowerCase() === title.toLowerCase());
  showQuizz().value = techno ?? null;
}

onMounted(() => {
  showTechno('Front-end');
});
</script>

<style>


</style>