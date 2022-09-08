<template>
 
  <spt-header />
  <div class="main">
    <spt-cadastro-produto/>
    <spt-pedido />
  </div>
  <spt-valor-compra />

</template>

<script>
import SptHeader from './components/SptHeader.vue';
import SptValorCompra from './components/SptValorCompra.vue'
import SptPedido from './components/SptPedido.vue'
import SptCadastroProduto from './components/SptCadastroProduto.vue';

export default {
  name: 'App',
  components: {
  SptHeader, 
  SptValorCompra,
  SptPedido,
  SptCadastroProduto
  }
}
</script>

<style>
  .main{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    flex-wrap: nowrap;
    width: 100%;

  }

</style>