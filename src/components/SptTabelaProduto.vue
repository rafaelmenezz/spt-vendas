<template>
   <tbody>
      
      <tr>
         <td>Celular Samsung</td>
         <td>1800.00</td>
         <td>3</td>
         <td>0</td>
         <td>4400.00</td>
      </tr>
      <tr>
         <td>Celular Samsung</td>
         <td>1800.00</td>
         <td>3</td>
         <td>0</td>
         <td>4400.00</td>
      </tr>
      <tr>
         <td>Celular Samsung</td>
         <td>1800.00</td>
         <td>3</td>
         <td>0</td>
         <td>4400.00</td>
      </tr>
      <tr>
         <td>Celular Samsung</td>
         <td>1800.00</td>
         <td>3</td>
         <td>0</td>
         <td>4400.00</td>
      </tr>

   </tbody>
</template>
<script>
export default {
   name: 'SptTabelaProduto'
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@200;300;400;500;600;700;800;900&display=swap');

td {

   font-family: 'Inconsolata',  Courier, monospace;
   letter-spacing: 2px;
   padding: 5px;
   border-bottom: 1px dashed #000; 

}



td:nth-child(1)
{
   text-align: left;
}

td:nth-child(2),
td:nth-child(3),
td:nth-child(4){
   text-align: center;
}

td:nth-child(5){
   text-align: right;
}
</style>