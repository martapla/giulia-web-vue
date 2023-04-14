<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <header>
        <Home />
        <nav class="container">
            <ul class="nav-routes">
                <RouterLink to="/">WELCOME</RouterLink>
                <RouterLink to="/about">ABOUT</RouterLink>
                <RouterLink to="/work">WORK</RouterLink>
                <RouterLink to="/contact">CONTACT</RouterLink>
            </ul>
        </nav>
    </header>
</template>

<style scoped>

.nav-routes {
    display:flex;
    flex-direction: row;
    justify-content: center;
    gap:80px;
    margin-top: 60px;
    margin-right: 40px;
    
}
.nav-routes a {
    display:inline;
    display:flex;
    flex-direction: row;
    justify-content: center;
    color:rgb(218, 119, 206);
    list-style: none;
    text-decoration: none;
    font-size: 18px;
    cursor:pointer;
    border:1px rgb(234, 82, 184) solid;
    box-shadow: 7px 3px 1px ;
    padding: 10px;
}
.nav-routes a:hover {
    color:rgb(158, 212, 31);
    border:1px solid rgb(158, 212, 31);
}


</style>