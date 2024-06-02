<template>
  <div>
    <h3>Selecione a carne do seu Burger</h3>
    <label></label>
    <select name="ListaDeCarnes" id="ListaDeCarnes">
      <option value="Carne">Selecione o tipo de carne</option>
      <option value="Carne">Fraldinha</option>
      <option value="Carne">Alcatra</option>
      <option value="Carne">Contrafilé</option>
      <option value="Carne">Picanha</option>
      <option value="Carne">Veggie Burger</option>
    </select>
    <option value> </option>
  </div>
</template>

<script>
export default {
  name: 'ListaDeCarnes',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

select {
  color: #000000;
  font-size: 16px;
  background-color: #f8f2ea;
}
</style>
