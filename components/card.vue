<template>
    <div class="card-item">
        <div class="header">
            <div class="logo"><img :src="service.logo" alt="service.slug"></div>
            <h4>{{service.slug}}</h4>
        </div>
        <div class="content">
            <ul v-for="item in service.item" :key="item">
                <li v-html="item"></li>
            </ul>
        </div>
    </div>
</template> 


<script>
    export default{
        props: ['service']
    }
</script>

<style scoped>
    .logo > img{
        width: 50px;
        border-radius: 50%;
        box-shadow: 1px 1px 3px black;
    }

    .card-item{
        margin: 0 30px;
        min-width: 230px;
        max-width: 230px;
        padding: 20px 5px; 
        border-bottom: 5px solid red;
    }

    .header{
        margin-bottom: 20px;
        color: black;
    }

    .content > ul > li{
        padding: 10px 0;
        border-bottom: 1px solid rgb(194, 194, 194);
        color: gray;
    }


</style>
