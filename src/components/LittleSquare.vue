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
        document.body.style.setProperty("--pos-l-x", this.x+'px'),
        document.body.style.setProperty("--pos-l-y", this.y+'px')
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