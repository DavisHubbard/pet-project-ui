<template>
  <div id="app">
    <MainPage />
  </div>
</template>

<script>
import MainPage from "@/components/MainPage";

export default {
  name: "App",
  components: {
    MainPage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
