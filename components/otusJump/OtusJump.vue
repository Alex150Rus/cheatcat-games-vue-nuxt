<template>
  <div class="grid">
    <Otus/>
    <Platforms :qty="qty"/>
  </div>
</template>

<script>

import Otus from "@/components/otusJump/Otus";
import Platforms from "@/components/otusJump/Platforms";
export default {
  name: "OtusJump",
  components: {Otus, Platforms},
  data() {
    return {
    qty: 5
  }
  },
  methods: {
    start() {

    },
  }
}
</script>

<style scoped>
  .grid {
    width: 400px;
    height: 600px;
    background-color: yellow;
    position: relative;
  }
</style>
