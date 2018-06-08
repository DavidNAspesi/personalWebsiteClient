<template>
    <div class="container">
        <img alt="headshot" src="../assets/DSC_7864.png">
            <div class="subcontainer">
                <h1>Who is David Aspesi?</h1>
                <p>It me</p>
            </div>
    </div>
</template>

<script>
export default {
    name: "aboutMe"
}
</script>

<style scoped>
img {
    height: 2in;
    border: 3px;
    border-style: solid;
    border-color: #2A9FD6;
}

.container {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}
</style>
