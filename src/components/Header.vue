<template>
<div class="header_container">
    <nav class="nav_container">
        <div class="label_container">
            <h2 class="label">
                <span>Graff </span>
                <span>pink</span>
            </h2>
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
</div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>

</style>
