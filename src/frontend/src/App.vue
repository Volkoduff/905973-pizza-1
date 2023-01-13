<template>
  <div id="app">
    <div class="main">
      <AppIndex/>
    </div>
  </div>
</template>

<script>
import AppIndex from './views/Index'

export default {
  name: "App",
  components: {
    AppIndex
  }
};
</script>

<style lang="scss">
@import "~@/assets/scss/app";
</style>
