<template>
    <div class="footer_container">
        <div class="sub-menu_container">
            <div class="sub-menu">
                <h4 class="title">Sub Menu</h4>
                <ul class="sub-menu_items">
                    <li class="sub-menu_item">
                        <router-link to="#">Android</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Apps</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Articles</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Backgrounds</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Blogger</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Books</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Coding</router-link>
                    </li>
                </ul>
            </div>
            <div class="sub-menu">
                <h4 class="title">Sub Menu</h4>
                <ul class="sub-menu_items">
                    <li class="sub-menu_item">
                        <router-link to="#">Freebies</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Greetings</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Icons</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Illustrator</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Inspiration</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">iPad</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">iPhone</router-link>
                    </li>
                </ul>
            </div>
            <div class="sub-menu">
                <h4 class="title">Sub Menu</h4>
                <ul class="sub-menu_items">
                    <li class="sub-menu_item">
                        <router-link to="#">Drupal</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Fonts</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Freebies</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Greetings</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Icons</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Illustrator</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Inspiration</router-link>
                    </li>
                </ul>
            </div>
            <div class="sub-menu">
                <h4 class="title">Sub Menu</h4>
                <ul class="sub-menu_items">
                    <li class="sub-menu_item">
                        <router-link to="#">JQuery</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Magento</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Mobile</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Photoshop</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Plugins</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Resource</router-link>
                    </li>
                    <li class="sub-menu_item">
                        <router-link to="#">Templates</router-link>
                    </li>
                </ul>
            </div>
        </div>
        <div class="social_container">
            <address class="social-link_container">
                <router-link to="#" class="facebook-link social-link">
                    <img src="../assets/img/svg/facebook-f-brands.svg" alt="facebook">
                </router-link>
                <router-link to="#" class="tweeter-link social-link">
                    <img src="../assets/img/svg/twitter-brands.svg" alt="tweeter">
                </router-link>
                <router-link to="#" class="dribble-link social-link">
                    <img src="../assets/img/svg/dribbble-brands.svg" alt="dribble">
                </router-link>
                <router-link to="#" class="share-link social-link">
                    <img src="../assets/img/svg/share-alt-solid.svg" alt="share">
                </router-link>
            </address>
            <small class="copyright">Copyright © 2009–2019 example.com</small>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style lang="sass">
    .footer_container
        width: 100%
        min-height: 258px
        background: url(../assets/img/png/bg_footer.png)
</style>
