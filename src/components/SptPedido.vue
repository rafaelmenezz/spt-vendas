<template>
   <content class="produto-container">
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
   </content>
</template>
   <script lang="js">
   import SptTabelaProduto from './SptTabelaProduto.vue'
   export default {
      name:'SptPedido',

      components: { SptTabelaProduto }
   }
   </script>
   <style  >
      .produto-container{
         width: 100%;
      
         position: relative;
         
      }

    table {
      border-spacing: 1;
      border-collapse: collapse;
      background: #fff;
      overflow: hidden;
      width: 60vw;
      margin: 0 auto;
      border-radius: 10px 10px 0px 0px;
      margin-bottom: 20px;
   }
   
   table td,
   table th {
      padding-left: 30px;
   }
   
   table th {
      height: 60px;
      background: #36304a;
   }
   
   table tbody tr {
      height: 60px;
      border: 0.5px solid rgb(170, 170, 170);
   }
   
   table td,
   table th {
      text-align: left;
   }
   
   th {
      font-family: OpenSans-Regular;
      font-size: 18px;
      color: #fff;
      line-height: 1.2;
      font-weight: unset;
   }
   
   tbody tr:nth-child(even) {
      background-color: #f5f5f5;
   }
   
   tbody tr {
      font-family: OpenSans-Regular;
      font-size: 15px;
      color: gray;
      line-height: 1.2;
      font-weight: unset;
   }
   </style>