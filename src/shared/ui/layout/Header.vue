<script setup lang="ts">
</script>

<template>
  <header class="header">
    <nav class="nav">
      <ul class="nav__items">
        <li class="nav__item">Каталог</li>
        <li class="nav__item">О нас</li>
        <li class="nav__item">Контакты</li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss">
.header {
  position: fixed;
  z-index: 1;
  top: 0;
  right: 0;
  left: 0;
  display: flex;
  height: 64px;
  width: 100%;
  background-color: #303336;
  align-items: center;
  padding: 0 calc(8px * 2.5);
  margin: 0 auto;
  transform: translate(0, 0);

  .nav {
    display: flex;
    width: 100%;
    max-width: 1680px;
    align-items: center;
    margin: 0 auto;

    &__items {
      display: flex;
    }
  }
}
</style>
