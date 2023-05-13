<template>
  <svg
      width="75"
      height="75"
      :style= "cssVars"
  >
    <rect
        id="rect925"
        class="rect925"
        width="75"
        height="75"
        x=0
        y=0 />
  </svg>
</template>

<script>
import ElementWithPos from "@/components/ElementWithPos";

export default {
  name: "BigSquare",
  extends: ElementWithPos,
}
</script>

<style scoped>

.rect925{
  fill:#000000;
  stroke:#000000;
  stroke-width:1;
}
</style>