<template>
  <div id="app">
    <div id="nav"></div>
    <router-view />
  </div>
</template>

<style>
#app {
  @font-face {
    font-family: NunitoSans;
    src: url(./assets/NunitoSans-Regular.ttf);
  }
}

body {
  font-family: NunitoSans;
}
</style>
