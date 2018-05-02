<template>
  <div id="app" data-spy="scroll">
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
}
</style>
