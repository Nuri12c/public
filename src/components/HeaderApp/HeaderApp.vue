<template>
<section class="header">
    <div class="container header__container">
      <div class="nav">
        <div class="logo-circle">
          <div class="logo"></div>
        </div>
        <ul class="nav__list">
          <li class="nav__item">О конкурсах </li>
          <li class="nav__item">Отзывы</li>
          <li class="nav__item">Программа</li>
          <li class="nav__item">Жюри</li>
          <li class="nav__item">Вопросы</li>
          <li class="nav__item">Лагерь</li>
        </ul>
        <div class="nav__buttons">
          <div class="inst"></div>
          <div class="vk"></div>
          <div class="tg"></div>
          <div class="zavka">Войти</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>

.header {
  width: 100%;
  height: 100px;
  position: fixed;
}
.header__container {
  width: 100%;
  height: 100px;
}
.nav {
  display: flex;
  justify-content: space-between;
  margin: 20px auto;
  width: 70%;
  height: 8vh;
  border-radius: 35px;
  border: 1px solid rgb(183, 183, 183);
  background-color: rgba(223, 230, 232, 0.582); /* Полупрозрачный фон */
  backdrop-filter: blur(3px); /* Эффект размытия фона */
  padding: 5px 10px 5px 10px; /* Отступы внутри блока */
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2); /* Тень для блока */
}
.nav__list {
  display: flex;
  align-items: center;
  height: 100%;
}
.nav__item {
  margin-right: 15px;
}
.logo-circle {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  transform: translate(0, -2px);
}
.logo {
  width: 9vw;
  height: 9vh;
  background: url(./photo.png);
  background-size: contain;
  background-repeat: no-repeat;
}
.nav__buttons {
  display: flex;
  align-items: center;
}
.inst {
  width: 40px;
  height: 40px;
  background-color: #000000;
  border-radius: 50%;
}
.tg {
  width: 40px;
  height: 40px;
  background-color: #000000;
  border-radius: 50%;
}
.vk {
  width: 40px;
  height: 40px;
  background-color: #000000;
  border-radius: 50%;
}
.zavka {
  padding: 10px;
  background-color: #151010;
  color: wheat;
  border-radius: 35px;
}
</style>