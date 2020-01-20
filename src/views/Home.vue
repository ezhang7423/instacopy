<template>
  <div>
    <navbar></navbar>
  </div>
</template>

<script>
import navbar from "@/components/navbar.vue";
export default {
  name: "home",
  components: { navbar }
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
