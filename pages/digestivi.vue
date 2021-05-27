<template>
  <div class="digestivi">
    <MenuDigestivi />
  </div>
</template>

<script>
import MenuDigestivi from '~/components/partials/MenuDigestivi.vue'

export default {
  head: {
    title: 'Vizi del Generale - Digestivi'
  },
  components: {
    MenuDigestivi
  }
}
</script>

<style scoped>
.digestivi {
  display: flex;
  height: 100vh;
  justify-content: center;
  text-align: center;
  margin-top: 120px;
}

.digestivi h1 {
  align-self: center;
}
</style>
