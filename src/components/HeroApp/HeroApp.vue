<template>
  <section class="hero">
    <div class="hero__heading">
      <h2 class="stalinist-one-regular1">Танцуешь?</h2>
      <h1 class="stalinist-one-regular2 ">Танцуй с Россией!</h1>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Stalinist+One&display=swap');
.hero__heading {
  padding-top: 10px;
}
.stalinist-one-regular1 {
  font-family: "Stalinist One", sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 1.5rem;
  color: rgba(255, 255, 255, 0.865);
  position: relative; /* Позволяет позиционировать псевдоэлемент относительно текста */
  

}
.stalinist-one-regular2 {
  font-family: "Stalinist One", sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 2.5rem;
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
