<template>
    <div id="card">

    </div>
</template>


<script>
    export default {
        name: 'CardFood'
    }
</script>


<style scoped>
    #card {
        width: 250px;
        height: 250px;
        background-color: #EBEBEB;
        border-radius: 40px;
    }

    @media screen and (min-width: 1024px) {
        #card {
            width: 300px;
            height: 300px;
        }
    }
</style>