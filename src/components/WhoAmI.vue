<template>
  <div class="WhoAmI col-12 col-md-6">
    <h3>Who Am I?</h3>
    <p class="text-left mt-4 mx-3">
      Greetings, my name is Josiah Aubin. I am a software developer who loves
      all
      things coding.
      <br />I developed a love for coding after my first coding class in college. After a few more
      classes
      that required coding and getting lost in it for hours on end, I realized that a career as a developer
      was for
      me. After graduation, I attended Boise CodeWorks to futher my coding skill and to gain the knowledge needed to perform at my
      best
      in the industry.
    </p>
    <p class="text-left mt-2 mx-3">
      If I am not spending my time behind a computer writing lines of code you can find
      me:
    </p>
    <ul class="text-left list-unstyled mx-4">
      <li class="py-1">
        Completing main missions (after all the side missions of course), capturing objectives,
        holding control
        points, or pushing payloads in some of my favorite videogames.
      </li>
      <li class="py-1">Spending time outdoors camping, fishing, and hunting.</li>
      <li class="py-1">Getting excerise by lifting weights or playing basketball.</li>
      <li class="py-1">Laughing with friends, or enjoying time with my family.</li>
    </ul>
    <img
      src="https://scontent.fboi1-1.fna.fbcdn.net/v/t1.0-9/64345640_2246232095424358_4702654263275290624_n.jpg?_nc_cat=102&_nc_oc=AQlarcxC6umJb4xjkr7jAhM5WAoeYD7yG5ZvASOfg0PqwK8hykzjvdqrPZpfLtgeGvg&_nc_ht=scontent.fboi1-1.fna&oh=3590ef87b42c7b7a9ff40d80a2ac734e&oe=5E5512B7"
      class="mt-2"
    />
  </div>
</template>


<script>
export default {
  name: "WhoAmI",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
h3 {
  font-family: "Indie Flower", cursive;
}
img {
  height: 40vh;
  width: 70vh;
  border-radius: 5px;
  box-shadow: 0px 0px 5px 1px;
}
ul {
  font-family: "Blinker", sans-serif;
}
</style>