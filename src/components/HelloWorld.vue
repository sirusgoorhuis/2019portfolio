<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Welcome to my portfolio. It may not look like much yet but I'm working on it! Expect there to be some mayor changes. You can check my progress here and if you want to know more vistit my
      <a href="https://github.com/sirusgoorhuis/2019portfolio" target="_blank" rel="noopener">GitHub</a>.
    </p>
    
    <section>
      <h3>Portfolio</h3>
      <div id="portfolioImage"></div>
      <p>
        Learn more about my work!
      </p>
    </section>

    <section>
      <h3>About me</h3>
      <div id="aboutMeImage"></div>
      <p>
          Get to know me a bit better.
      </p>
    </section>

    <section>
      <h3>Something Fun!</h3>
      <div id="somethingFunImage"></div>
      <p></p>
    </section>
    
    <footer>

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
h3 {
  margin: 40px 0 0;
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
  width: 90vw;
  height: 90vw;
  background-image: url(https://festivalfans.nl/wp-content/uploads/2014/11/paaspop-2019.png);
  background-size: cover;
  background-repeat: no-repeat;
  margin: 10px;
}
#aboutMeImage {
  width: 90vw;
  height: 90vw;
  background-image: url(https://avatars1.githubusercontent.com/u/31924849?s=460&v=4);
  background-size: cover;
  background-repeat: no-repeat;
  margin: 10px;
}
#somethingFunImage {
  width: 90vw;
  height: 90vw;
  background-image: url('../assets/fuut.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  margin: 10px;
}
</style>
