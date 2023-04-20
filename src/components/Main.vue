<template>
  <div class="main-panel">
    <div class="picture">
      <div class="phone" >
        <div class = "screen">

        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'main-panel',
  components: {
  }
}
</script>
<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.main-panel{
  height: 100vh;
}
.picture{
  position: relative;
}
.phone{
  position: absolute;
  top: 50%;
  left: 50%;
  width: 250px;
  height: 500px;
  background: #141444;
  border-radius: 25px;
  margin:0 0 0 -120px;
}
.screen{
  position: absolute;
  top: 10px;
  left: 3px;
  width:244px;
  height: 470px;
  background: #d8dde2;
  border-radius: 20px;
}
</style>