<template>
  <big-square :x="300"
              :y="35"
              class="universal_svg"
  />

  <big-square :x="30"
              :y="15"
              class="universal_svg"
  />
  <little-square :x="300"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="340"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="380"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="300"
                 :y="390"
                 class="universal_svg"
  />
  <little-square :x="300"
                 :y="430"
                 class="universal_svg"
  />
  <little-square :x="300"
                 :y="470"
                 class="universal_svg"
  />
  <little-square :x="300"
                 :y="510"
                 class="universal_svg"
  />
  <little-square :x="340"
                 :y="510"
                 class="universal_svg"
  />
  <little-square :x="380" :y="510" class="universal_svg"
  />

  <little-square :x="450"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="490"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="530"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="450"
                 :y="390"
                 class="universal_svg"
  />
  <little-square :x="450"
                 :y="430"
                 class="universal_svg"
  />
  <little-square :x="450"
                 :y="470"
                 class="universal_svg"
  />
  <little-square :x="450"
                 :y="510"
                 class="universal_svg"
  />
  <little-square :x="530"
                 :y="390"
                 class="universal_svg"
  />
  <little-square :x="530"
                 :y="430"
                 class="universal_svg"
  />
  <little-square :x="530"
                 :y="470"
                 class="universal_svg"
  />
  <little-square :x="530"
                 :y="510"
                 class="universal_svg"
  />
  <little-square :x="490"
                 :y="470"
                 class="universal_svg"
  />

  <little-square :x="600"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="600"
                 :y="390"
                 class="universal_svg"
  />
  <little-square :x="600"
                 :y="430"
                 class="universal_svg"
  />
  <little-square :x="600"
                 :y="470"
                 class="universal_svg"
  />
  <little-square :x="600"
                 :y="510"
                 class="universal_svg"
  />
  <little-square :x="640"
                 :y="470"
                 class="universal_svg"
  />
  <little-square :x="680"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="680"
                 :y="390"
                 class="universal_svg"
  />
  <little-square :x="680"
                 :y="430"
                 class="universal_svg"
  />
  <little-square :x="680"
                 :y="470"
                 class="universal_svg"
  />
  <little-square :x="680"
                 :y="510"
                 class="universal_svg"
  />

  <little-square :x="750"
                 :y="390"
                 class="universal_svg"
  />
  <little-square :x="750"
                 :y="430"
                 class="universal_svg"
  />
  <little-square :x="750"
                 :y="510"
                 class="universal_svg"
  />
  <little-square :x="790"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="790"
                 :y="470"
                 class="universal_svg"
  />
  <little-square :x="830"
                 :y="350"
                 class="universal_svg"
  />
  <little-square :x="830"
                 :y="390"
                 class="universal_svg"
  />
  <little-square :x="830"
                 :y="430"
                 class="universal_svg"
  />
  <little-square :x="830"
                 :y="470"
                 class="universal_svg"
  />
  <little-square :x="830"
                 :y="510"
                 class="universal_svg"
  />

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

.universal_svg{
  --pos-x: 0px;
  --pos-y: 0px;
  position: absolute;
  left: var(--pos-x);
  top:var(--pos-y);
}
</style>
