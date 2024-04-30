<script>
import AppTitle from "./components/AppTitle.vue";

export default {
  components: { AppTitle },

  data() {
    return {
      greetings: "Hello world!"
    };
  }
}
</script>

<template>
  <h1> {{ greetings }} </h1>
  <AppTitle />
</template>

<style></style>