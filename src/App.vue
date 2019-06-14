<template>
  <div id="app">
    <header>
      <h2>movieLoader</h2>
    </header>

    <router-view />
  </div>
</template>

<style lang="scss">
html {
  height: 100%;
}
body {
  height: 100%;
  margin: 0;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}

header {
  background-color: #507478;
  overflow-y: hidden;
  text-align: left;
  h2 {
    margin: 0.5em;
  }
}
</style>
