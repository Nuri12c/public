<template>
  <section class="hero">
    <div class="hero__heading">
      <h2 class="stalinist-one-regular">Танцуешь?</h2>
      <h1 class="stalinist-one-regular">Танцуй с Россией!</h1>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Stalinist+One&display=swap');

.stalinist-one-regular {
  font-family: "Stalinist One", sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 3rem;
  color: rgba(255, 255, 255, 0.865);
  position: relative; /* Позволяет позиционировать псевдоэлемент относительно текста */
}

.hero {
  width: 100%;
  height: 800px;
  background: url(https://i.gifer.com/7hoG.gif);
  background-size: cover;
  background-repeat: no-repeat;
  background-position-y: center;
  text-align: center;
  padding-top: 80px;
}


</style>
