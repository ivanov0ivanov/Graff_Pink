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
        <ul class="nav-bar">
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
    </nav>
    <div class="welcome_container">
        <h2 class="welcome_title">Welcome to Pink</h2>
        <p class="welcome_description">A multi purpose theme from cssauthor.com</p>
    </div>
</div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped lang="sass">
    .header_container  //какого-то хера не работает в подключаемом файле
        width: 100%
        height: 580px
        background: url(../assets/img/png/header.png) no-repeat
        background-size: cover
        position: relative
</style>
