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
        document.body.style.setProperty("--pos-b-x", this.x+'px'),
        document.body.style.setProperty("--pos-b-y", this.y+'px')
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