<template>
  <HeaderApp></HeaderApp>
  <HeroApp></HeroApp>
  <LineApp></LineApp>
  <PriceApp></PriceApp>

</template>

<script>
import HeaderApp from './components/HeaderApp/HeaderApp.vue';
import HeroApp from './components/HeroApp/HeroApp.vue';
import PriceApp from './components/PriceApp/PriceApp.vue';
import LineApp from './components/LineApp/LineApp.vue';

export default {
  components: {
    HeaderApp, // Здесь вы добавляете компонент
    HeroApp,
    PriceApp,
    LineApp

  }
}
</script>

<style>

</style>