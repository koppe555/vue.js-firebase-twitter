<!-- Header.vue -->
<template>
  <header>
    <router-link to="/">
      <h1>whisp.</h1>
    </router-link>
    <fa icon="user"/>
  </header>
</template>

<style lang="stylus" scoped>
header {
  position: fixed;
  top: 0;
  width: 100%;
  text-align: center;
  padding: 10px;

  h1 {
    width: fit-content;
    margin: 0 auto;
    font-size: 1.4rem;
  }

  .btns {
    position: absolute;
    top: 10px;
    right: 30px;
    cursor: pointer;

    img {
      width: 100%;
    }
  }
}
</style>