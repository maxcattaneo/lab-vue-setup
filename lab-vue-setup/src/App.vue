<template>
  <div class="flex-col">
    <NewComponent/>
    <div>Message: {{ mensaje }}</div>
    <button @click="helloWord">Saludo</button>
  </div>

  
</template>

<script setup>
import NewComponent from './components/NewComponent.vue'
const mensaje = 'Soy un mensaje'
function helloWord() {
  alert(`Hello Word!`)
}

</script>

<style>

</style>
