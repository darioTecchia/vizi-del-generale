<template>
  <div class="info">
    <div class="logo">
      <LogoVizi />
    </div>
    <div class="info-box">
      <span>Bar • Gelateria I Vizi del Generale</span>
      <br><br>
      <span>
        <a target="_blank" href="https://goo.gl/maps/Jx5F4pw1v1LpsLPf6">P.za Generale Avitabile, 6, 80051 Agerola NA</a>
      </span>
      <br><br>
      <span><a href="tel:+39 347 569 9819">347 569 9819</a></span>
    </div>
  </div>
</template>

<script>
import LogoVizi from '~/components/logo/LogoVizi.vue'

export default {
  components: {
    LogoVizi
  },
  head: {
    title: 'Vizi del Generale - Info'
  }
}
</script>

<style scoped>
.info {
  display: flex;
  height: 100vh;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  flex-wrap: wrap;
}

.info > div {
  width: 18%;
  flex: 1 1 18%;
}

@media all and (max-aspect-ratio: 1/1) {
  .info {
    flex-direction: column;
    padding-top: 54px;
  }

  .info-box{
    width: fit-content !important;
  }

  .info > div {
    width: 40%;
    flex: 0 1 40%;
  }
}
</style>
