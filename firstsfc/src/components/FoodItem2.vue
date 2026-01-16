<template>
  <div  class="Frutas">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Frutas and Fruits',
      message: 'I like Starapple , Lansones,mangga and egg'
    }
  }
};
</script>

<style>
  .patola {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgb(91, 110, 216);
  }  
</style>