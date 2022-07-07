<!--<template>
  <decision></decision>
</template>

<script>
import decision from "./components/decision.vue";
export default {
  name: "App",
  components: {
    decision: decision,
  },
};
</script>

<style>
</style>
-->
<template>
  <headpage></headpage>
  <comppage></comppage>
  <footpage></footpage>
</template>

<script>
import headpage from "./components/headpage.vue";
import comppage from "./components/comppage.vue";
import footpage from "./components/footpage.vue";
export default {
  name: "App",
  components: {
    headpage: headpage,
    comppage: comppage,
    footpage: footpage,
  },
};
</script>

<style>
</style>
