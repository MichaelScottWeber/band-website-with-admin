<template>
  <section id="music">
    <h2>Listen now!</h2>
    <ul>
      <li>
        <a href=""> <SpotifyIcon size="60px" /> </a>
      </li>
      <li>
        <a href=""> <AppleMusicIcon size="60px" /> </a>
      </li>
      <li>
        <a href="">
          <AmazonIcon size="60px" />
        </a>
      </li>
      <li>
        <a href="">
          <YoutubeIcon size="60px" />
        </a>
      </li>
    </ul>
  </section>
</template>

<script setup lang="ts">
import SpotifyIcon from './icons/SpotifyIcon.vue';
import AppleMusicIcon from './icons/AppleMusicIcon.vue';
import AmazonIcon from './icons/AmazonIcon.vue';
import YoutubeIcon from './icons/YoutubeIcon.vue';
</script>

<style scoped></style>
