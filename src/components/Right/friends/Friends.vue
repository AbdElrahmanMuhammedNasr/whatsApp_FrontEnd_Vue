<template>
    <div class="Friends">
        <app-friend v-for="friend in Friends" :fri = friend :key="friend.id"></app-friend>
    </div>
</template>

<script>
    import friend from './Friend/Friend'
    export default {
        data:function () {
            return {
                Friends : [
                    {id:1,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'Badawy', last:'ok',time:'12 PM'},
                    {id:2,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:3,image:'https://www.nretnil.com/avatar/LawrenceEzekielAmos.png', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:4,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:5,image:'https://www.nretnil.com/avatar/LawrenceEzekielAmos.png', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:6,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:7,image:'https://www.nretnil.com/avatar/LawrenceEzekielAmos.png', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:8,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:9,image:'https://www.nretnil.com/avatar/LawrenceEzekielAmos.png', name:'Badawy', last:'ok',time:'12 PM'},
                    {id:21,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:31,image:'https://www.nretnil.com/avatar/LawrenceEzekielAmos.png', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:41,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:51,image:'https://www.nretnil.com/avatar/LawrenceEzekielAmos.png', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:61,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:71,image:'https://www.nretnil.com/avatar/LawrenceEzekielAmos.png', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:81,image:'https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50.jpg', name:'hassan', last:'bye',time:'11:30 AM'},

                ]
            }
        },
        components: {
            'app-friend': friend,
        }
    }
</script>

<style scoped>
    .Friends{
        height: 100%;
        overflow: hidden;
        overflow-y: scroll;
    }
    ::-webkit-scrollbar{
        display: none;
    }

</style>
