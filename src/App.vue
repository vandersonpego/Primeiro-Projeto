<template>
  <img alt="Vue logo" src="./assets/burger.png">
  <BurgerNew msg="Monte o seu Burger"/>
  <ListaDePaes />
  <ListaDeCarnes />
  <ListaDeOpcionais />

</template>

<script>
import BurgerNew from './components/BurgerNew.vue'
import ListaDePaes from './components/ListaDePaes.vue'
import ListaDeCarnes from './components/ListaDeCarnes.vue'
import ListaDeOpcionais from './components/ListaDeOpcionais.vue'

export default {
  name: 'App',
  components: {
    BurgerNew, ListaDePaes, ListaDeCarnes, ListaDeOpcionais
  }
}
</script>
<style>

#app {
  font-family:Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  text-align:center;
  color: #052002;
  margin-top: 0px;
  background-image: linear-gradient(to top, rgb(191, 218, 149), rgb(48, 99, 60))
}

</style>
