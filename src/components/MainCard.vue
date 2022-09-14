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
                    <a href="">
                        <img src="../assets/Git.png" alt="" />
                        <h2>GitHub</h2></a
                    >
                </div>
                <div class="link">
                    <a href="">
                        <img src="../assets/linkedin.png" alt="" />
                        <h2>LinkedIn</h2></a
                    >
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
                <div class="projects-button">
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
    height: 2rem;
}

.main-container {
    display: flex;
    flex-direction: row;
    background-color: rgba(214, 214, 214, 0.5);
    border-radius: 20px;
}

.container-one {
    width: 40%;
    padding: 2.5%;
    background-color: rgba(255, 192, 203, 0.552);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    border-radius: 20px;
}

.profile img {
    height: 5rem;
    border-radius: 50%;
}

.container-two {
    width: 60%;
    background-color: rgba(81, 62, 208, 0.2);
    margin: 1rem;
}

.technology-section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    margin: auto;
    text-align: center;
}

.logos {
    margin: auto;
}

.logos img {
    margin: 0.5rem;
}

.button-container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0.5rem;
}

.projects-button {
    background-color: #7c58ff;
    padding: 0.2rem;
    margin: 5px;
    width: 50%;
    text-align: center;
    border-radius: 10px;
}

.projects-button a {
    text-decoration: none;
    color: white;
}
</style>
