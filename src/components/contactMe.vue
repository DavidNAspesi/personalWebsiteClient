<template>
    <div class="outerContainer">
        <div class="container">
            <h4>Let's connect!  Feel free to reach out to me at any of these places:</h4>
            <br>
            <div class="innerContainer">
                <a href="mailto:DavidNAspesi@gmail.com"><i class="fas fa-envelope-square fa-6x"></i></a>
                <a href="https://www.linkedin.com/in/DavidNAspesi" target="_blank"><i class="fab fa-linkedin fa-6x"></i></a>
                <a href="https://github.com/DavidNAspesi" target="_blank"><i class="fab fa-github-square fa-6x"></i></a>
                <a href="https://drive.google.com/file/d/1X0T-7-uHokbAvEiyTE9RlJdlnIqbqg8m/view?usp=sharing" target="_blank"><i class="fas fa-external-link-square-alt fa-6x"></i></a>
            </div>
            <br>
            <p>&copy; 2018 David Aspesi</p>
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
    padding-bottom: 0px;
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

h4 {
    text-align: center;
}

p {
    text-align: center;
    color: black;
}

.fa-file-alt {
    align-self: center;
}
</style>

