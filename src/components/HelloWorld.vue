<template>
  <h1>Calculadora</h1>
  <h3>Denys Ferreira Malta</h3>
  <div class="calculator">
    <div class="display">
      {{ current || 0 }}
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped></style>
