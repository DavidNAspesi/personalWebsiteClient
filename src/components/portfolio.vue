<template>
  <v-carousel class="container">
    <v-carousel-item v-for="(item,i) in items" :src="item.img" :key="i"></v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
    name: "portfolio",
    props: [
        "item",
        "items"
            ]
}
</script>

<style scoped>

</style>
