<template>
  <div :class="['otus', isGameOver ? 'd-none' : '' ]" :style="{left: leftPosition + 'px', bottom: bottomPosition + 'px'}"></div>
</template>

<script>
export default {
name: "Otus",
  data() {
    return {
      leftPosition: 50,
      bottomPosition: 150,
      isGameOver: false,
    }
  },
}
</script>

<style scoped>
.otus {
  width: 60px;
  height: 85px;
  background-color: red;
  position: absolute;
}
</style>
