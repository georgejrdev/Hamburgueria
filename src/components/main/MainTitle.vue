<template>
    <h2>A SUA <span>MELHOR</span> ESCOLHA</h2>
</template>


<script>
    export default {
        name: 'MainTitle'
    }
</script>


<style scoped>
    h2 {
        margin: auto;
        width: 90vw;
        font-size: 28px;
        text-align: center;
        color: #353535;
    }

    span{
        color: #A72424;
    }

    @media screen and (min-width: 1024px) { 
        h2 {
            font-size: 56px;
        }
    }
</style>