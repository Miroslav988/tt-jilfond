<template>
  <aside class="sidebar">
    <form>
      <label class="searchEmploee" for="search"
        ><h3>Поиск сотрудников</h3></label
      >
      <input
        class="nameOrIdInput"
        name="search"
        type="text"
        placeholder="Введите Id или имя"
      />
    </form>
    <h3 class="sideTitle">Результаты</h3>
    <div class="resCont">
      <p class="startSearch">начните поиск</p>
      <p class="noRes">ничего не найдено</p>
      <UserCard />
    </div>
  </aside>
</template>
<script>
import UserCard from "./UserCard.vue";

export default {
  components: {
    UserCard,
  },
};
</script>
<style lang="scss">
.sidebar {
  position: relative;
  display: flex;
  flex-direction: column;
  width: 23%;
  height: 100%;
  margin: 27px 31px 0px 20px;

  &::before {
    content: "";
    position: absolute;
    background-color: #dededd;
    width: 1px;
    height: 110%;
    right: -31px;
    top: -27px;
    min-height: 589px;
  }
}
.nameOrIdInput {
  padding: 16px;
  width: 100%;
  border-radius: 8px;
  border: 2px solid #e9ecef;
  box-sizing: border-box;
}
</style>
