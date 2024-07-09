<template>
    <header>
        <HeaderNavBar />
        <HeaderTitle />
    </header>
</template>


<script>
    import HeaderNavBar from './HeaderNavBar.vue'
    import HeaderTitle from './HeaderTitle.vue'

    export default {
        name: 'HeaderComponent',
        components: {
            HeaderNavBar,
            HeaderTitle
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

    @media screen and (min-width: 1024px) {
        header {
            background: linear-gradient(110deg, #FF8A00 0%, #FFF 50%);
            justify-content: left;
        }        
    }
</style>