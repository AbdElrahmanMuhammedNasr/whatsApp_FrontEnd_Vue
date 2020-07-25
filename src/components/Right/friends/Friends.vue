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
                    {id:1,image:'../../../../assets/badawy.jpg', name:'Badawy', last:'ok',time:'12 PM'},
                    {id:2,image:'../../../../assets/hassan.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:3,image:'../../../../assets/badawy.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:4,image:'../../../../assets/hassan.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:5,image:'../../../../assets/badawy.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:6,image:'../../../../assets/hassan.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:7,image:'../../../../assets/badawy.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    {id:8,image:'../../../../assets/hassan.jpg', name:'hassan', last:'bye',time:'11:30 AM'},

                    // {id:9,image:'../../../../assets/badawy.jpg', name:'Badawy', last:'ok',time:'12 PM'},
                    // {id:21,image:'../../../../assets/hassan.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    // {id:31,image:'../../../../assets/badawy.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    // {id:41,image:'../../../../assets/hassan.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    // {id:51,image:'../../../../assets/badawy.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    // {id:61,image:'../../../../assets/hassan.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    // {id:71,image:'../../../../assets/badawy.jpg', name:'hassan', last:'bye',time:'11:30 AM'},
                    // {id:81,image:'../../../../assets/hassan.jpg', name:'hassan', last:'bye',time:'11:30 AM'},

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
        overflow: hidden;
        overflow-y: scroll;
    }
    ::-webkit-scrollbar{
        display: none;
    }

</style>
