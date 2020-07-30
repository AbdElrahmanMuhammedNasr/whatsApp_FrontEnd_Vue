<template >
    <div id="app" class="row  main" >

            <section class="col-sm-9 ">
                <app-LeftBar></app-LeftBar>
            </section>
            <section class="col-sm-3 .d-none .d-sm-block">
                <app-RightBar></app-RightBar>
            </section>
    </div>

</template>

<script>
    import rightBar from './components/Right/RightBar';
    import leftBar from './components/Left/LeftBar';
    export default {
        components:{
            'app-RightBar':rightBar,
            'app-LeftBar':leftBar,
        }

    }
</script>

<style scoped>
    .main{
        width: 80vw;
        margin: 5vh auto ;
        background-color: whitesmoke;
        /*background-color: blue;*/
        height: 90vh;
        overflow: hidden;
    }

</style>
