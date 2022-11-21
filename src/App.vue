<template>
  <div class="background">
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
html, body, #app {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  overflow: hidden;
}
.background {
  width: 100%;
  height: 100%;
  background-image: url("./assets/bbj.jpg");
  background-size: cover;
  background-position: center;
  z-index: -1;
  position: absolute;
}
</style>
