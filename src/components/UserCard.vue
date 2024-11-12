<template>
  <div class="resExample">
    <div class="userPhoto"></div>
    <div class="userInfo">
      <p class="userName">Bret Ebany</p>
      <p class="userMail">siskatryas@mail.228</p>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.resExample {
  display: flex;
  border-radius: 10px;
  box-shadow: 0px 0px 10px 0px #0000001a;
}
.userPhoto {
  width: 70px;
  height: 70px;
  border-right: 1px solid #e0e0e0;
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
}
.userInfo {
  display: flex;
  flex-direction: column;
  gap: 5px;
  justify-content: center;
  align-items: left;
  padding-left: 15px;
}
.userName,
.userMail {
  margin: 0;
}
</style>
