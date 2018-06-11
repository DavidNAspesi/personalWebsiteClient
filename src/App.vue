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
              "img": "https://s26.postimg.cc/pd51v5o7t/accuthermcap.jpg",
              "deployed": false,
              "deployedSite": ""
          },
          {
              "id": 2,
              "title": "Bill Tracker",
              "gitHub": "https://github.com/DavidNAspesi/billTrackerClient",
              "img": "https://s26.postimg.cc/ojsg2kkrt/bill_Tracker_Cap.jpg",
              "deployed": true,
              "deployedSite": "https://bill-track.firebaseapp.com/#/"
          },
          {
              "id": 3,
              "title": "Vocab Builder",
              "gitHub": "https://github.com/DavidNAspesi/Vocab-Builder-Client",
              "img": "https://s26.postimg.cc/vkgfvl76x/Screen_Shot_2018-06-07_at_1.14.43_PM.png",
              "deployed": true,
              "deployedSite": "http://vocabbuilder.surge.sh/"
          },
          {
              "id": 4,
              "title": "Fridge Vision",
              "gitHub": "https://github.com/SethCaparelli/fridge-vision",
              "img": "https://s26.postimg.cc/pyu0rcyqh/fridge-vision-icon.jpg",
              "deployed": false,
              "deployedSite": ""
          }
      ]
    }
  },
}
</script>

<style>
#app {
  font-family: 'PT Serif', serif;
}

#intro {
  height: 275px;
}

#about {
  height: 400px;
}

#portfolio {
  height: 600px;
}

#contact {
  height: 200px;
}
</style>
