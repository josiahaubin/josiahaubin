<template>
  <div id="app" class="container-fluid">
    <div id="nav">
      <div class="row align-items-center mt-5">
        <div class="col-12 col-md-6">
          <img
            src="https://avatars1.githubusercontent.com/u/53383352?s=460v=4"
            alt="Josiah Aubin Photo"
            class="mb-1"
          />
        </div>
        <div class="col-12 col-md-4">
          <h1 class="navFont">Josiah Aubin</h1>
          <h1>Software Developer</h1>
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <a href="https://github.com/josiahaubin" class="mx-2">
            <i class="fab fa-github"></i> GitHub
          </a>
          <a href="https://www.linkedin.com/in/josiah-aubin/" class="mx-2">
            <i class="fab fa-linkedin"></i> LinkedIn
          </a>
        </div>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}

#nav a {
  color: black;
}

#nav a:hover {
  color: blue;
}

#nav img {
  height: 30vh;
  width: 30vh;
  border-radius: 10px;
  box-shadow: 0px 0px 5px 1px;
}
.navFont {
  font-size: 4em;
}
</style>
