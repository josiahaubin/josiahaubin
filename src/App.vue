<template>
  <div id="app" class="container-fluid">
    <div id="nav">
      <div class="row align-items-center">
        <div class="col-12 col-md-6 mt-3">
          <img
            src="https://avatars1.githubusercontent.com/u/53383352?s=460v=4"
            alt="Josiah Aubin Photo"
            class="mb-1"
          />
        </div>
        <div class="col-12 col-md-4 mt-3">
          <h1 class="navFont">Josiah Aubin</h1>
          <h1>Software Developer</h1>
        </div>
      </div>
      <div class="row navRow mt-2">
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
    <div class="row mt-4 navRow">
      <div class="offset-1 col-md-3 mt-2">
        <a href="https://github.com/josiahaubin" class="text-dark">
          <i class="fab fa-github fa-3x mx-3"></i>
        </a>
        <a href="https://www.linkedin.com/in/josiah-aubin/" class="text-dark">
          <i class="fab fa-linkedin fa-3x mx-3"></i>
        </a>
      </div>
      <div class="offset-2 col-md-6 mt-3">
        <p>This page was made by Josiah Aubin</p>
      </div>
    </div>
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
  background-color: #e9f0fa;
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

#nav h1 {
  font-family: "Indie Flower", cursive;
}

.navRow {
  background-color: #a4bde0;
  padding: 1%;
  border-radius: 1%;
}
.navFont {
  font-size: 4em;
}
p,
a {
  font-family: "Blinker", sans-serif;
}
</style>
