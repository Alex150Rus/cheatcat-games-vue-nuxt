<template>
  <div>
    <slot>dfgfg</slot>
  </div>
</template>

<script>

export default {
  name: "Platforms",
  props: ['qty'],
  data() {
    return {
      divs: []
    }
  },
  created() {
    this.divs = new Array(10);
  },
}
</script>

<style scoped>
.platform {
  width: 85px;
  height: 15px;
  background-color: green;
  position: absolute;
}
</style>
