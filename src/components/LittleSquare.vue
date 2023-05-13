<template>
  <svg
    width="40"
    height="40"
    :style= "cssVars">
    <rect
        id="rect923"
        class="rect923"
        width="40"
        height="40"
        x=0
        y=0 />
  </svg>
</template>

<script>
import ElementWithPos from "@/components/ElementWithPos";

export default {
  name: "LittleSquare",
  extends: ElementWithPos,
}
</script>

<style scoped>

.rect923{
  fill:#0000ff;
  stroke:#0000ff;
  stroke-width:1
}
</style>