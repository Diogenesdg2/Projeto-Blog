<script>
import Botao from './Botao.vue';

  export default{
    name: "Cabeçalho",
    props: {
      logotipo:{
        type: String,
        required:false
      },
      textoBotao: {
        type: String,
        required: false
      },
      link: {
        type: String,
        required: false
      },
      components: {
        Botao
      }
    }
  }
</script>

<template>
    <div>
       
  <div class="etecCabecalho">
    <img :src="logotipo">
  </div>
    <Botao textodoBotao="Acessar Agora" link="http://youtube.com.br" />
  
  </div>
  
  </template>
  
  
  <style>
  .etecCabecalho {
    display: flex;
    justify-content: left;
    width: 75px;
    height: 75px;
  }
  
  .btnSair {
    display: flex;
    justify-content: flex-end;
   
  
  }
  </style>