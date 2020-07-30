<template>
    <div class="row Main">
        <section class="col-sm-1">
            <span class="fa fa-ellipsis-v"></span>
        </section>

        <section class="col-sm-1">
            <span class="fa fa-folder-open"></span>
        </section>

        <section class="col-sm-1">
            <span class="fa fa-search"></span>
        </section>
        
        <section class="col-sm-2 offset-7 row" >
            <p class="col-sm-6 text-muted">{{name}}</p>
            <img class="col-sm-5" :src="image">
        </section>

    </div>
</template>

<script>
    export default {
      computed:{
        name(){
              return this.$store.state.chatWith.name
        },
        image(){
          return this.$store.state.chatWith.image
        }

      }
    }
</script>

<style scoped>
    .Main{
        padding: 10px 0px 0px 0px;
        background-color: #ededed;
    }
    img{
        width: 30px;
        height:30px;
        border-radius: 50%;
    }
    span{
        color: #939393;
    }
</style>
