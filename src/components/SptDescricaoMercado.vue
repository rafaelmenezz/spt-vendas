<template>
  
  <header>
      <div class="imgBx">
            <img src="@/assets/logo_cp.png" alt=""> 
      </div>
      <div class="detalhes">
            <p>Nome do Supermercado</p>
            <p>Nome de Fantasia</p>
            <p>AVENIDA FULANO DE TAL, 999</p>
            <p>CENTRO - AQUINÓPOLIS-SC</p>
            <p>CEP 45820-280 </p>
      </div>
       
  </header>

</template>

<script>
export default {
      name: 'SptDescricaoMercado'

}
</script>

<style scoped>
      header{
            display: flex;
            padding: 0;
            align-items: center;
            border-bottom: 1px solid #000;
      }
      header .detalhes{
            width: 100%;
            margin-top: 0;
            text-align: center;
      }
       header .detalhes p{
            font-family: 'Courier New', Courier, monospace;
            margin-bottom: 0;
       }

.imgBx{
      position: relative;
      width: 220px;
      height: 220px;
      border-radius: 50%;
      overflow: hidden;

      
}

.imgBx img{
      position:absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
}

</style>