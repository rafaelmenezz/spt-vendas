<template>
 
  <spt-header />
  <div class="tabela">
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
  .tabela{
    display: flex;
    margin-top: 25px;
    margin-left: 25px;
    width: 100vw;
  }

</style>