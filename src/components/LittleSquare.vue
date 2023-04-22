<template>
  <rect
      style="fill:#0000ff;stroke:#0000ff;stroke-width:1"
      id="rect923"
      width="40"
      height="40"
      x={{y}}
      y={{x}} />
</template>

<script>
export default {
  name: "LittleSquare",
  props: ['x', 'y']
}
</script>

<style scoped>

</style>