<template>
  <div class="home">
    <SigninUp />
  </div>
</template>

<script>
// @ is an alias to /src
import SigninUp from "@/components/signin-up.vue";

export default {
  name: "HomeView",
  components: {
   
    SigninUp
},
};
</script>
