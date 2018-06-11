<template>
    <div class="outerContainer">
        <div class="container">
            <h3>Let's connect!  Feel free to reach out to me at any of these places:</h3>
            <br>
            <div class="innerContainer">
                <a href="mailto:DavidNAspesi@gmail.com"><i class="fas fa-envelope-square fa-6x"></i></a>
                <a href="https://www.linkedin.com/in/DavidNAspesi"><i class="fab fa-linkedin fa-6x"></i></a>
                <a href="https://github.com/DavidNAspesi"><i class="fab fa-github-square fa-6x"></i></a>
                <a href="https://drive.google.com/file/d/1X0T-7-uHokbAvEiyTE9RlJdlnIqbqg8m/view?usp=sharing"><i class="fas fa-file-alt fa-5x"></i></a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "contactMe"
}
</script>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
}

.innerContainer {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-content: center;
}

.outerContainer {
    background-color: #2A9FD6;
}

a {
    color: black;
}

a:hover, a:visited {
    color: white;
}

h3 {
    text-align: center;
}

</style>

