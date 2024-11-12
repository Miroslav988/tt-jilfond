<script>
import MainContent from "./components/MainContent.vue";
import MyHeader from "./components/MyHeader.vue";
export default {
  components: {
    MyHeader,
    MainContent,
  },
};
</script>

<template>
  <MyHeader />
  <MainContent />
</template>
<style lang="scss">
@font-face {
  font-family: "Monserat";
  src: url(../public/Font/Montserrat-VariableFont_wght.ttf);
}
#app {
  margin: 50px 51px 44px 47px;
  font-family: "Monserat", sans-serif;
}
</style>
