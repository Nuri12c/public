<template>
  <HeaderApp></HeaderApp>
  <HeroApp></HeroApp>
</template>

<script>
import HeaderApp from './components/HeaderApp/HeaderApp.vue';
import HeroApp from './components/HeroApp/HeroApp.vue';

export default {
  components: {
    HeaderApp, // Здесь вы добавляете компонент
    HeroApp
  }
}
</script>

<style>

</style>