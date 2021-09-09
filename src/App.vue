<template>
  <LoaderComponent :visible="true" />
</template>

<script>
import LoaderComponent from "./components/loaderComponent/loaderComponent.vue";
export default {
  name: "App",
  components: {
    LoaderComponent,
  },
};
</script>

<style>
@import url("./assets/global/normalize.scss");
</style>
