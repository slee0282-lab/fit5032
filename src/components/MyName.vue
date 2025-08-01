<!-- src/components/MyName.vue -->
<template>
  <div class="my-name">
    <h2>Hello</h2>
    <p>My name is <strong>Seungho</strong>. Please refer my Github repository below</p>
    <a href="https://github.com/slee0282-lab/fit5032" target="_blank" rel="noopener"></a>
  </div>
</template>

<script>
export default {
  name: 'MyName',
}
</script>

<style scoped>
.my-name {
  border: 2px dashed #42b983;
  padding: 1rem;
  margin: 2rem 0;
  background-color: #f0f9f5;
  color: #2c3e50;
  font-family: 'Segoe UI', sans-serif;
}
</style>
