<template>
  <div>
    <img v-lazy-load data-src="~/assets/menu/digestivi/page_1.jpg">
    <img v-lazy-load data-src="~/assets/menu/digestivi/page_2.jpg">
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
img {
  width: 100%;
  height: 100%;
  opacity: 0;

  -webkit-transition: opacity ease-in .6s;
  -moz-transition: opacity ease-in .6s;
  -ms-transition: opacity ease-in .6s;
  -o-transition: opacity ease-in .6s;
  transition: opacity ease-in .6s;
}

.isLoaded {
  height: unset;
  opacity: 1;
}

@media all and (max-width: 768px) {
  img {
    width: 100%;
  }
}
</style>
