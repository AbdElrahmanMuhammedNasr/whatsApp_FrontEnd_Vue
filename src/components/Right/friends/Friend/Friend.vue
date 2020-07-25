<template>
    <div class="row Friend" >
        <section class="col-lg-4 col-md-4 col-sm-1">
            <p class="text-muted">{{fri.time}}</p>
        </section>

        <section class="col-lg-2 col-md-2 col-sm-1">
            <p class="text-muted">{{fri.last}}</p>
        </section>

        <section class="col-lg-4 col-md-4 col-sm-1" >
            <p>{{fri.name}}</p>
        </section>



        <section class="col-lg-2 col-md-2 col-sm-1">
<!--            <img :src="fri.image">-->
            <img src="../../../../assets/badawy.jpg">
        </section>

        <hr>

    </div>

</template>

<script>
    export default {
        props:['fri']
    }
</script>

<style scoped>

    img{
        width: 30px;
        height: 30px;
        border-radius: 50%;
    }
    .Friend{

        background-color: white;
        padding: 20px 10px;
    }

</style>
