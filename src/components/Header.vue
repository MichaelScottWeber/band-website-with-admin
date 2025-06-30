<template>
  <header>
    <div class="header-container">
      <div class="logo-container">
        <img src="../assets/The-Disconnect-Logo-80.jpg" alt="The Disconnect" />
      </div>
      <nav>
        <ul class="nav-links">
          <li><a href="/">Home</a></li>
          <li><a href="#music">Music</a></li>
          <li><a href="#shows">Shows</a></li>
          <li><a href="#merch">Merch</a></li>
        </ul>
        <ul class="social-links">
          <li>
            <a href=""><InstagramIcon color="#ffffff" size="20px" /></a>
          </li>
          <li>
            <a href=""><FacebookIcon color="#ffffff" size="20px" /></a>
          </li>
          <li>
            <a href=""><YoutubeIcon color="#ffffff" size="20px" /></a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script setup lang="ts">
import InstagramIcon from './icons/InstagramIcon.vue';
import FacebookIcon from './icons/FacebookIcon.vue';
import YoutubeIcon from './icons/YoutubeIcon.vue';
</script>

<style scoped>
header {
  background-color: #0c0b0b;
  color: #ffffff;
}

.header-container {
  max-width: 1280px;
  display: flex;
  height: 80px;
  align-items: center;
  justify-content: start;
  padding: 0 24px;
  gap: 24px;
  margin: 0 auto;
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
}

ul {
  display: flex;
  text-transform: uppercase;
  gap: 10px;
}

ul:first-of-type {
  font-size: 20px;
  gap: 20px;
}

li {
}

a {
  text-decoration: none;
}

img {
  /* height: 80px; */
}
</style>
