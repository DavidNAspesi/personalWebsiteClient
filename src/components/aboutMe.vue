<template>
    <div class="container bigContainer">
        <img alt="headshot" src="../assets/DSC_7864.png">
            <div class="subcontainer">
                <h4>Who is David Aspesi?</h4>
                <p>{{message}}</p>
                <h4>I am proficient in the following technologies:</h4>
                <p>On the front-end: {{frontEnd}}</p>
                <p>On the back-end: {{backEnd}}</p>
                <p>Techniques and methodology: {{techniques}}</p>
            </div>
    </div>
</template>

<script>
export default {
    name: "aboutMe",
    data() {
        return {
            message: "I am a life long learner, and a professional Full Stack Web Developer. Even though I am new to the industry, I am hungry to learn new and relevant technologies in order to solve your company's problems. When I worked as a coffee roaster, I made it my mission to learn everything I could in order to inform my own problem solving, and that attitude serves me equally well in the world of web development. I left one customer-facing, detail-oriented industry in order to join another!  If you're looking to add to your development team, let's connect!",
            frontEnd: "HTML5, CSS3, JavaScript, Vue.js, Cypress (for testing)",
            backEnd: "Node.js, Express, PostgresQL, Knex.js",
            techniques: "Building & interacting with RESTful APIs, Pair-programming, Agile Software Development"
        }

    }
}
</script>

<style scoped>
img {
    height: 2.5in;
    border: 3px;
    border-style: solid;
    border-color: #2A9FD6;
    margin-top: 1in;
}

p {
    font-size: large;
}

.bigContainer {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}

.subcontainer {
    margin: 25px 50px 50px 50px;
}
</style>
