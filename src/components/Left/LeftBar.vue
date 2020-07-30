<template>
    <div v-if="name.length > 0">
        <app-Bar class=".d-none .d-sm-block"></app-Bar>
        <app-Chat></app-Chat>
        <app-Send></app-Send>
    </div>
</template>
<script>
    import Bar from './TakeToBar/TakeToBar';
    import Chat from './Chat/Chat';
    import Send from './SendBar/SendBar';
    export default {
      computed:{
        name(){
          return this.$store.state.chatWith.name
        },

      },
        components:{
            'app-Bar':Bar,
            'app-Chat':Chat,
            'app-Send':Send
        }
    }
</script>
