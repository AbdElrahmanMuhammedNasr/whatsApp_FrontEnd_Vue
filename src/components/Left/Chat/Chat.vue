<template>
  <div class="Main">
    <div class="row" v-for="message in messages" :key="message.id">


      <section class="owner col-sm-12" v-if="message.owner">
        <p style="padding: 20px; background-color: #addc80" >
          {{message.msg}}.
          <span class="text-muted">{{message.time}} AM</span>
        </p>
      </section>

      <section class="friend col-sm-12" v-if="!message.owner">
        <p style="padding: 20px ; background-color: white" >
          {{message.msg}}.
          <span class="text-muted">{{message.time}} AM</span>
        </p>
      </section>



     

    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {

        messages: [
                {"id":"1", "owner":true, "msg":'Hi iam Abdo',"time":'2:30'},
                {"id":"2", "owner":true, "msg":'and u?',"time":'2:32'},
                {"id":"3", "owner":false, "msg":'Tamer',"time":'3:30'},
                {"id":"4", "owner":true, "msg":'Nice',"time":'2:31'},
                {"id":"5", "owner":false, "msg":'u 2',"time":'2:33'},
    ] };
  },
};
</script>

<style scoped>
.Main {
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
.Main .owner {
  border-radius: 10px;
  color: black;
  width: 100%;
}
.Main .owner p {
  float: left;
  border-radius: 20px;
}
.Main .friend {
  border-radius: 10px;
  color: black;
  width: 100%;
}
.Main .friend p {
  float: right;
  border-radius: 20px;
}
</style>
