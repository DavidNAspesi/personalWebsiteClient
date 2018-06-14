<template>
  <div class="cont">
    <img alt="double helix" src="../assets/icon.svg">
      <div class="subcontainer">
        <h1>David N. Aspesi</h1>
        <h3>Full Stack Web Developer</h3>
        <div class="buttonDiv">
          <a class="btn btn-secondary btn-sm" href="https://drive.google.com/file/d/1X0T-7-uHokbAvEiyTE9RlJdlnIqbqg8m/view?usp=sharing">See my resume!</a>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: "introduction",
}
</script>


<style scoped>
.cont {
  margin-top: 30px;
  display: flex;
  justify-content: space-around;
  align-content: center;
  background-color: #2A9FD6;
  padding-left: 1.5in;
  padding-right: 2in;
}

img {
  height: 2in;
  align-self: center;
}

.subcontainer {
  margin-top: 1in;
}

.buttonDiv {
  display: flex;
  justify-content: center;
}
</style>
