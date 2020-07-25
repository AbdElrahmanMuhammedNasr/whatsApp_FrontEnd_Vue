<template>
    <div>
        <app-Bar></app-Bar>
        <app-Chat></app-Chat>
        <app-Send></app-Send>
    </div>
</template>
<script>
    import Bar from './TakeToBar/TakeToBar';
    import Chat from './Chat/Chat';
    import Send from './SendBar/SendBar';
    export default {
        components:{
            'app-Bar':Bar,
            'app-Chat':Chat,
            'app-Send':Send
        }
    }
</script>
