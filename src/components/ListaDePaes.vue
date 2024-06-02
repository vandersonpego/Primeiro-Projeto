<template>
  <div>
    <h3>Nome do Cliente</h3>
    <input name="checkbox" id="Name" value="Name" v-model="checked" />
    <h3>Escolha o pão preferido</h3>
    <label></label>
    <select name="ListaDePaes" id="ListaDePaes">
      <option value="Pão">Selecione o seu pão</option>
      <option value="Pão">Americano</option>
      <option value="Pão">Italiano Branco</option>
      <option value="Pão">Australiano</option>
      <option value="Pão">Brioche</option>
      <option value="Pão">Integral</option>
    </select>
    <option value> </option>
  </div>
</template>

<script>
export default {
  name: 'ListaDePaes',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
select {
  color: #030000;
  font-size: 16px;
  background-color: #f8f2ea;
}
input{
  color: #030000;
  font-size: 14px;
  background-color: #f8f2ea;
}

</style>
