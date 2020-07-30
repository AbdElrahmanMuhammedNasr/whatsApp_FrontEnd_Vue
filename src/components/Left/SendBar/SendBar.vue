<template>
   <div class="row Main">
<!--       <span class="fa fa-volume-up	 col-sm-1" style="font-size: 35px; color: grey"> </span>-->
       <input class="form-control col-sm-10 offset-1" placeholder="Message" v-model="message">
     <button class="btn btn-primary">Send</button>
<!--       <span class="fa fa-smile-o	col-sm-1" style="font-size: 35px; color: grey " ></span>-->

   </div>
</template>

<script>
    export default {
        data:function () {
            return{
                message:''
            }
      }
    }
</script>

<style scoped>
    .Main{
        /*background-color: ;*/
    }

</style>
