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
      <portfolio id="portfolio" :items="items"></portfolio>
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
  },
  data() {
    return {
      items: [
          {
              "id": 1,
              "title": "AccuTherm",
              "gitHub": "https://github.com/DavidNAspesi/AccuTherm",
              "img": "https://s15.postimg.cc/fio3qcfij/Screen_Shot_2018-06-06_at_3.58.17_PM.png"
          },
          {
              "id": 2,
              "title": "Bill Tracker",
              "gitHub": "https://github.com/DavidNAspesi/billTrackerClient",
              "img": "./billtracker.gif"
          },
          {
              "id": 3,
              "title": "Vocab Builder",
              "gitHub": "https://github.com/DavidNAspesi/Vocab-Builder-Client",
              "img": "./VocabBuilderGif.gif"
          },
          {
              "id": 4,
              "title": "Fridge Vision",
              "gitHub": "https://github.com/SethCaparelli/fridge-vision",
              "img": "./fridge-vision.gif"
          }
      ]
    }
  },
}
</script>

<style>
theHeader {
  z-index: 9999;
}

#intro {
  height: 400px;
}

#about {
  height: 400px;
}

#portfolio {
  height: 600px;
}

#contact {
  height: 400px;
}
</style>
