<template>
    <div class="Right">
        <app-UpBar></app-UpBar>
        <app-friends></app-friends>
    </div>

</template>

<script>
    import upBar from './UpBar/UpBar';
    import friends from './friends/Friends'

    export  default {
        components:{
            'app-UpBar':upBar,
            'app-friends':friends,
        }

    }

</script>

<style scoped>
    .Right{
        /*background-color: red;*/

    }

</style>
