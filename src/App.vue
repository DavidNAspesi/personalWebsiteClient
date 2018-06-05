<template>
  <div id="app">
    <theHeader></theHeader>
    <a name="intro">
      <introduction id="intro"></introduction>
    </a>
    <a name="about">
      <aboutMe id="about"></aboutMe>
    </a>
    <a name="portfolio">
      <portfolio id="portfolio"></portfolio>
    </a>
    <a name="contact">
      <contactMe id="contact"></contactMe>
    </a>
  </div>
</template>

<script>
import theHeader from "@/components/theHeader"
import introduction from '@/components/introduction'
import aboutMe from "@/components/aboutMe"
import portfolio from "@/components/portfolio"
import contactMe from "@/components/contactMe"

export default {
  name: 'app',
  components: {
    theHeader,
    introduction,
    aboutMe,
    portfolio,
    contactMe
  }
}
</script>

<style>
#intro {
  height: 400px;
}

#about {
  height: 400px;
}

#portfolio {
  height: 400px;
}

#contact {
  height: 400px;
}
</style>
