<template>
    <HeaderComponent />
    <MainComponent />
    <LocalComponent />
</template>


<script>
    import HeaderComponent from './components/header/HeaderComponent.vue'
    import MainComponent from './components/main/MainComponent.vue'
    import LocalComponent from './components/local/LocalComponent.vue'

    export default {
        name: 'App',
        components: {
            HeaderComponent,
            MainComponent,
            LocalComponent
        }
    }
</script>


<style>
    * {
        margin: 0;
        padding: 0;
        font-family: "Open Sans", sans-serif;
    }
</style>