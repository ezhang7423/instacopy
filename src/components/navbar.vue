<template>
  <div class="container">
    <div class="left">
      <img class="logo" src="@/assets/ico.svg" />
      <h1 class="name">Instacopy</h1>
    </div>
    <div class="middle">
      <b-form-input
        class="searche"
        v-model="text"
        placeholder="Search"
      ></b-form-input>
    </div>
    <div class="right">
      <b-button variant="primary" class="login">Log In</b-button>
      <b-link style="margin: 1vh 0 0 1vw">Sign Up</b-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "navbar",
  components: {},
  data() {
    return {
      text: ""
    };
  }
};
</script>

<style scoped>
.container {
  border-bottom: 1px solid gray;
  max-width: 100vw;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  padding: 2vh 0;
}

.right {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-right: 20vw;
}
.left {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-left: 20vw;
}
.login {
  background-color: #3897f0;
  line-height: 0.7;
  margin-top: 1vh;
  padding-bottom: 10px;
  border: 1px solid transparent;
  font-weight: 500;
}
.logo {
  height: 5vh;
}
@font-face {
  font-family: Cookie;
  src: url("../assets/Cookie-Regular.ttf");
}
.searche {
  width: 15vw;
  text-align: center;
  align-items: center;
  justify-content: center;
  height: 4vh;
  margin-top: 1vh;
}

* {
  font-family: Segoe UI;
  font-size: 14px;
  font-weight: 500;
}
h1 {
  font-size: 2.5rem;
  font-family: Cookie;
  margin: 1vh 0 0 0;
}
</style>
