<template>
  <button>
    <slot></slot>
  </button>
</template>

<style scoped>
button {
  padding: 0.5rem 2rem;
  border: 1px solid #360032;
  color: white;
  font: inherit;
  cursor: pointer;
  background-color: #360032;
}

button:hover,
button:active {
  border-color: #5c0556;
  background-color: #5c0556;
}
</style>
