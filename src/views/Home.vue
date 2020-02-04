<template>
  <div>
    <navbar></navbar>
    <mprofile></mprofile>
  </div>
</template>

<script>
import navbar from "@/components/navbar.vue";
import mprofile from "@/components/miniprofile.vue";
export default {
  name: "home",
  components: { navbar, mprofile }
};
</script>

<style scoped>
@font-face {
  font-family: Cookie;
  src: url("../assets/Cookie-Regular.ttf");
}

* {
  font-family: Cookie;
}
</style>
