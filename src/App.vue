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
      items: [
        {
          name: 'Characters'
        },
        {
          name: 'Comics'
        },
        {
          name: 'Movies'
        },
        {
          name: 'TV'
        },
        {
          name: 'Games'
        },
        {
          name: 'Collectibles'
        },
        {
          name: 'Videos'
        },
        {
          name: 'Fans'
        },
        {
          name: 'News'
        },
        {
          name: 'Shop'
        },
      ]
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
  <AppMain></AppMain>
  <AppLinks></AppLinks>
  <AppFooter></AppFooter>
  <AppCTA></AppCTA>
</template>

<style lang="scss"></style>