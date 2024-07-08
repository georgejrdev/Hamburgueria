<template>
    <header>
        <HeaderTitle />
    </header>
</template>


<script>
    import HeaderTitle from './HeaderTitle.vue'

    export default {
        name: 'HeaderComponent',
        components: {
            HeaderTitle,
        }
    }
</script>


<style scoped>
    header {
        width: 100vw;
        max-width: 100%;
        height: 100vh;
        background: linear-gradient(to bottom, #FF8A00 0%, #FFF 77%);
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>