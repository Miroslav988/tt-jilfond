<template>
  <header class="header">
    <h1 class="logo">Жилфонд</h1>
    <span class="user">Пользователь</span>
  </header>
</template>
<script>
export default {};
</script>

<style lang="scss">
.header {
  display: flex;
  width: 100%;
  justify-content: space-between;
  align-items: center;
}
.logo {
  color: #e31f24;
  font-size: 32px;
  font-weight: 700;
  line-height: 39px;
  margin-left: 3px;
  margin-bottom: 26px;
}
.user {
  font-size: 16px;
  font-weight: 400;
  line-height: 19px;
  margin-right: -1px;
}
</style>
