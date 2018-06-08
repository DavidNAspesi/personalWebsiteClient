<template>
    <div class="container">
        <div id="header-carousel" style="display:flex;justify-content:center">
            <v-carousel style="width:640px">
                <v-carousel-item v-for="(item, i) in items" :src="item.img" :key="i" style="height:480px;width:640px;background-color:#555">
                <v-container fill-height >
                    <v-layout align-center>
                    <v-flex style="display:flex;flex-direction:column">
                        <h3 class="display-3">{{ item.title }}</h3>
                        <a class="subheading" v-if="item.deployed" :href=item.deployedSite>See the deployed site!</a><br>
                        <a class="subheading" :href=item.gitHub>Go to this project's GitHub Repository</a>
                    </v-flex>
                    </v-layout>
                </v-container>
                </v-carousel-item>
            </v-carousel>
        </div>
    </div>
</template>

<script>
export default {
    name: "portfolio",
    props: [
        "items"
            ]
}
</script>

<style scoped>
h3, a {
    align-self: center;
}
</style>
