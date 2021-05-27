<template>
  <div class="birre">
    <MenuBirre />
  </div>
</template>

<script>
import MenuBirre from '~/components/partials/MenuBirre.vue'

export default {
  head: {
    title: 'Vizi del Generale - Birre'
  },
  components: {
    MenuBirre
  }
}
</script>

<style scoped>
.birre {
  display: flex;
  height: 100vh;
  justify-content: center;
  text-align: center;
  margin-top: 120px;
}

.birre h1 {
  align-self: center;
}
</style>
