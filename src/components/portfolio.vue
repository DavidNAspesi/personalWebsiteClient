<template>
  <v-carousel class="container">
    <v-carousel-item v-for="(item,i) in items" :src="item.src" :key="i"></v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
    name: "portfolio"
}
</script>

<style scoped>

</style>
