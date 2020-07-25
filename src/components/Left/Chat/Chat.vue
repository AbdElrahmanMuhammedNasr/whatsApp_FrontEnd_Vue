<template>
        <div class="Main">
                     <div class="row">
                             <section class="owner col-sm-12">
                                     <p  style="padding: 20px; background-color: #addc80">hi my name is abdo . <span class="text-muted">2:30 AM </span></p>
                             </section>

                             <section class="friend col-sm-12">
                                     <p   style="padding: 20px ; background-color: white" >hi abdo . <span class="text-muted">2:30 AM </span></p>
                             </section>

                             <section class="owner col-sm-12">
                                     <p  style="padding: 20px; background-color: #addc80">what is your name . <span class="text-muted">2:30 AM </span></p>
                             </section>

                             <section class="friend col-sm-12">
                                     <p   style="padding: 20px ; background-color: white" >Nasr  . <span class="text-muted">2:30 AM </span></p>
                             </section>
                     </div>

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
        min-height: 74vh;
        width: 100%;
        border: none;
        color: white;
        background-image: url("../../../assets/7.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
        padding: 20px;
    }
    .Main .owner{ border-radius: 10px;  color: black;  width: 100%; }
    .Main .owner p{float: left; border-radius: 20px}
    .Main .friend{ border-radius: 10px;color: black;width: 100%;}
    .Main .friend p{float: right;border-radius: 20px}


</style>
