<script>

import ComponenteCabecalho from './components/ComponenteCabecalho.vue'
export default{
  name:"App",
  data() {
    return {
      nome: "Diógenes Gomes"
    }
  }
}


</script>

<template>
  <div>

    <header>

      <div class="etecCabecalho">
        <img src="./assets/favicon.png">
      </div>
 
      <div class="btnSair">
        <img src="./assets/exit.png">
        <span> {{ nome }} </span>
      </div>

    </header>

  <div class="logo">
    <img src="./assets/imagemysql.jpg" alt="imgsql" class="img1">
    <div>
      <h2>Titulo</h2>
      <p>Aqui haverá um texto Aqui haverá o texto 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
Suspendisse euismod dignissim lectus in tempus. Phasellus quis porttitor leo.<br>
Vestibulum ant...</p>
<p class="autor">Aleksander Gustavo</p>
    </div>
  </div>

  <br>

  <div class="logo">

    <img src="./assets/imgjavascript.jpg" alt="javascriptimg" class="img1">
    
    <div>
      <h2>Titulo</h2>
      <p>Aqui haverá um texto Aqui haverá o texto 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
Suspendisse euismod dignissim lectus in tempus. Phasellus quis porttitor leo.<br>
Vestibulum ant...</p>
<p class="autor">Aleksander Gustavo</p>
    </div>

  </div>

  <br>

  <div class="logo">
    <img src="./assets/php.jpg" alt="php" class="img1">
    <div>
      <h2>Titulo</h2>
      <p>Aqui haverá um texto Aqui haverá o texto 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
Suspendisse euismod dignissim lectus in tempus. Phasellus quis porttitor leo.<br>
Vestibulum ant...</p>
<p class="autor">Aleksander Gustavo</p>
    </div>
  </div>

</div>
</template>


<style scoped>

.logo {
  background-color: grey;
  padding: 10px;
}

.img1 {
  width: 600px;
}

.btnSair {
  float: right;
}

.autor {
  font-size: 0.8em;
}

h2 {
  color: black;
  font-weight: bolder;
}

h6 {
  color: black;
}

p {
  color: black;
}
</style>