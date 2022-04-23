<template>
  <section class="l-home d-flex justify-content-around">
    <div>
      <AppMainHomeSaveTitle />
      <AppMainHomeSaveList />
    </div>

    <div>
      <AppMainHomeSaveDevTitle />
      <AppMainHomeSaveDevList />
    </div>
  </section>
</template>

<script>
  import AppMainHomeSaveTitle from './AppMainHomeSaveTitle.vue'
  import AppMainHomeSaveList from './AppMainHomeSaveList.vue'

  import AppMainHomeSaveDevTitle from './AppMainHomeSaveDevTitle.vue'
  import AppMainHomeSaveDevList from './AppMainHomeSaveDevList.vue'

  export default {
    components: {
      AppMainHomeSaveTitle,
      AppMainHomeSaveList,
      AppMainHomeSaveDevTitle,
      AppMainHomeSaveDevList
    }
  }
</script>

<style lang="scss" scoped>
  .l-home {
    padding: 3em;
    background-color: rgba(53, 73, 94, .2);
  }
</style>