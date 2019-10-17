<template>
    <div>
        <header>
            <Header/>
        </header>
        <main>
            <Body/>
        </main>
        <footer>
            <Footer/>
        </footer>
    </div>
</template>

<script>
    import Header from "../components/Header";
    import Body from "../components/Body";
    import Footer from "../components/Footer";

    export default {
        name: 'home',
        components: {Footer, Body, Header},
    }
</script>

<style lang="sass" scoped>
</style>
