<script>
import AppBanner from "./components/AppBanner.vue";
import AppTitle from "./components/AppTitle.vue";

export default {
  components: {
    AppBanner,
    AppTitle
  },
  data() {
    return {
      title: "my title"
    }
  }
}

</script>

<template>
  <h1>html qui dentro {{ title }}</h1>
  <AppTitle />
  <AppBanner />
  <AppBanner />
  <AppBanner />
</template>

<style>
h1 {
  color: blue;
}
</style>