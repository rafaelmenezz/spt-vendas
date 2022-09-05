<template>
 
  <spt-header />
  <spt-valor-compra />

</template>

<script>
import SptHeader from './components/Spt-Header.vue';
import SptValorCompra from './components/SptValorCompra.vue'

export default {
  name: 'App',
  components: {
  SptHeader, 
  SptValorCompra
  }
}
</script>

<style>

</style>
