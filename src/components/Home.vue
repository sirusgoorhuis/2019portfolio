<template>
  <div class="md-layout">
    <h1>Hi, i'm Sirus Goorhuis</h1>
    <p>
      Welcome to my portfolio. It may not look like much yet but I'm working on it! Expect there to be some mayor changes. You can check my progress here and if you want to know more vistit my
      <a href="https://github.com/sirusgoorhuis/2019portfolio" target="_blank" rel="noopener">GitHub</a>.
    </p>

    <section class="md-layout-item">
      <nuxt-link to="/app-portfolio">
        <h3>Portfolio</h3>
        <div id="portfolioImage" class="md-elevation-24"></div>
        <p>
          Learn more about my work!
        </p>
      </nuxt-link>  
    </section>

    <section class="md-layout-item">
      <h3>About me</h3>
      <div id="aboutMeImage" class="md-elevation-24"></div>
      <p>
          Get to know me a bit better.
      </p>
    </section>

    <section class="md-layout-item">
      <h3>Something Fun!</h3>
      <div id="somethingFunImage" class="md-elevation-24"></div>
      <p></p>
    </section>
    
    <footer class="md-layout-item">

    </footer>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@import url('https://cdnjs.cloudflare.com/ajax/libs/vue-material/0.7.4/vue-material.css');

h1 {
  width: 100vw;
  text-align: center;
}
h3 {
  margin: 40px 0 0;
  width: 100%;
  text-align: center;
  float: center;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #f700cd;
  text-decoration: none;
}
#portfolioImage {
  width: 80vw;
  height: 50vw;
  background-image: url(https://festivalfans.nl/wp-content/uploads/2014/11/paaspop-2019.png);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  margin: 10px;
  text-align: center;
  align-content: center;
  display: inline-block;
  /* box-shadow: 5px 5px 5px rgba(255, 255, 255, 0.699); */
}
#aboutMeImage {
  width: 80vw;
  height: 50vw;
  background-image: url(https://avatars1.githubusercontent.com/u/31924849?s=460&v=4);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  margin-left: 10px;
  display: inline-block;
  /* box-shadow: 5px 5px 5px rgba(255, 255, 255, 0.699); */
}
#somethingFunImage {
  width: 80vw;
  height: 50vw;
  background-image: url('../assets/fuut.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  margin-left: 10vw;
  display: inline-block;
  /* box-shadow: 5px 5px 5px rgba(255, 255, 255, 0.699); */
}
</style>
