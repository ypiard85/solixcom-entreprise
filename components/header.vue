<template>
    <div class="header">
        <div class="header_left">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptas animi magni asperiores neque deleniti eveniet officiis repellat eaque illo nesciunt sapiente exercitationem cum, cumque ad voluptatem veniam blanditiis magnam omnis.</p>
        </div>
        <div class="header_right">
            <img src="https://cdn.pixabay.com/photo/2019/10/09/07/28/development-4536630_960_720.png" alt="">
        </div>
    </div>
</template>
  
  
<style scoped>
    .header{
        height: 100vh;
        background-image: url('../static/bg-site.png');
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 20px;
    }

    .header_left{
        width: 500px;
    }

    .header_right > img{
        width: 600px;
        max-width: 100%;
    }


</style>
  