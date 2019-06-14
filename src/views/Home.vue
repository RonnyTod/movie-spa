<template>
  <div class="home">
    <Filters />
    <Items />
  </div>
</template>

<script>
import Filters from "@/components/Filters";
import Items from "@/components/Items";
export default {
  name: "home",
  components: {
    Items,
    Filters
  },
  data: function() {
    return {};
  }
};
</script>

<style scoped lang="scss">
.home {
  min-height: 100%;
  background-color: #7a96bc;
  width: 800px;
  margin: 0 auto;
}
</style>
