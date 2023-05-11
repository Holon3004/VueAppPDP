<template>
  <svg
      class="u_svg"
    width="40"
    height="40">
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
export default {
  name: "LittleSquare",
  props: ['x', 'y'],
  data(){
    let x_s = this.x + "px";
    let y_s = this.y + "px";
    document.body.style.setProperty("--pos-l-x", x_s),
        document.body.style.setProperty("--pos-l-y", y_s)
  }
}
</script>

<style scoped>
:root{
  --pos-l-x:0px;
  --pos-l-y:0px;
}
.rect923{
  fill:#0000ff;
  stroke:#0000ff;
  stroke-width:1
}
.u_svg{
  position: absolute;
  left: var(--pos-l-x);
  top: var(--pos-l-y);
}
</style>