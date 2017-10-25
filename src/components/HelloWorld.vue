<template>
  <div class="hello">
    <h1>Le compteur est à {{ compteur }}</h1>
    <button class="button is-primary" @click="compteur++">+1</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      compteur: 0,
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
