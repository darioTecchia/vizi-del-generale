<template>
  <div class="drink">
    <MenuDrink />
  </div>
</template>

<script>
import MenuDrink from '~/components/partials/MenuDrink.vue'

export default {
  head: {
    title: 'Vizi del Generale - Drink'
  },
  components: {
    MenuDrink
  }
}
</script>

<style scoped>
.drink {
  display: flex;
  height: 100vh;
  justify-content: center;
  text-align: center;
  margin-top: 120px;
}

.drink h1 {
  align-self: center;
}
</style>
