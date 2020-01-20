<template>
  <div id="app">
    <h1>instacopy</h1>
    <home></home>
  </div>
</template>

<script>
import home from "./components/home.vue";

export default {
  name: "app",
  components: {
    home
  }
};
</script>

<style>
@font-face {
  font-family: Cookie;
  src: url(assets/Cookie-Regular.ttf);
}

* {
  font-family: Cookie;
}
</style>
