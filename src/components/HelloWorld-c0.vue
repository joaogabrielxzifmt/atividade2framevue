<template>
  <h1>{{ msg }}</h1>
  <h3>Aluno: João Gabriel</h3>
</template>

<script>
export default {
  name: "HelloWorld-c0",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0 0;
}
h3 {
  margin: 10px 0 0;
  font-size: 24px;
}
</style>
