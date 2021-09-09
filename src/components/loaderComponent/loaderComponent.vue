<template>
  <div id="loaderComponent" v-if="visible">
    <img src="../../assets/images/pokeball.svg" />
  </div>
</template>

<script>
export default {
  name: "LoaderComponent",
  props: {
    visible: {
      type: Boolean,
      required: true,
      default: false,
    },
  },
};
</script>

<style scoped>
@import url("loaderComponent.scss");
</style>

