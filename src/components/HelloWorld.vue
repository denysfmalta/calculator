<template>
  <h1>Calculadora</h1>
  <h3>Denys Ferreira Malta</h3>
  <div class="calculator">
    <div class="display">
      {{ current || 0 }}
    </div>
    <div>C</div>
    <div>0</div>
    <div>+/-</div>
    <div>%</div>
    <div>/</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>*</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>-</div>
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>+</div>
    <div>.</div>
    <div>=</div>
    <div>0</div>
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
