<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#intro">Introduction</a>
        <a class="navbar-brand" href="#about">About Me</a>
        <a class="navbar-brand" href="#portfolio">Portfolio</a>
        <a class="navbar-brand" href="#contact">Contact Me!</a>


    </nav>
</template>

<script>
export default {
    name: "theHeader"
}
</script>

<style scoped>
.navbar {
    justify-content: space-around;
    position: fixed;
    width: 100%;
    top: 0;
    right: 0;
}
</style>
