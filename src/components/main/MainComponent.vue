<template>
    <main>
        <MainTitle />

        <section id="food-list">
            <CardFood />
            <CardFood />
            <CardFood />
        </section>
    </main>
</template>


<script>
    import MainTitle from './MainTitle.vue'
    import CardFood from './CardFood.vue'

    export default {
        name: 'MainComponent',
        components: {
            MainTitle,
            CardFood
        }
    }
</script>


<style scoped>
    main {
        width: 100vw;
        max-width: 100%;
        padding-top: 10vh;
        min-height: 80vh;
        padding-bottom: 10vh;
    }

    #food-list {
        margin:auto;
        margin-top: 10vh;
        width: 90vw;
        display: flex;
        justify-content: space-around;
        align-items: center;
        flex-wrap: wrap;
        gap: 50px;
    }
</style>