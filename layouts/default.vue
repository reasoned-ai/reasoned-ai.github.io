<template>
  <div>
    <Nav />
    <div class="parallax-container">
      <no-ssr>
        <parallax speed-factor="1.0" breakpoint="(min-width: 80px)" class="parallax-img" sectionHeight=100>
          <img src="../assets/images/background.jpg" class="background">
        </parallax>
        <nuxt class="parallax-title"/>
      </no-ssr>
    </div>
    <Footer />
  </div>
</template>

<script>
import Nav from './partials/nav';
import Parallax from "vue-parallaxy";
import Footer from './partials/footer';

export default {
  components: {
    Nav, Parallax, Footer
  }

}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 12px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

@media (min-width:300px) {
  body {
    font-size: 12px;
  }
}

@media (min-width:800px) {
  body {
    font-size: 16px;
  }
}

@media (min-width:2000px) {
  body {
    font-size: 20px;
  }
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #03d6a5;
  color: #03d6a5;
  text-decoration: none;
  padding: 0.6em 2em;
  margin-left: 1em;
  transition-duration: 0.5s;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
  transform: scale(1.1);
}

.button--blue {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #04aada;
  color: #04aada;
  text-decoration: none;
  padding: 0.6em 2em;
  margin-left: 1em;
  transition-duration: 0.5s;
}

.button--blue:hover {
  color: #fff;
  background-color: #35495e;
  transform: scale(1.1);
}

.button--white {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid rgb(210, 210, 210);
  color: rgb(210, 210, 210);
  text-decoration: none;
  padding: 0.6em 2em;
  margin-left: 1em;
  transition-duration: 0.5s;
}

.button--white:hover {
  color: #fff;
  background-color: rgb(110, 110, 110);
  transform: scale(1.1);
}

.parallax-container {
  position: relative;
}

.parallax-container img {
  opacity: 1;
}

.parallax-title {
  position: absolute;
  top: 20%;
  left: 2%;
  right: 2%;
  padding: 1em;
  background: rgba(0, 0, 0, 0);
  color: white;
  text-align: center;
}

@media (min-width:800px) {
  .parallax-container {
    height: 35em;
  }
  .parallax-title {
    top: 5%;
  }
}

@media (min-width:2000px) {
  .parallax-container {
    height: 68em;
  }
  .parallax-title {
    top: 10%;
  }
}

.background {
  filter: brightness(0.35);
}
</style>
