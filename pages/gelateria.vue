<template>
  <div class="gelateria">
    <MenuGelateria />
  </div>
</template>

<script>
import MenuGelateria from '~/components/partials/MenuGelateria.vue'

export default {
  head: {
    title: 'Vizi del Generale - Gelateria'
  },
  components: {
    MenuGelateria
  }
}
</script>

<style scoped>
.gelateria {
  display: flex;
  height: 100vh;
  justify-content: center;
  text-align: center;
  margin-top: 120px;
}

.gelateria h1 {
  align-self: center;
}
</style>
