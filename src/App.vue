<template>
  <div id="app">
    <SideBar />
    <div class="content">
      <KPIArea />
      <GraphArea />
    </div>
  </div>
</template>

<script>
import GraphArea from "./components/Layout/GraphArea.vue";
import KPIArea from "./components/Layout/KPIArea.vue";
import SideBar from "./components/Layout/SideBar.vue";

export default {
  name: "App",
  components: {
    SideBar,
    GraphArea,
    KPIArea,
  },
};
</script>

<style>
#app {
  display: flex;
  height: 100vh;
}
.content {
  flex: 1;
  display: flex;
  flex-direction: column;
  padding: 20px;
}
</style>
