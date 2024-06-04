<template>
  <label>Selecione uma opção</label>
  <select name="opções" id="opções">
    <option value="opção1">Opção 1</option>
    <option value="opção2">Opção 2</option>
    <option value="opção3">Opção 3</option>
  </select>
</template>

<script>
export default {
  name: "HelloWorld-c2",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
label {
  margin: 10px;
  font-weight: bolder;
  color: #65c7cf;
}
select {
  color: #163741;
}
option {
  color: #163741;
}
</style>
