<template>
  <svg>
    <rect
        id="rect923"
        class="rect923"
        width="40"
        height="40"
        x={{x}}
        y={{y}} />
  </svg>
</template>

<script>
export default {
  name: "LittleSquare",
  props: ['x', 'y']
}
</script>

<style scoped>
.rect923{
  fill:#0000ff;
  stroke:#0000ff;
  stroke-width:1
}
</style>