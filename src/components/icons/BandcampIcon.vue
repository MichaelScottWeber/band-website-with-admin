<template>
  <svg
    xmlns:dc="http://purl.org/dc/elements/1.1/"
    xmlns:cc="http://creativecommons.org/ns#"
    xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
    xmlns:svg="http://www.w3.org/2000/svg"
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 682.66669 682.66669"
    :height="size"
    :width="size"
    xml:space="preserve"
    id="svg2"
    version="1.1"
  >
    <defs id="defs6">
      <clipPath id="clipPath20" clipPathUnits="userSpaceOnUse">
        <path
          style="clip-rule: evenodd"
          id="path18"
          d="M 2560,0 C 3973.85,0 5120,1146.15 5120,2560 5120,3973.85 3973.85,5120 2560,5120 1146.15,5120 0,3973.85 0,2560 0,1146.15 1146.15,0 2560,0 Z"
        />
      </clipPath>
      <clipPath id="clipPath26" clipPathUnits="userSpaceOnUse">
        <path id="path24" d="M 0,0 H 5120 V 5120 H 0 Z" />
      </clipPath>
      <clipPath id="clipPath36" clipPathUnits="userSpaceOnUse">
        <path
          style="clip-rule: evenodd"
          id="path34"
          d="m 3248.57,2735.96 c -183.49,0 -277.25,-144.42 -277.25,-362 0,-205.66 101.38,-360.04 277.25,-360.04 198.89,0 273.45,182.02 273.45,360.04 -0.14,185.9 -93.84,362 -273.51,362 M 2761,3275.92 h 217.97 v -522.15 h 3.85 c 59.28,98.87 183.55,160.21 294.46,160.21 311.63,0 462.74,-245.35 462.74,-544.05 0,-274.84 -133.84,-533.97 -426.43,-533.97 -133.85,0 -277.25,33.54 -342.29,168.09 h -3.78 v -140.51 h -206.53 v 1412.35 l 0.01,0.03"
        />
      </clipPath>
      <clipPath id="clipPath42" clipPathUnits="userSpaceOnUse">
        <path id="path40" d="M 0,0 H 5120 V 5120 H 0 Z" />
      </clipPath>
      <clipPath id="clipPath52" clipPathUnits="userSpaceOnUse">
        <path
          style="clip-rule: evenodd"
          id="path50"
          d="m 4543.89,2544.02 c -17.22,124.62 -105.15,191.92 -225.61,191.92 -112.87,0 -271.54,-61.35 -271.54,-371.91 0,-170.13 72.64,-350.15 261.97,-350.15 126.18,0 214.11,87.14 235.18,233.51 h 217.97 c -40.16,-265.06 -198.84,-411.43 -453.15,-411.43 -309.78,0 -479.95,227.42 -479.95,528.07 0,308.56 162.53,549.89 487.6,549.89 229.44,0 424.54,-118.68 445.5,-369.91 h -217.61 l -0.36,0.01"
        />
      </clipPath>
      <clipPath id="clipPath58" clipPathUnits="userSpaceOnUse">
        <path id="path56" d="M 0,0 H 5120 V 5120 H 0 Z" />
      </clipPath>
      <clipPath id="clipPath68" clipPathUnits="userSpaceOnUse">
        <path
          style="clip-rule: evenodd"
          id="path66"
          d="M 1998.95,1866.62 H 364.078 l 763.462,1409.3 h 1634.88 l -763.47,-1409.3"
        />
      </clipPath>
      <clipPath id="clipPath74" clipPathUnits="userSpaceOnUse">
        <path id="path72" d="M 0,0 H 5120 V 5120 H 0 Z" />
      </clipPath>
    </defs>
    <g transform="matrix(1.3333333,0,0,-1.3333333,0,682.66667)" id="g10">
      <g transform="scale(0.1)" id="g12">
        <g id="g14">
          <g clip-path="url(#clipPath20)" id="g16">
            <g clip-path="url(#clipPath26)" id="g22">
              <path
                :fill="color1"
                id="path28"
                style="fill-opacity: 1; fill-rule: nonzero; stroke: none"
                d="M 0,0 H 5170 V 5170 H 0 Z"
              />
            </g>
          </g>
        </g>
        <g id="g30">
          <g clip-path="url(#clipPath36)" id="g32">
            <g clip-path="url(#clipPath42)" id="g38">
              <path
                :fill="color2"
                id="path44"
                style="fill-opacity: 1; fill-rule: nonzero; stroke: none"
                d="M 2710.99,1785.96 H 3790.02 V 3325.92 H 2710.99 Z"
              />
            </g>
          </g>
        </g>
        <g id="g46">
          <g clip-path="url(#clipPath52)" id="g48">
            <g clip-path="url(#clipPath58)" id="g54">
              <path
                :fill="color2"
                id="path60"
                style="fill-opacity: 1; fill-rule: nonzero; stroke: none"
                d="m 3778.76,1785.96 h 1033.1 v 1177.96 h -1033.1 z"
              />
            </g>
          </g>
        </g>
        <g id="g62">
          <g clip-path="url(#clipPath68)" id="g64">
            <g clip-path="url(#clipPath74)" id="g70">
              <path
                :fill="color2"
                id="path76"
                style="fill-opacity: 1; fill-rule: nonzero; stroke: none"
                d="m 314.078,1816.62 h 2498.34 v 1509.3 H 314.078 Z"
              />
            </g>
          </g>
        </g>
      </g>
    </g>
  </svg>
</template>

<script setup lang="ts">
type PropsType = {
  color1: string;
  color2: string;
  size: string;
};

const props = withDefaults(defineProps<PropsType>(), {
  color1: '#000000',
  color2: '#ffffff',
  size: '100px',
});
</script>

<style scoped></style>
