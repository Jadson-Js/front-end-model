<template>
  <AppHeader />

  <AppMain />

  <router-view name="footer"></router-view>
</template>

<script>
  import AppHeader from "./components/Header/AppHeader.vue";
  import AppMain from "./components/Main/AppMain.vue"
  export default {

    name: 'App',
    components: {
      AppHeader,
      AppMain
    }
  }
</script>

<style>
</style>