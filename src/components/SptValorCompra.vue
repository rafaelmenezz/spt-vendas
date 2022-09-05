<template>
  <section>
      <div class="total">
            <div class="bruto">
                  <span class="title">Total Itens</span>
                  <span class="valor">R$ 2.441,00</span>
            </div>
            <div class="desconto">
                  <span class="title">Total Desconto</span>
                  <span class="valor">R$ 0,00</span>
            </div>
      </div>
      <div class="total-compra">
            <div>
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
    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
section{
            position: fixed;
            bottom: 30px;
            right: 10px;
            width: 40%;
            flex-direction: row;
            min-height: 300px;
            font-family: "Poppins";
      }
      .total{
            display: grid;
            grid-template-columns: repeat(2,1fr);
            gap: 10px;
            width: 100%;
            justify-content: space-between;
      }   
      .total .bruto{
            width: 50%;
      }

      .total .bruto,
      .total .desconto{
            display: grid;
            width: 100%;
            padding: 20px;
    
           
      }
    .total-compra{
            margin-top: 10px;
            grid-area: repeat(1,1fr);
            width: 100%;
      }
      .total-compra div{
            display: grid;
            padding: 20px;
            width: 100%;
      }
   
      .title{
            font-size: 1.8em;
            width: 100%;
            text-align: left;
            font-weight: 800;
            border-bottom: 1pt solid #000;
      }
      .valor{
            padding: 10px 0;
            font-family: "Poppins";
            text-align: right;
            font-size: 1.8em;
      }




</style>