<template>
    <div class="nav">
        <div class="nav_left">
            <nuxt-link to="/">SOLIXCOM</nuxt-link>
        </div>
        <div class="nav_right">
            <nuxt-link to="/">A propos</nuxt-link>
            <nuxt-link to="/">Services</nuxt-link>
            <nuxt-link to="/">Contacts</nuxt-link>
            <button id="toggle">-</button>
        </div>
    </div>
</template>

<style scoped> 
    .nav{
        display: flex;
        position: fixed;
        top: 0;
        width: 100%;
        justify-content: space-around;
        padding: 20px 0;
        background-color: transparent;
    }

    .nav_left > a{
        color: white;
    }

    .nav_right{
        display: flex;
    }

    .nav_right > a{
        margin-right: 20px;
        color: white;
    }

    #toggle{
        display: block;
        border: none;
        background-color: transparent;
        cursor: pointer;
        outline: none;
    }
</style>
