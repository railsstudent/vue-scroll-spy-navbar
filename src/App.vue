<template>
  <div id="app">
    <ScrollSpy />
  </div>
</template>

<script>
import ScrollSpy from "./components/ScrollSpy.vue";

export default {
  name: "app",
  components: {
    ScrollSpy
  }
};
</script>

<style>
body {
  padding-top: 3.25rem;
  //height: 120vh;
  bottom: -20px;
}
</style>
