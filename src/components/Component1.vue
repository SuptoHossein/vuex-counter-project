<template>
  <div>
    <component-2 />
  </div>
</template>

<script>
import Component2 from "./Component2.vue";

export default {
  name: "component-1",
  components: {
    Component2,
  },
};
</script>

<style>
</style>