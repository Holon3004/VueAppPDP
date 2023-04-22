<template>
  <main-panel>
  </main-panel>
  <little-square :x="30" :y="35"/>
  <big-square :x="30" :y="110"/>
</template>

<script>
import MainPanel from "@/components/Main";
import LittleSquare from "@/components/LittleSquare";
import BigSquare from "@/components/BigSquare";

export default {
  name: 'App',
  components: {
    BigSquare,
    LittleSquare, MainPanel,
  }
}
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}



</style>
