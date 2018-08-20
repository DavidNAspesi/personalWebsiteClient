<template>
    <div class="container">
        <h3 class="titleP">My projects:</h3>
        <div class="container" style="display:flex;justify-content:space-around">
            <div class="card" style="width: 18rem;margin: 10px" v-for="(item, i) in items" :key="i">
                <img class="card-img-top" :src="item.img" :alt="item.title">
                <div class="card-body">
                    <h5 class="card-title">{{item.title}}</h5>
                    <p class="card-text">{{item.description}}</p>
                    <a :href="item.gitHub" class="btn btn-primary">See the code!</a>
                    <a class="btn btn-secondary" v-if="item.deployed" :href=item.deployedSite>See the deployed site!</a>
                </div>
            </div>
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

a {
    color: white;
}

.titleP {
    text-align: center;
}
</style>
