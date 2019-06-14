<template>
  <ul class="filters">
    <li>
      <label>
        <select name="year"></select>
      </label>
    </li>
    <li>
      <label>
        <select name="genre"></select>
      </label>
    </li>
  </ul>
</template>

<script>
export default {
  name: "Filters"
};
</script>

<style scoped lang="scss">
.filters {
  background: wheat;
  height: 60px;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  list-style: none;
  margin: 0;
  padding: 0;
}
</style>
