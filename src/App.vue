<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppLinks from './components/AppLinks.vue';
import AppFooter from './components/AppFooter.vue';
import AppCTA from './components/AppCta.vue';





export default {

  name: 'App',
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppMain,
    AppLinks,
    AppFooter,
    AppCTA,

  }

}

</script>

<template>
  <AppHeader></AppHeader>
  <div class="jumbo">

  </div>
  <AppMain></AppMain>
  <AppLinks></AppLinks>
  <AppFooter></AppFooter>
  <AppCTA></AppCTA>
</template>

<style lang="scss">
@use './assets/scss/partials/variables.scss' as *;

.jumbo {
  background-image: url('../src/assets/img/jumbotron.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  height: 23rem;
}
</style>