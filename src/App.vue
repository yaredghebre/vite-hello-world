<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  components: {
    AppTitle,
    AppHero,
  },
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="wrapper">
    <AppTitle />
    <AppHero />
  </div>

</template>

<style>
  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  body {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    background-color: rgba(0, 0, 0, 0.399);
  }

  .wrapper {
    height: 100vh;
    width: 80%;
    margin: 0 auto;
  }
</style>