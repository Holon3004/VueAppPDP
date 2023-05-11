<template>
  <svg
      class="u_svg"
      width="75"
      height="75">
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
export default {
  name: "BigSquare",
  props: ['x', 'y'],
  data(){
    let x_s = this.x + "px";
    let y_s = this.y + "px";
        document.body.style.setProperty("--pos-b-x", x_s),
        document.body.style.setProperty("--pos-b-y", y_s)
  }
}
</script>

<style scoped>

:root{
  --pos-b-x:0px;
  --pos-b-y:0px;
}
.rect925{
  fill:#000000;
  stroke:#000000;
  stroke-width:1;
}
.u_svg{
  position: absolute;
  left: var(--pos-b-x);
  top: var(--pos-b-y);
}

</style>