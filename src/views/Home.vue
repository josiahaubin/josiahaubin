<template>
  <div class="home">
    <div class="row mt-5">
      <WhoAmI />
      <Education />
    </div>
    <hr />
    <div class="row mt-4">
      <KnowledgeBase />
    </div>
    <hr />
    <Projects />
    <hr />
    <Contact />
  </div>
</template>

<script>
import WhoAmI from "../components/WhoAmI";
import Education from "../components/Education";
import KnowledgeBase from "../components/KnowledgeBase";
import Projects from "../components/Projects";
import Contact from "../components/Contact";
export default {
  name: "home",
  components: { WhoAmI, Education, KnowledgeBase, Projects, Contact }
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
