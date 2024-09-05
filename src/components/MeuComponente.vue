<script>
export default{
        name:'MeuComponente',
        props: {
            titulo:{
                type: String,
                required:true
            },
            conteudo:{
                type: String,
                required:true,
                default: 'Esta é uma descrição padrão'
            }
        }
    }
</script>

<template>
    
</template>