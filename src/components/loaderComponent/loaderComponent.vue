<template>
  <div id="loaderComponent" v-if="visible">
    <img
      class="animate__animated animate__bounce animate__infinite	animate__delay-2s "
      src="../../assets/images/pokeball.svg"
    />
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
