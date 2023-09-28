<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppLinks from './components/AppLinks.vue';
import AppFooter from './components/AppFooter.vue';
import AppCTA from './components/AppCta.vue';
import AppJumbo from './components/AppJumbo.vue';





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
    AppJumbo
  }

}

</script>

<template>
  <AppHeader></AppHeader>
  <AppJumbo></AppJumbo>
  <AppMain></AppMain>
  <AppLinks></AppLinks>
  <AppFooter></AppFooter>
  <AppCTA></AppCTA>
</template>

<style lang="scss">
@use './assets/scss/partials/variables.scss' as *;
</style>