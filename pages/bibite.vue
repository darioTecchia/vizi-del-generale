<template>
  <div class="bibite">
    <MenuBibite />
  </div>
</template>

<script>
import MenuBibite from '~/components/partials/MenuBibite.vue'

export default {
  head: {
    title: 'Vizi del Generale - Bibite'
  },
  components: {
    MenuBibite
  }
}
</script>

<style scoped>
.bibite {
  display: flex;
  height: 100vh;
  justify-content: center;
  text-align: center;
  margin-top: 120px;
}

.bibite h1 {
  align-self: center;
}
</style>
