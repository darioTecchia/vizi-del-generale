<template>
  <div class="colazione">
    <MenuColazione />
  </div>
</template>

<script>
import MenuColazione from '~/components/partials/MenuColazione.vue'

export default {
  head: {
    title: 'Vizi del Generale - Colazione'
  },
  components: {
    MenuColazione
  }
}
</script>

<style scoped>
.colazione {
  display: flex;
  height: 100vh;
  justify-content: center;
  text-align: center;
  margin-top: 120px;
}

.colazione h1 {
  align-self: center;
}
</style>
