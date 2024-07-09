<template>
    <section>
        <LocalTitle />
        <LocalMap />
    </section>
</template>


<script>
    import LocalTitle from './LocalTitle.vue'
    import LocalMap from './LocalMap.vue'

    export default {
        name: 'LocalComponent',
        components: {
            LocalTitle,
            LocalMap
        }
    }
</script>


<style scoped>
    section {
        background: linear-gradient(to bottom, #FFF 0%, #D78A31 88%);
        width: 100vw;
        max-width: 100%;
        padding-top: 10vh;
        padding-bottom: 10vh;
        height: 80vh;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
    }

    @media screen and (min-width: 1024px) {
        section {
            background: #D78A31;
        }
    }
</style>