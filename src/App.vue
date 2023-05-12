<template>
  <little-square :x="30" :y="35"/>
  <big-square :x="300" :y="150"/>
</template>

<script>
import LittleSquare from "@/components/LittleSquare";
import BigSquare from "@/components/BigSquare";

export default {
  name: 'App',
  components: {
    BigSquare,
    LittleSquare,
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
