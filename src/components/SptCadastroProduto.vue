<template lang="">
      <form class="cadastro-produtos">
         <h1>Produto</h1>
         <div class="card-cadastro">
            <div class="form-input cod-barras">
               <label for="codBarras">Código de barras</label>
               <input type="number" name="codBarras" id="codBarras" />
            </div>
            <div><i class="fa-solid fa-xmark"></i></div>
         </div>
         <div class="quantidade">
            <div class="form-input">
               <label for="quantidade">Quantidade</label>
               <input type="number" name="quantidade" id="quantidade" />
            </div>
            <div class="form-input">
               <label for="precoUni">Preço unitário</label>
               <input type="number" name="precoUni" id="precoUni" />
            </div>
         </div>
         <div class="desconto">
            <div class="form-input">
               <label for="Desconto">Desconto</label>
               <input type="number" name="desconto" id="desconto" />
            </div>
            <div class="form-input">
               <label for="precoDesc">Preço c/ desconto</label>
               <input type="number" name="precoDesc" id="precoDesc" disabled />
            </div>
         </div>
         <div class="checked">
            <i class="fa-solid fa-check"></i>
         </div>
      </form>
   </template>
   <script>
   export default {
      name: 'SptCadastroProduto'
   }
   </script>
   <style scoped>
   input{
      height: 30px;
      width: 190px;   
      outline: none;
      border: none;
      border-bottom: 2px solid rgb(189, 206, 158);
      padding: 10px 10px;
      font-size: 20px;
   }
   input:focus{
      border-bottom: 2px solid rgb(0, 0, 0);
   }
   
   input:disabled{
      background: none;
      background: rgb(247, 247, 247);
      border-radius: 10px;
      border: 1px solid rgb(165, 165, 165);
   }
   
   .cadastro-produtos {
      position: relative;
      padding: 0 30px;
      width: 35vw;
      
   }
   .card-cadastro,.quantidade,.desconto {
      margin-bottom: 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
   }
   .card-cadastro{
      margin-bottom: 50px;
      border-bottom: 2px solid rgb(209, 209, 209);
      padding-bottom: 10px;
   }
   .form-input{
      display: flex;
      flex-direction: column;
   }
   #codBarras{
      width: 100%;
   }
   .cod-barras{
      width: 350px;
   }
   
   .card-cadastro i , .checked{
      font-size: 40px;
      color: white;
      
      background: red;
      padding: 5px 40px;
      border-radius: 10px;
      transition: all ease 0.7s;
   }
   .card-cadastro i:hover{
      cursor: pointer;
      background: rgba(255, 0, 0, 0.705);
   }
   
   .checked{
      background: rgb(124, 218, 37);
      
   }
   .checked:hover{
      cursor: pointer;
      background: rgba(125, 218, 37, 0.658);
      
   }
   
   
   </style>