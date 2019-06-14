<template>
  <div class="item">
    <h2>filmName</h2>
  </div>
</template>

<script>
export default {
  name: "Item"
};
</script>

<style scoped lang="scss">
.item {
  background: black;
  overflow-y: hidden;
  height: 300px;
  width: 200px;

  &:nth-child(odd) {
    background-color: white;
  }
  &:nth-child(even) {
    color: white;
  }
}
</style>
