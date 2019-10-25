<template>
  <div class="home">
    <div class="row mt-5">
      <WhoAmI />
      <Education />
    </div>
  </div>
</template>

<script>
import WhoAmI from "../components/WhoAmI";
import Education from "../components/Education";
export default {
  name: "home",
  components: { WhoAmI, Education }
};
</script>

<style>
.edu-img {
  height: 10vh;
  width: 10vh;
}
.h5-edu {
  display: inline;
}
.bsu {
  height: 10vh;
  width: 12vh;
}
</style>
