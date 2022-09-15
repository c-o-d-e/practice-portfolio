<template>
    <div class="main-container">
        <div
            class="projects"
            v-for="items in projectData.ProjectsArray"
            v-bind:key="items"
        >
            <h2>{{ items.Title }}</h2>
            <img :src="items.Image" alt="image" />
            <p>{{ items.About }}</p>
            <p>Tech Stack: {{ items.Stack }}</p>
            <div class="button-container">
                <a :href="items.Link1" target="_blank" class="projects-button"
                    >Live</a
                >

                <a href="" class="projects-button">Code</a>
            </div>
        </div>
    </div>
</template>

<script>
import jsonData from "../../projects.json";
export default {
    data() {
        return {
            projectData: jsonData,
        };
    },
};
</script>

<style scoped>
.main-container {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

.projects {
    text-align: center;
    box-shadow: 0px 5px 10px 0px rgba(0, 255, 255, 0.4);
    border-radius: 20px;
    margin: 1rem;
}

.projects img {
    height: 300px;
}
</style>
