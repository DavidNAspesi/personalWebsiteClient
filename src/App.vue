<template>
  <div id="app">
    <img src="./assets/logo.png">
    <introduction></introduction>
    <aboutMe></aboutMe>
    <portfolio></portfolio>
    <contactMe></contactMe>
  </div>
</template>

<script>
import introduction from '@/components/introduction'
import aboutMe from "@/components/aboutMe"
import portfolio from "@/components/portfolio"
import contactMe from "@/components/contactMe"

export default {
  name: 'app',
  components: {
    introduction,
    aboutMe,
    portfolio,
    contactMe
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
