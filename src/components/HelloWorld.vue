<template>
  <h1>Calculadora</h1>
  <h3>Denys Ferreira Malta</h3>
  <div class="calculator">
    <div class="display">
      {{ current || 0 }}
    </div>
    <div class="btn">C</div>
    <div class="btn">0</div>
    <div class="btn">+/-</div>
    <div class="btn">%</div>
    <div class="btn">/</div>
    <div class="btn">7</div>
    <div class="btn">8</div>
    <div class="btn">9</div>
    <div class="btn">*</div>
    <div class="btn">4</div>
    <div class="btn">5</div>
    <div class="btn">6</div>
    <div class="btn">-</div>
    <div class="btn">1</div>
    <div class="btn">2</div>
    <div class="btn">3</div>
    <div class="btn">+</div>
    <div class="btn">0</div>
    <div class="btn">.</div>
    <div class="btn">=</div>
    <div class="btn"></div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>
.
<style scoped>
.calculator {
  cursor: pointer;
  margin: 0 auto;
  width: 400px;
  font-size: 40px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}

.display {
  grid-column: 1 / 5;
  background-color: #333;
  color: white;
}
</style>
