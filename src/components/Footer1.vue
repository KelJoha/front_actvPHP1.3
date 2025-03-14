<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">--Cliquea--Contador va en {{ count }}</button>
    <p>
      KellyPrieto Proyecto usando
      <code>components/HelloWorld.vue</code> para prueba de componentes.
    </p>
  </div>

  <p>
    Revisa
    <a href="https://www.youtube.com/" target="_blank"
      >YouTube</a
    >, para más información =).
  </p>
  <p>
    Para más, click en:::
    <a
      href="https://www.google.co.uk/"
      target="_blank"
      >Google</a
    >.
  </p>
  <p class="read-the-docs">Recuerda seguir Mejorando =)</p>
</template>

<style scoped>
.read-the-docs {
  color: #df0d17;
}
</style>
