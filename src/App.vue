<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppLinks from './components/AppLinks.vue';
import AppFooter from './components/AppFooter.vue';




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

  }

}

</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppLinks></AppLinks>
  <AppFooter></AppFooter>
</template>

<style lang="scss"></style>