<template>
    <div class="section">
        <div class="title">
            <h2>Services</h2>
            <h5>lorem</h5>
        </div>
        <div class="card">
            <Card :service="service" v-for="(service, i) in services" :key="i" /> 
        </div>
    </div>
</template>

<script>

    import Card from '~/components/card'
    import {service} from '~/assets/service'
    
    export default{
        data(){
            return{
                services: service
            }
        }
    }

</script>

<style scoped>



    .card{
        display: flex;
        justify-content: center;
    }



</style>