<template>
    <header>
        <img alt="Vue logo" class="logo" src="../assets/logo.svg" width="70" height="70" />
        <ul class="menu">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </header>
</template>

<style scoped>
    header {
        background-color: bisque;
        display: flex;
        place-items: center;
        place-content: space-between;
        min-height: 80px;
    }
    .menu {
        margin: 0;
        padding: 0;
    }
    .menu li{
        display: inline-block;
    }
    .menu li a {
        padding: 5px 10px;
        text-transform: uppercase;
    }
</style>