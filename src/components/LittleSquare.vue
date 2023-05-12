<template>
  <svg
      class="u_svgl"
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
export default {
  name: "LittleSquare",
  props: ['x', 'y'],
  data(){
        //document.body.style.setProperty("--pos-b-x", this.x+'px'),
        //document.body.style.setProperty("--pos-b-y", this.y+'px')
  },
  computed:{
    cssVars(){
      return{
        '--pos-l-x': this.x + 'px',
        '--pos-l-y': this.y + 'px'
      }
    }
  }
}
</script>

<style scoped>

.rect923{
  fill:#0000ff;
  stroke:#0000ff;
  stroke-width:1
}
.u_svgl{
  --pos-l-x: 0px;
  --pos-l-y: 0px;
  position: absolute;
  left: var(--pos-l-x);
  top:var(--pos-l-y);
}

</style>