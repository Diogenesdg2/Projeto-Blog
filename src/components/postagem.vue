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
        <img v-if="imagem" :src="imagem" alt="sem imagem">

        <h1>{{ titulo }}</h1>

        <p>{{ mensagem }}</p>

        <p>{{ autor }}</p>
    </div>
</template>

<style scoped>
#container{
    position: relative;
    background-color: rgb(228, 228, 228);
    width: 1300px;
    height: 720px;
}

#container img{
    margin: 25px 75px;
    position: relative;
    
    
    

}
#container h1{
    position: absolute;
    
    left: 100px;
    color: black;
       
}
#container p:nth-of-type(1){
    color: brown;
    display: flex;
    margin-left: 110px;
}
#container :nth-child(3){
    color: aquamarine;
}
</style>