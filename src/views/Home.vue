<template>
  <div class="home">
    <div class="row mt-5">
      <WhoAmI />
      <Education />
    </div>
    <KnowledgeBase />
  </div>
</template>

<script>
import WhoAmI from "../components/WhoAmI";
import Education from "../components/Education";
import KnowledgeBase from "../components/KnowledgeBase";
export default {
  name: "home",
  components: { WhoAmI, Education, KnowledgeBase }
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
