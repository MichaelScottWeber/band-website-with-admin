<template>
  <svg
    :fill="color"
    :width="size"
    :height="size"
    viewBox="-6 0 24 24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="m12.462.173v3.808h-2.265c-.079-.011-.171-.017-.264-.017-.542 0-1.036.203-1.411.538l.002-.002c-.275.384-.439.863-.439 1.381 0 .062.002.124.007.185v-.008 2.726h4.229l-.56 4.27h-3.663v10.946h-4.417v-10.947h-3.68v-4.269h3.68v-3.145c-.007-.102-.011-.222-.011-.342 0-1.478.575-2.822 1.513-3.82l-.003.003c.972-.92 2.288-1.485 3.735-1.485.09 0 .18.002.27.007h-.013c.118-.002.256-.003.395-.003 1.02 0 2.025.064 3.011.188l-.117-.012z"
    />
  </svg>
</template>

<script setup lang="ts">
import { IconPropsType } from '../../types.ts';

const props = withDefaults(defineProps<IconPropsType>(), {
  color: '#000000',
  size: '100px',
});
</script>

<style scoped></style>
