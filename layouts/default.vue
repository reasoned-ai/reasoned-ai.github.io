<template>
  <div>
    <Nav />
    <div class="parallax-container">
      <no-ssr>
        <nuxt class="parallax-title"/>
        <parallax :speed-factor="1.0" breakpoint="(min-width: 80px)">
          <img src="../assets/images/background.jpg" class="background">
        </parallax>
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
  font-size: 16px;
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

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #03d6a5;
  color: #03d6a5;
  text-decoration: none;
  padding: 10px 30px;
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
  padding: 10px 30px;
  margin-left: 15px;
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
  padding: 10px 30px;
  margin-left: 15px;
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
  padding: 20px;
  background: rgba(0, 0, 0, 0);
  color: white;
  text-align: center;
}

.background {
  filter: brightness(0.35);
}
</style>
