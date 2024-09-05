<script>
import MeuComponente from "./components/MeuComponente.vue"
import postagem from "./components/postagem.vue"
import post1Image from "./components/imgs/post1.jpg"
export default{
        name:'App',
        components: {  
            postagem
    },
    data() {
        return {
            // Define a imagem importada no data para uso em props
            post1Image
        };
    }
}
</script>

<template>
    <div>

        <postagem :imagem="post1Image" titulo="MySQL" mensagem="Aqui vai a mensagem do post 1 " autor="Diogenes Gomes"/>
        <br>
        <postagem :imagem="post1Image" titulo="JAVA" mensagem="Aqui vai a mensagem do post 2 " autor="Diogenes Gomes"/>
        <br>
        <postagem :imagem="post1Image" titulo="PHP" mensagem="Aqui vai a mensagem do post 3 " autor="Diogenes Gomes"/>
    </div>
</template>

<style  scoped>

</style>