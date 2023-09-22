<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppLinks from './components/AppLinks.vue'



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

  }

}

</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppLinks></AppLinks>
  <footer></footer>
</template>

<style lang="scss"></style>