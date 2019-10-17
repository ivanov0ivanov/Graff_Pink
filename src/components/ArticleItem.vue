<template>
    <div class="article_container">
        <div class="article_item">
            <img src="../assets/img/png/article-img1.png" alt="article-img">
            <div class="article-heading_container">
                <router-link to="#"><h3 class="article_title">Lorem Ipsum is simply</h3></router-link>
                <p class="article_description">
                    Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown
                    printer took a galley of type and scrambled it to make a type specimen book. It has survived not
                    only five centuries,
                    but also the leap into electronic typesetting, remaining essentially unchanged.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "ArticleItem"
    }
</script>

<style scoped>

</style>
