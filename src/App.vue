<template>
  <div class="app">
    <div class="nav">
      <router-link to="/home">spacer</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss" scoped>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,400;0,600;0,800;1,300&display=swap');

  * {
    box-sizing: border-box;
  }

  body {
    font-family: 'Montserrat', sans-serif;
    margin: 0;
    padding: 0;
  }
</style>
