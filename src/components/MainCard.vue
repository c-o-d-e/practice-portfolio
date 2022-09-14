<template>
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/blankprofile.png" alt="" />
                <h3>Name here</h3>
                <p>Front-end Engineer</p>
            </div>
            <div class="social-links">
                <div class="link">
                    <img src="../assets/Git.png" alt="" />
                    <a href=""><h2>GitHub</h2></a>
                </div>
                <div class="link">
                    <img src="../assets/linkedin.png" alt="" />
                    <a href=""><h2>LinkedIn</h2></a>
                </div>
            </div>
        </div>
        <div class="container-two">
            <div class="about-me">
                <h1>About Me</h1>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Quis nulla, consequatur officiis veritatis fugiat
                    repellendus ipsa iure aliquam deserunt voluptatum tempore
                    optio odio animi error nisi ratione adipisci architecto? Ad?
                </p>
            </div>
            <div class="technology-section">
                <h1>Technologies Studied</h1>
                <div class="logos">
                    <img src="../assets/html.svg" alt="html logo" />
                    <img src="../assets/css.svg" alt="css logo" />
                    <img
                        src="../assets/javascript-programming-language.svg"
                        alt="javascript logo"
                    />
                </div>
            </div>
            <div class="button-container">
                <div class="projects-button">
                    <a href="">My Projects</a>
                </div>
                <div>
                    <a href="">My Resume</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style scoped>
img {
    height: 20px;
}

.main-container {
    display: flex;
    flex-direction: row;
}

.container-one {
    width: 40%;
    padding: 2.5%;
}

.profile img {
    height: 5rem;
    border-radius: 50%;
}

.container-two {
    width: 60%;
}
</style>
