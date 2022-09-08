<template>
   <div class="produtos">
      <h2>Nome do Produto</h2>
      <div class="descricao">
         <div class="dados">
            <label for="quantidade">Quantidade</label>
            <input type="number" name="quantidade" id="quantidade" />
         </div>
         <div class="dados">
            <label for="precoUni">Preço unitário</label>
            <input type="number" name="precoUni" id="precoUni" />
         </div>
         <div class="dados">
            <label for="Desconto">Desconto</label>
            <input type="number" name="desconto" id="desconto" />
         </div>
         <div class="dados">
            <label for="precoDesc">Preço c/ desconto</label>
            <input type="number" name="precoDesc" id="precoDesc" disabled />
         </div>
      </div>
   </div>
</template>
<script>
export default {
   name: 'SptCadastroProduto'
}
</script>
<style scoped>
.produtos {
   width: 100%;
   padding: 30px 40px;
   flex: 0 0 60%;
}

.produtos h2 {
   width: 100%;
   margin-bottom: 45px;
   font-size: 2.5em;
   font-weight: 900;
}

.produtos .descricao{ 
   display: flex;
   flex-direction: row;
   flex-wrap: wrap;
   gap: 5%;

}

.dados{
   flex: 0 0 47%;
   margin: 30px 0;
   font-family: "Poppins";
   font-size: 2.5em;
}

.dados label{
  
   margin-bottom: 35px;
   font-weight: 700;
}



input , input:disabled{ 
   height: 30px;
   width: 100%;
   outline: none;
   border: none;
   border-bottom: 2px solid rgb(189, 206, 158);
   padding: 10px 10px;
   font-size: 20px;
}

input:focus {
   border-bottom: 2px solid rgb(0, 0, 0);
}


</style>