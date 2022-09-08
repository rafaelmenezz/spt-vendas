<template>
  <section>
      <div class="valores">
            <div class="bruto">
                  <span class="title">Total Itens</span>
                  <span class="valor">R$ 2.441,00</span>
            </div>
            <div class="desconto">
                  <span class="title">Total Desconto</span>
                  <span class="valor">R$ 0,00</span>
            </div>
     
            <div class="total">
                  <span class="title">Total da Venda</span>
                  <span class="valor">R$ 2.441,00</span>
            </div>
      </div>
  </section>
</template>

<script>
export default {
      name: 'SptValorCompra'

}
</script>

<style scope>
   
section{
            position: fixed;
            display: flex;
            bottom: 0;
            left: 0;
            width: 100%;
            flex-direction: column;
            min-height: auto;
            font-family: "Poppins";
      }
      .valores{
            width: 100%;
            display: flex;

      }   

      .valores .bruto,
      .valores .desconto,
      .valores .total{
            display: flex;
            flex-direction: column;
            width: 100%;
            padding: 20px;
    
           
      }

      .valores .bruto,
      .valores .desconto{
            width: 70%;
      }
    
      .total-compra{
            margin-top: 10px;
            grid-area: repeat(3,2fr);
            width: 100%;
      }
      .total-compra div{
            display: grid;
            padding: 20px;
            width: 100%;
      }
   
      .title{
            font-size: 1.5em;
            width: 100%;
            text-align: left;
            font-weight: 800;
            border-bottom: 1pt solid #000;
      }
      .valor{
            padding: 10px 0;
            font-family: "Poppins";
            text-align: right;
            font-size: 2.2em;
      }




</style>