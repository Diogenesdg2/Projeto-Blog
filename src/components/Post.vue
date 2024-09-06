<script>
    export default{
        name:'Post',
        props: {
            imagem:{
                type: String,
                required:false
            },
            titulo: {
                type: String,
                required:true
            },
            texto: {
                type: String,
                required:true
            },
            autor: {
                type: String,
                required:true
            }
        }
    }
</script>

<template>
    <div>
        <img src="">
        <h1>
            {{ titulo }}
        </h1>
        <p>
            {{ texto }}
        </p>
        
        <p>{{ autor }}</p>
    </div>
    
</template>

<style scoped>
</style>