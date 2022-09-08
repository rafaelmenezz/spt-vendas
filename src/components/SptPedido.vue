<template>
   <div class="recibo">
      <spt-descricao-mercado />

      <h2>Cupom Fiscal</h2>
      <div class="tabela-recibo">
         <table>
            <thead>
              <tr>
                  <th>Nome</th>
                  <th>R$ Unit.</th>
                  <th>Qtd.</th>
                  <th>R$ Desc</th>
                  <th>Total</th>
               </tr>

            </thead>
            <spt-tabela-produto />
         </table>
      </div>
   </div>
</template>
<script lang="js">
import SptTabelaProduto from './SptTabelaProduto.vue'
import SptDescricaoMercado from './SptDescricaoMercado.vue';
export default {
   name: 'SptPedido',

   components: {
      SptTabelaProduto,
      SptDescricaoMercado
   }
}
</script>
<style  scoped>
.recibo {
   margin-top: 10px;
   margin-right: 10px;
   border-radius: 20px;
   width: 100%;
   padding-bottom: 0;
   background: #fff0b8;
   overflow-y: auto;
   overflow-x: hidden;
}
.recibo h2{
   font-family: 'Courier New', Courier, monospace;
   letter-spacing: 1px;
   width: 100%;
   text-align: center;
   margin: 15px 0;
}

.tabela-recibo {
   padding: 5px;
}

table {
   font-family: 'Courier New', Courier, monospace;
   border-spacing: 1;
   border-collapse: collapse;
   overflow: hidden;
   width: 100%;
   border-radius: 10px 10px 0px 0px;
   margin: 20px 10px;
}


th {

   border-bottom: 1px dashed #000; 
   font-family: 'Courier New', Courier, monospace;
}

th:nth-child(1)
{
   text-align: left;
}

th:nth-child(2),
th:nth-child(3),
th:nth-child(4){
   text-align: center;
}

th:nth-child(5){
   text-align: right;
}
</style>