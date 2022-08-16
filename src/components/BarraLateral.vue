<template>
  <header>
    <h1>
      <img
        src="https://bulma.io/images/bulma-logo.png"
        alt="Bulma: a modern CSS framework based on Flexbox"
        width="112"
        height="28"
      />
    </h1>
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'BarraLateral',
});
</script>

<style>
header {
  background-color: #0d3b66;
  width: 100%;
  height: 100vh;
  padding: 1rem;
}

@media (min-width: 768px) {
  header {
    padding: 2.5rem;
    height: 100vh;
  }
}
</style>
