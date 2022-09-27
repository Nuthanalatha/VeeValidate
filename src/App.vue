<template>
  <vee-validate />
</template>

<script>
import VeeValidate from "./Vee-Validate.vue";

export default {
  name: "App",
  components: {
    VeeValidate,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
  background-color: greenyellow;
}
</style>
