<template>
  <div class="santol">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Santol, Ampalaya, Manok',
      message: 'I like santol , Ampalaya and Manok'
    }
  }
};
</script>

<style>
 .santol {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgba(91, 50, 168, 0.384);
  }

</style>