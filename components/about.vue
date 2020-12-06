<template>
    <div class="section">
        <div class="title">
            <h2>A propos de nous</h2>
            <h5>Lorem</h5>
        </div>
        <div class="content_section">
            <div class="content_left">
                <img src="../static/solixcomlogo.png" alt="">
            </div>
            <div class="content_right">
                <p>Solixom est une entreprise vendéene crée en 2020....</p>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .content_section{
        display: flex;
        justify-content: center;
        margin-top: 200px;
    }

    .content_left > img{
        transform: rotate(-20deg);
        border-bottom: 2px solid black;
        width: 400px;
        max-width: 100%;
        box-shadow: 0 0 10px black;
        margin-right: 100px;
    }

    .content_right{
        width: 300px;
        text-align: left;
    }

</style>

