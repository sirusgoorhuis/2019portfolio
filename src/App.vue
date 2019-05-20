<template>
  <div id="app">
    <nav id="navBar">
      <li class="navItem"><a class="link" href="https://google.com">Home</a></li>
      <li class="navItem"><a class="link" href="https://google.com">About</a></li>
      <li class="navItem"><a class="link" href="https://google.com">Contact</a></li>
    </nav>
    <HelloWorld msg="Hi, i'm Sirus Goorhuis"/>
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
  color: #2c3e50;
  margin-top: 60px;
}
#navBar {
  width: 100%;
  height: 10vw;;
}
.navItem {
  list-style-type: none;
  display: inline-block;
  margin: 2vw;
  float: center;
}
.link {
   text-decoration: none;
   padding: 1vw;
}
.link:hover {
  background-color: black;
  color: white;
}
</style>
