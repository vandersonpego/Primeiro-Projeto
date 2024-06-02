<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Confira o cardápio e personalize o seu lanche,<br>
      clique em
      <a href="https://casaeconstrucao.org/comercio/cardapio-de-hamburguer-artesanal/" target="_blank" rel="noopener">Cardápio de hamburguer artesanal</a>.
    </p>    
  </div>
</template>

<script>
export default {
  name: 'BurgerNew',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #534504c0;
}
</style>
