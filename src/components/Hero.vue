<template>
  <div class="hero-container">
    <h1>The Disconnect</h1>
    <img src="../assets/IMG_9634 banner.jpg" alt="" />
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
h1 {
  text-transform: uppercase;
  font-size: min(10vw, 96px);
  white-space: nowrap;
  color: #fff;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  text-shadow: 6px 6px 4px rgba(0, 0, 0, 0.25);
}

img {
  position: relative;
}

.hero-container {
  display: inline-block;
  position: relative;
}
</style>
