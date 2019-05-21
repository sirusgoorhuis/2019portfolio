<template>
  <div id="app">
    <nav id="navBar">
      <li class="navItem"><a class="link" href="https://google.com">Home</a></li>
      <li class="navItem"><a class="link" href="https://google.com">About</a></li>
      <li class="navItem"><a class="link" href="https://google.com">Contact</a></li>
    </nav>
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'app',
  components: {
    HelloWorld,
  },
};
</script>

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
