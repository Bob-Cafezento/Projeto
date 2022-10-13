<script>
export default {
    methods: {
        goLinguagens() {
            alert('oioi')
        }
    }
}
</script>

<template>
    <!--Aqui nós temos o resto do conteúdo-->
    <h1>
        SUCCESS STUDENT
    </h1>
    <div id="abrangent">
        <main>
            <div class="box" @click="$router.push('/linguagens')">
                <img src="@/assets/imagens/Linguagens.png">
                Português
            </div>
            <div class="box" @click="$router.push('/matematica')">
                <img src="@/assets/imagens/Esquadro.png">
                Matemática
            </div>
            <div class="box">   
                <img src="@/assets/imagens/Ampulheta.png"><br>
                História
            </div>
            <div class="box">
                <img src="@/assets/imagens/geografia.png" ><br>
                Geografia
            </div>
        </main>
    </div>
</template>

<style scoped>
.box img {
    width: 60%;
    max-height: 200px;
}
</style>