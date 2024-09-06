<script>
    export default{
        name:'Post',
        props: {
            imagem:{
                type: String,
                required: false
            },
            titulo: {
                type: String,
                required:false
            },
            mensagem: {
                type: String,
                required:false
            },
            autor:{
                type: String,
                required:false
            }
        }

    }
</script>

<template>
    <div id="container">
        <h1>{{ titulo }}</h1>

        <img v-if="imagem" :src="imagem" alt="sem imagem">
      
        <p>{{ mensagem }}</p>

        <p>{{ autor }}</p>
    </div>
</template>

<style scoped>
#container{
    position: relative;
    background-color: rgb(187, 181, 181);
    width: 1300px;
    height: 950px;
}

#container img{
    margin: 25px 75px;
    position: relative;
}

#container h1{
    position: relative ;
    
    left: 110px;
    color: black;       
}

#container :nth-child(2){
    font-size: 20px;
    color: black;
    display: flex;
    text-align: justify;
    margin-left: 50px;
    margin-right: 10px;
}

#container :nth-child(3){
    font-size: 20px;
    color: black;
    display: flex;
    text-align: justify;
    margin-left: 50px;
    margin-right: 10px;
}

#container :nth-child(4){
    font-size: 20px;
    color: black;
    display: flex;
    text-align: justify;
    margin-left: 50px;
    margin-right: 10px;

}

</style>