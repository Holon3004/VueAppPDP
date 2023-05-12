<template>
  <svg
      class="u_svgb"
      width="75"
      height="75"
      :style="cssVars">
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
    //alert(document.element.class)
  },
  computed:{
    cssVars(){
      return{
        '--pos-b-x': this.x + 'px',
        '--pos-b-y': this.y + 'px'
      }
    }
  }
}
</script>

<style scoped>

.rect925{
  fill:#000000;
  stroke:#000000;
  stroke-width:1;
}
.u_svgb{
  --pos-b-x: 0px;
  --pos-b-y: 0px;
  position: absolute;
  left: var(--pos-b-x);
  top: var(--pos-b-y);
}

</style>