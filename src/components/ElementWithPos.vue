<template>
  <div>

  </div>
</template>

<script>
export default {
  name: "ElementWithPos",
  props: ['x', 'y'],
  computed:{
    cssVars(){
      return{
        '--pos-x': this.x + 'px',
        '--pos-y': this.y + 'px'
      }
    }
  }

}
</script>

<style scoped>

</style>