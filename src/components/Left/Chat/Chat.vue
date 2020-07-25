<template>
        <div class="Main">
            <textarea class="form-control"  readonly></textarea>
        </div>
</template>

<script>
    export default {
        name: "Chat"
    }
</script>

<style scoped>
    .Main{
        height: 75vh;
        margin-top: 10px;
        margin-bottom: 20px;
    }
    textarea{
        min-height: 74vh;
        width: 100%;
        border: none;
        color: white;
        background-image: url("../../../assets/abdo.jpg");
        background-repeat: no-repeat;
        background-size: 100%;
    }


</style>
