<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorldC0 msg="Atividade Avaliativa 2" />
  <HelloWorldC1 />
  <HelloWorldC2 />
  <HelloWorldC3 />
  <HelloWorldC4 />
</template>

<script>
import HelloWorldC0 from "./components/HelloWorld-c0.vue";
import HelloWorldC1 from "./components/HelloWorld-c1.vue";
import HelloWorldC2 from "./components/HelloWorld-c2.vue";
import HelloWorldC3 from "./components/HelloWorld-c3.vue";
import HelloWorldC4 from "./components/HelloWorld-c4.vue";

export default {
  name: "App",
  components: {
    HelloWorldC0,
    HelloWorldC1,
    HelloWorldC2,
    HelloWorldC3,
    HelloWorldC4,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2979a2;
  margin-top: 40px;
}
</style>
