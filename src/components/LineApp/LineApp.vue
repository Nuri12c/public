<template>
  <section class="line">
    <div class="line__container">
      <ul class="line__first-list">
        <li class="line__item">Картинка 1</li>
        <li class="line__item">Картинка 1</li>
        <li class="line__item">Картинка 1</li>
        <li class="line__item">Картинка 1</li>
      </ul>
      <ul class="line__second-list">
        <li class="line__item">Блок 5</li>
        <li class="line__item">Блок 6</li>
        <li class="line__item">Блок 7</li>
        <li class="line__item">Блок 8</li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>

.line {
  padding-top: 100px;
  background-color: #000000;
}
.line__container {
  width: 100%;
  height: 500px;

  display: flex;
  overflow-x: hidden;
  position: relative;
}

.line__first-list, .line__second-list {
  display: flex;
  width: 200%;
  height: 200px;
  justify-content: space-around;
  position: absolute;
  top: 0;
  left: 0;
  animation-duration: 20s;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}
.line__first-list {
  animation-name: marquee1;
}
.line__second-list {
  animation-name: marquee2;
}
.line__item {
  width: 160px;
  height: 100px;
  background: radial-gradient(circle at 50% 100%, #2d3457, #000000);
  border-radius: 15px;
}
@keyframes marquee1 {
  0% {
    transform: translateX(0%);
  }
  100% {
    transform: translateX(-100%);
  }
}

@keyframes marquee2 {
  0% {
    transform: translateX(100%);
  }
  100% {
    transform: translateX(0%);
  }
}
</style>