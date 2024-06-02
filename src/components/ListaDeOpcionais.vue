<template>
  <h3>Selecione os opcionais</h3>
  <div id="v-model-multiple-checkboxes">
    <input type="checkbox" id="Bacon" value="Bacon" v-model="checked" />
    <label for="Bacon">Bacon</label>
    <input type="checkbox" id="Salame" value="Salame" v-model="checked" />
    <label for="Salame">Salame</label>
    <input type="checkbox" id="Cebola" value="Cebola" v-model="checked" />
    <label for="Cebola">Cebola</label>
    <br />
    <input type="checkbox" id="Cheddar" value="Cheddar" v-model="checked" />
    <label for="Cheddar">Cheddar</label>
    <input type="checkbox" id="Tomate" value="Tomate" v-model="checked" />
    <label for="Tomate">Tomate</label>
    <input type="checkbox" id="Alface" value="Alface" v-model="checked" />
    <label for="Alface">Alface</label>
    <br />
    <option value> </option>
    <input type="button" value="Criar meu Hambúrger">
  </div>
  <br />
</template>

<script>
export default {
  name: 'ListaDeOpcionais',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
label {
  color: #000000;
  font-size: 20px;
}
input{
  font-size: 20px;
  color: #f8f2ea;
  background-color: rgb(104, 84, 58);

}
</style>
