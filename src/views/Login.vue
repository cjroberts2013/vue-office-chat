<template>
  <div class="login">
    <b-jumbotron
      header="Vue Chat Room"
      lead="Powered by Chatkit SDK and Bootstrap-Vue"
      bg-variant="success"
      text-variant="white"
    >
      <p>For more information visit website</p>
      <b-btn variant="light" target="_blank" href="https://pusher.com/chatkit">More Info</b-btn>
    </b-jumbotron>
    <b-container>
      <b-row>
        <b-col lg="4" md="3"></b-col>
        <b-col lg="4" md="6">
          <LoginForm />
        </b-col>
        <b-col lg="4" md="3"></b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import LoginForm from "@/components/LoginForm.vue";

export default {
  name: "login",
  components: {
    LoginForm
  }
};
</script>
