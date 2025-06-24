<template>
  <div id="app">Hello World</div>
  <KPIArea />
  <GraphArea />
</template>

<script>
import GraphArea from "./components/Layout/GraphArea.vue";
import KPIArea from "./components/Layout/KPIArea.vue";
export default {
  name: "App",
  components: {
    GraphArea,
    KPIArea,
  },
};
</script>
