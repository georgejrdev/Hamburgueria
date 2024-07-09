<template>
    <h2>EM <span>TODA</span> ESQUINA</h2>
</template>


<script>
    export default {
        name: 'LocalTitle'
    }
</script>


<style scoped>

    h2 {
        margin: auto;
        width: 90vw;
        font-size: 28px;
        text-align: center;
        color: #404040;
    }

    span {
        color: rgb(0, 0, 0);
    }

    @media screen and (min-width: 1024px) { 
        h2 {
            color: black;
            font-size: 56px;
        }        

        span {
            color: white;
        }
    }
</style>