<script setup lang="ts">
import { useCounterStore } from "@/stores/counter";
import PinapleIcon from "~icons/mdi/fruit-pineapple";
import SimpleCard from "./SimpleCard.vue";

const counterStore = useCounterStore();
</script>

<template>
  <main class="container">
    <h1>Vue 3 Playground Template</h1>
    <SimpleCard class="pinia-card">
      <h2><PinapleIcon style="color: yellow" /> Pinia Store</h2>
      <p>Count is {{ counterStore.count }}</p>
      <button @click="counterStore.increment">Increase</button>
    </SimpleCard>
  </main>
</template>

<style scoped lang="scss">
main {
  margin-top: 2rem;
  text-align: center;
}

.pinia-card {
  margin-top: 4rem;
  margin-inline: auto;
}
</style>
