<template>
  <header>
    <div class="header-container">
      <div class="logo-container">
        <img src="" alt="" />
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
            <a href=""><InstagramIcon size="20px" /></a>
          </li>
          <li>
            <a href=""><FacebookIcon size="20px" /></a>
          </li>
          <li>
            <a href=""><YoutubeIcon size="20px" /></a>
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

<style scoped></style>
