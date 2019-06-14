<template>
  <div>
    <Nav />
    <no-ssr>
      <nuxt />
    </no-ssr>
  </div>
</template>

<script>
import Nav from './partials/nav';

export default {
  components: {
    Nav
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
</style>
