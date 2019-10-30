<template>
  <div class="Projects row">
    <div class="col-12 mt-2">
      <h3>Projects</h3>
    </div>
    <div class="col-md-4">
      <img
        src="http://ksplumbinginc.com/wp-content/uploads/2018/03/shutterstock_611361611-555x555.jpg"
        alt="Coming Soon Image"
        class="img-projects"
      />
      <h5 class="txt-font-v2">Highland Authority</h5>
      <p class="mt-1 mx-2">
        <b>Project Description:</b> Worked with a group of peers to create a social stat tracking application for the Scottish Highland Games. We implemented user roles to allow admins to change roles and allow judges to create games and input scores for athletes. Used Vue.Js on the front-end, and used Express and Node.Js for the back-end. It also implements express-sessions for authentication, bcrypt for password hashing, mongoose as an ORM and MongoDB as the database.
      </p>
      <button type="button" class="btn btn-light">Go to Project</button>
    </div>
    <div class="col-md-4">
      <img
        src="http://ksplumbinginc.com/wp-content/uploads/2018/03/shutterstock_611361611-555x555.jpg"
        alt="Coming Soon Image"
        class="img-projects"
      />
      <h5 class="txt-font-v2">Kanban</h5>
      <p class="mt-1 mx-2">
        <b>Project Description:</b> Worked with a partner to create an application that allows users to create boards with lists, tasks, and comments. On the front-end we utilized Vue.Js, implementing the Vuex design and Vue-Router to manage the dom. This project also utilizes Express, Node.js, authentication, bcrypt, mongoose, and MongoDB.
      </p>
      <button type="button" class="btn btn-light">Go to Project</button>
    </div>
    <div class="col-md-4">
      <img
        src="http://ksplumbinginc.com/wp-content/uploads/2018/03/shutterstock_611361611-555x555.jpg"
        alt="Coming Soon Image"
        class="img-projects"
      />
      <h5 class="txt-font-v2">Keepr</h5>
      <p class="mt-1 mx-2">
        <b>Project Description:</b> Keepr is a social network, similar to Pinterest, that allows users to visually share, and discover new interests by posting images to their own or others' collections. It utilizes a Vue.Js front-end. The server side utilizes DotNet WebApi and implements the Repository pattern to communicate with the database. Keepr also utilizes bcrypt for password hashing, dapper as an ORM and MySQL as the database.
      </p>
      <button type="button" class="btn btn-light">Go to Project</button>
    </div>
  </div>
</template>


<script>
export default {
  name: "Projects",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
.img-projects {
  height: 25vh;
  width: 25vh;
  border-radius: 5px;
}
</style>