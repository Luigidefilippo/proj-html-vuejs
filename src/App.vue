<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppMain,
    AppHeader,
    AppFooter,
  }
}

</script>

<template>

  <AppHeader/>
  <AppMain/>
  <AppFooter/>
  
</template>

<style lang="scss">
@use './components/style/main.scss';
</style>
