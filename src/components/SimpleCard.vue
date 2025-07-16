<template>
  <div class="card">
    <slot />
  </div>
</template>

<style scoped lang="scss">
.card {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  padding: 2rem;
  border-radius: 0.25rem;
  background-color: var(--pico-card-background-color);
  border: 1px solid var(--pico-muted-border-color);
  box-shadow: var(--pico-box-shadow);
  width: 300px;
  text-align: center;
}
</style>
