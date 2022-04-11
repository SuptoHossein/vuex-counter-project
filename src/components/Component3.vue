<template>
  <div>
    <component-4 />

    <history />
  </div>
</template>

<script>
import Component4 from "./Component4.vue";
import History from "./History.vue";

export default {
  name: "component-3",
  components: {
    Component4,
    History,
  },
};
</script>

<style>
</style>