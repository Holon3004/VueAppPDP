<template>
  <svg>
    <rect
          id="rect925"
          class="rect925"
          width="75"
          height="80"
          x={{y}}
          y={{x}} />
  </svg>
</template>

<script>
export default {
  name: "BigSquare",
  props: ['x', 'y']
}
</script>

<style scoped>
.rect925{
  fill:#000000;
  stroke:#000000;
  stroke-width:1
}
</style>