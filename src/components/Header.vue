<template>
    <div class="header_container">
        <nav class="nav_container">
            <div class="label_container">
                <router-link to="/">
                    <h2 class="label">
                        <span>Graff </span>
                        <span>pink</span>
                    </h2>
                </router-link>
            </div>
            <button type="button" id="menuToggle" class="burger-menu" @click="menuActive = !menuActive">
                <input id="burgerInput" type="checkbox"/>
                <span class="burger-line one"></span>
                <span class="burger-line two"></span>
                <span class="burger-line three"></span>
            </button>

            <transition  name="bounce"
                         enter-active-class="bounceInLeft"
                         leave-active-class="bounceOutRight">

                <ul v-if="menuActive" class="nav-bar">
                    <li class="nav-item">
                        <router-link to="#" class="nav-link">Home</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="#" class="nav-link">About Us</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="#" class="nav-link">Services</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="#" class="nav-link">Contact</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="#" class="nav-link login-link">
                            <font-awesome-icon icon="user"/>
                            Login
                        </router-link>
                    </li>
                </ul>
            </transition>
        </nav>
        <div class="welcome_container">
            <h2 class="welcome_title">Welcome to Pink</h2>
            <p class="welcome_description">A multi purpose theme from cssauthor.com</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Header",
        data() {
            return {
                menuActive: false
            }
        }
    }
</script>

<style lang="sass"> // Мы тут пишем крестик для бургера
.burger-menu
    width: 50px
    display: none
    flex-direction: column
    align-self: center
    background-color: transparent

    .burger-line
        &:last-child
            margin: 0 !important

#menuToggle
    overflow: hidden
    width: 60px
    height: 100%
    display: flex
    flex-direction: column
    justify-content: center
    align-items: center

#menuToggle
    #burgerInput
        display: flex
        width: 60px
        height: 60px
        position: absolute
        cursor: pointer
        opacity: 0
        z-index: 1

#menuToggle
    span
        width: 55px
        height: 8px
        margin-bottom: 10px
        background: #8C8D8D
        border-radius: 4px
        -webkit-transition: all .5s cubic-bezier(.08, .81, .87, .71)
        -moz-transition: all .5s cubic-bezier(.08, .81, .87, .71)
        -ms-transition: all .5s cubic-bezier(.08, .81, .87, .71)
        -o-transition: all .5s cubic-bezier(.08, .81, .87, .71)
        transition: all .5s cubic-bezier(.08, .81, .87, .71)

.one
    transform-origin: 4px 0

.three
    transform-origin: bottom right

#menuToggle
    #burgerInput:checked ~ .one
        background-color: #b73958
        transform: rotate(45deg) translate(8px)

#menuToggle
    #burgerInput:checked ~ .two
        background-color: #b73958
        transform: rotate(495deg) translate(4px)

#menuToggle
    #burgerInput:checked ~ .three
        background-color: #b73958
        transform: rotate(45deg)
        opacity: 0
</style>

<style scoped lang="sass">
    //какого-то хера не работает в подключаемом файле
    .header_container
        width: 100%
        height: 580px
        background: url(../assets/img/png/header.png) no-repeat
        background-size: cover
        position: relative
</style>
