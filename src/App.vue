<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgba(12, 11, 11, 0.918);
  margin-top: 60px;
}
#navBar {
  width: 100%;
  height: 10vw;
}
.navItem {
  list-style-type: none;
  display: inline-block;
  margin: 2vw;
}
.link {
   text-decoration: none;
   padding: 1vw;
   color: rgba(12, 11, 11, 0.918);
}
.link:hover {
  background-color: black;
  color: rgba(12, 11, 11, 0.918);
}
</style>
