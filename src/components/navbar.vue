<template>
  <div class="container">
    <h1>Instacopy</h1>
    <b-form-input
      class="searche"
      v-model="text"
      placeholder="Search"
    ></b-form-input>
  </div>
</template>

<script>
export default {
  name: "navbar",
  components: {}
};
</script>

<style scoped>
@font-face {
  font-family: Cookie;
  src: url("../assets/Cookie-Regular.ttf");
}
.searche {
  width: 5vw;
  height: 4vh;
}
.container {
  border-bottom: 1px solid gray;
  max-width: 100vw;
  display: flex;
  flex-direction: row;
  align-items: center;
}

h1 {
  font-family: Cookie;
}

* {
  font-family: Segoe UI;
}
</style>
