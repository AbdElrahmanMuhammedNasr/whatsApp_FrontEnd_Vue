<template>
    <div class="Main" style="overflow: hidden">
        <div class="row"  style=" ; overflow: hidden;padding: 10px 20px">

            <section class="col-sm-11 row" >
                <section class="col-sm-1">
                    <span class="fa fa-ellipsis-v"></span>
                </section>

                <section class="col-sm-1">
                    <span class="fa fa-comments"></span>
                </section>

                <section class="col-sm-1">
                    <span class="fa fa-circle-o-notch"></span>
                </section>

            </section>


            <section class="col-sm-1" >
                <img src="../../../assets/abdo.jpg">
            </section>
        </div>

        <input class="form-control" style="background-color: white" placeholder="Search">

    </div>

</template>

<script>
    export default {

    }
</script>

<style scoped>
    .Main{
        background-color: #ededed;
    }
    img{
        width: 30px;
        height: 30px;
        border-radius: 50%;
    }
    span{
        color: #939393;
    }

</style>
