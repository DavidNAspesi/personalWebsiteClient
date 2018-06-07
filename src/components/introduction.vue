<template>
  <div class="container">
    <img alt="double helix" src="../assets/icon.svg">
      <div class="subcontainer">
        <h1>David N. Aspesi</h1>
        <h2>Full Stack Web Developer</h2>
      </div>
  </div>
</template>

<script>
export default {
  name: "introduction",
}
</script>


<style scoped>
.container {
  margin-top: 60px;
  display: flex;
  justify-content: space-around;
  align-content: center;
}

img {
  height: 3in;
}

.subcontainer {
  align-items: center;
  margin-top: 10%;
}
</style>
