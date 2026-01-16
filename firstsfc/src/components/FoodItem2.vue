<template>
  <div class="Apple">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Apple, Banana, Orange, Egg',
      message: 'I like all of this'
    }
  }
};
</script>

<style></style>