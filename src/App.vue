<script setup></script>

<template>
  <div class="main">
    <div class="main-top"></div>
    <div class="main-bottom">
      <div class="main-bottom-detail meta-width" v-for="item in 30"></div>
    </div>
  </div>
</template>

<style scoped>
html,
body {
  margin: 0;
  padding: 0;
}

.main-top {
  height: 60px;
  background: black;
}

.main-bottom {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 0 20px;
}

.main-bottom-detail {
  margin: 10px 0;
  height: 255px;
  width: 300px;
  background: #ccc;
  border-radius: 3px;
}
</style>
