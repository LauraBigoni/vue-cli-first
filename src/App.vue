<template>
  <div id="app">
    <Title />
    <img alt="Vue logo" class="vue-logo" src="@/assets/logo.png" />
    <Hero />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero,
  },
};
</script>

<style>
#app {
  text-align: center;
  color: #194b4b;
}

img.vue-logo {
  width: 80px;
}
</style>