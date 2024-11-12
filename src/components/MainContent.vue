<template>
  <div class="mainContent">
    <Sidebar />
  </div>
</template>
<script>
import Sidebar from "./Sidebar.vue";

export default {
  components: {
    Sidebar,
  },
};
</script>
<style lang="scss">
.mainContent {
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 100%;
  min-height: 589px;
  background-color: #fdfdfd;
  box-shadow: 0px 0px 10px 0px #0000001a;
  border-radius: 10px;
}
</style>
