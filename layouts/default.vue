<template>
  <div>
    <Header />
    <Nuxt />
  </div>
</template>

<script>
import Header from '~/components/partials/Header.vue'

export default {
  components: {
    Header
  },
  created (context) {
    console.log('Developed by Dario Tecchia')
  },
  head: {
    title: 'Vizi del Generale'
  }
}
</script>

<style>
@font-face {
  font-family: 'EB Garamond';
  src: url('../assets/fonts/EBGaramond-Regular.eot');
  src: url('../assets/fonts/EBGaramond-Regular.eot?#iefix') format('embedded-opentype'),
      url('../assets/fonts/EBGaramond-Regular.woff2') format('woff2'),
      url('../assets/fonts/EBGaramond-Regular.woff') format('woff'),
      url('../assets/fonts/EBGaramond-Regular.ttf') format('truetype'),
      url('../assets/fonts/EBGaramond-Regular.svg#EBGaramond-Regular') format('svg');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

:root {
  --std-size: 40px;
  --petit-size: 20px;
}

a,
a:visited {
  text-decoration: none;
  color: #000000;
}

* {
  font-weight: lighter;
}

body {
  font-family: 'EB Garamond';
  margin: 0px;
  background: #f1f1f1 !important;
}

.upper-case {
  text-transform: uppercase;
}

.hide {
  display: none;
}
</style>
