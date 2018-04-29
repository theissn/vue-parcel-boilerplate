<template>
  <div id="home">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
  export default {
    name: 'home',
    data() {
      return {
        msg: 'Home sweet home',
      };
    },
  };
</script>

<style scoped>

  .home p {
    color: red;
  }

</style>