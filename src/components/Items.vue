<template>
  <div class="items">
    <Item />
    <Item />
    <Item />
    <Item />
    <Item />
    <Item />
    <Item />
    <Item />
    <Item />
    <Item />
    <Item />
  </div>
</template>

<script>
import Item from "@/components/Item";
export default {
  name: "Items",
  components: { Item }
};
</script>

<style scoped lang="scss">
.items {
  height: 100%;
  display: grid;
  justify-content: space-evenly;
  align-items: center;
  padding: 2rem;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 2rem;

  .item {
    background: black;
    overflow-y: hidden;
    height: 300px;
    width: 200px;

    &:nth-child(odd) {
      background-color: white;
    }
  }
}
</style>
