<template>
    <section>
        <Offer/>
        <Article/>
    </section>
</template>

<script>
    import Offer from "./Offer";
    import Article from "./Article";

    export default {
        name: "Body",
        components: {Article, Offer}
    }
</script>

<style scoped>

</style>
